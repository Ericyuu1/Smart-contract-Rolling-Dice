# Smart-contract-Rolling-Dice
The smart contract should emulate a dice roll. In other words, the contract should enable the
computation of a random number n in the range [1, 6]. If n is 1, 2, or 3, then A wins; otherwise, B
wins. If A wins, A is rewarded n ETH; if B wins, B is rewarded (n - 3) ETH. After a game ends, two
new players should be able to start a new game on the same contract.
Example. Two players, A and B, each with 100 ETH in their wallets, start a game. The produced
number is 5, so B wins. After the game ends, B’s balance is 102 ETH (minus some gas fees,
perhaps, if necessary).
