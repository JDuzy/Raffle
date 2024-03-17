# Lottery

## Project overview

The objective of this project was to learn foundry and oracle interaction with Chainlink with CEI Pattern for more secure smart contracts.

Using chainlink VRF & Chainlink automation.

- Chainlink VRF -> Randomness
- Chainlink automation -> Time based trigger

1. Users can enter a raffle by paying a ticket.
   The tickets fees are going to the winner during the draw.

2. After X period of time, the lottery will automatically draw a winner

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```
