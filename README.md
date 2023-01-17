# Donation

## Overview

The case shows how a community of users, within the Humanitarian space, can create and deliver donations following the principles of accountability and traceability.

For simplification, there are no restrictions about who can connect ('following') with who and the connection is accepted directly. However, in a real scenario, there should be the possibility to accept/reject/cancel an invitation to connect.

Basically a donation can be firstly created and subsequently transferred until reaches the final destination who is a beneficiary.

As a donation has an 'issuer' and an 'owner' and along with the archived contracts, the proposed solution can enforce traceability and accountability in the Humanitarian space.

## Workflow

1. Donors can start following NGOs with `Follow` choice.
2. NGOs can start following Beneficiaries with `Follow` choice.
3. Donors create a donations.
4. Donors create proposals to transfer a donation to a connected NGOs.
5. Donors can Cancel proposals by excercising that choice.
6. NGOs can Accept/Reject a proposal by excercising the corresponding choice.
7. NGO create proposals to transfer a donation to a connected Beneficiaries.
8. NGO can Cancel proposals by excercising that choice.
9. Beneficiaries can Accept/Reject a proposal by excercising the corresponding choice.

## Building

To compile the project:

```
daml build
```

## Testing

The model is tested for positive and negative scenarios.
