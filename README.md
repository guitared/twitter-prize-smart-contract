# twitter-prize-smart-contract
Transparency design for twitter random winner using smart contract

## User Story
- Donator
  - provide twitter status URL
  - specify actions (e.g. require follow, require retweet, require like)
  - specify campaign ending condition (trigger time or manual execution)
  - specify currency and amount
  - transfer prize to smart contract (initialize the contract)

- Smart Contract
  - TODO: update smart contract user story
  
- Player
  - follow instruction (required actions) in twitter status
  - register in a contract as player by providing wallet deposit address
  - wait for campaign ending
  
- Donator
  - manually end the campaign (if needed)
  
- Smart Contract
  - random winner
  - check the condition by calling twitter API
  - broadcast winner

- Winner
  - Claim the prize and pay the gas
