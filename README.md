# InviteToken

## Project Title
**InviteToken (ITK)**

## Project Description
InviteToken is a simple and efficient ERC-20 smart contract designed to incentivize user engagement and participation through an invite-based reward system. By integrating a token economy, InviteToken empowers owners to reward users for inviting others to their platform or service. The token adheres to the widely used ERC-20 standard, making it compatible with most Ethereum-based applications.

## Contract Address
0xDc65F5724c5CAdc81feAC18954d97E7482F5AF89
![image](https://github.com/user-attachments/assets/df0e3975-1f5d-44a7-9e23-d0a8d249ebb6)


## Project Vision
InviteToken aims to facilitate growth and engagement within decentralized ecosystems by providing a reliable and straightforward reward mechanism. It seeks to:

- Enhance community-building efforts.
- Enable decentralized platforms to incentivize user acquisition effectively.
- Promote the use of blockchain technology for fostering trust and transparency.

## Key Features
1. **ERC-20 Standard Compliance**: InviteToken is fully compatible with the Ethereum ecosystem.
2. **Invite Reward System**: Users can invite others and reward them with tokens using the `inviteLearner` function.
3. **Ownership Control**: The owner has the ability to manage the total supply effectively.
4. **Token Transfer Capabilities**: Supports token transfers between users and allowances via `transfer` and `transferFrom` functions.
5. **Customizable Supply**: The initial supply of tokens can be set during contract deployment.
6. **Transparency and Security**: All token interactions are logged through events such as `Transfer`, `Approval`, and `Invited`.

## Usage Examples
### Transferring Tokens
Users can transfer tokens to other addresses using the `transfer` function:
```solidity
function transfer(address _to, uint256 _value) public returns (bool success);
```

### Approving and Delegating Transfers
Token owners can delegate transfer permissions using the `approve` and `transferFrom` functions:
```solidity
function approve(address _spender, uint256 _value) public returns (bool success);
function transferFrom(address _from, address _to, uint256 _value) public returns (bool success);
```

### Rewarding Invites
Owners can reward invitees via the `inviteLearner` function:
```solidity
function inviteLearner(address _invitee, uint256 _reward) public returns (bool success);
```

## Deployment
This contract is written in Solidity (version ^0.8.0). To deploy the contract, use any Ethereum-compatible IDE or deployment tools such as Remix or Hardhat, and specify the desired initial token supply.


