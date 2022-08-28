## Token Processor
This is microservice processing tokens for reciepts, slips, envelopes and coupons. Utilizes blinded tokens

## Objects

### Keys
Every chain and asset will have its own key
Properties:
- duration
- overlap
- count
- ephermal

### Issuers
Signer associated to key
- Parent Key
- Signing key

### Redemption
Proof of redemption
- Parent Issuer
- id

## Endpoints
- Sign
    - request
    - fetch
- Redeem
    - request
    - check
- Keys
    - create
    - filter