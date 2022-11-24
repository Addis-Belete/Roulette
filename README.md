# On-chain Roulette

> On-chain roulette generate random numbers. and it is deployed on to Goerli.

The smart contract:-
1. Allow anyone to initiate new games if they pay the minimum stake.
2. Use Chainlink VRFv2 to generate a truly random number.
3. Allow winners to claim their prizes once the game has finished.

## Instructions: 
On-chain Roulette considerations:
1. Available numbers are `0-36`.
2. Available colors are `BLACK` (even numbers), `RED` (odd numbers). Note that `ZERO` would be the "no-color" option when the number is 0.
3. Players can only bet on a single outcome per game: either a number or a color (0 counts as a number).
4. If a player bets on a number and wins, the prize is `stake * 36`.
5. If a player bets on a color and wins, the prize is `stake * 2`.

## Built With

- Solidity
- Chainlink VRFv2
- Foundry

## Install

```
$ forge install

```

## Getting Started

## To get local copy up and running follow these simple example steps

```
- git clone git@github.com:Addis-Belete/Crowd_Funding.git
- npm install
```


👤 **Addis Belete**

- GitHub: [@Addis0943](https://github.com/Addis0943)
- Twitter: [@Addis32018084](https://twitter.com/Addis32018084)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/addis-belete-134b98191/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](./MIT.md) licensed.



