## Solidity-beach-rental

#### Solidity smart contract example

A smart contract for a beach vacation property rental. This is in development (*i.e.* not extensively tested for deploying on the Ethereum mainnet). It has been tested using [Remix](https://remix.ethereum.org).

----
#### Basic instructions to run:
1) Open [Remix](https://remix.ethereum.org) and deploy the contract as owner.

2) Switch to a new Account for renter and populate the reserve function. For example:

![reserve](reserve.png)

3) Run rentalTotal and paste the value (in wei) to Value at top.

4) Ensure the selected Account is for renter and run deposit:

![deposit](deposit.png)

5) Switch back to owner Account and run withdraw with the rentalTotal amount.
