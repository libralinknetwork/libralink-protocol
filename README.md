# Libralink Protocol v1

## Context

<p align="center">
    <img src="./resources/UC_Cross_Border.png" width="75%" height="75%"/>
</p>

## API Endpoints
- `GET /processors/trusted` - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
- `POST /payer/echeck-pre-issue`
- `POST /payer/echeck-issue`
- `POST /payee/request`
- `POST /payee/echeck-deposit`

## API Object Model

<p align="center">
    <img src="./resources/Libralink_Protocol_Simplified.png" width="100%" height="100%"/>
</p>

## Details
### Processing Fee
TBD

##### Total Amount
TBD

### Error Message
TBD 

#### Errors
- `100` - Insufficient funds
- `200` - Invalid Payer signature
- `201` - Invalid Payee signature
- `9xx` - Extension, user defined error codes

## Use Cases

### Payee initiated Payment
<p align="center">
    <img src="./resources/UC_Payee_Initiated_Payment.png" width="50%" height="50%" />
</p>

TBD

### Payer initiated Payment

<p align="center">
    <img src="./resources/UC_Payer_Initiated_Payment.png" width="50%" height="50%" />
</p>

TBD

### Payee deposits E-Check
<p align="center">
    <img src="./resources/UC_Payee_Deposits_Check.png" width="75%" height="75%" />
</p>

### Partial Internet Access
TBD

### Offline Payment (neither Payee, not Payer have Internet Access)

<p align="center">
    <img src="./resources/UC_No_Internet.png" width="75%" height="75%" />
</p>

