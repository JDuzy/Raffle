# Raffle smart contract

## Project overview

The objective of this project was to learn foundry and oracle interaction with Chainlink.

Using chainlink VRF & Chainlink automation.

- Chainlink VRF -> Randomness
- Chainlink automation -> Time based trigger

## Use cases
1. Users can enter a raffle by paying a ticket.
   The tickets fees are going to the winner during the draw.

2. After X period of time, the lottery will automatically draw a winner.

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```
