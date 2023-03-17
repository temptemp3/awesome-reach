## Awesome Reach - Challenges

Reach challenges. Monetary incentives for challenges may be expired. Taking a stab before watching the video is recommended.

## The Vault

* [Challenge: Vault](https://github.com/temptemp3/awesome-reach/blob/main/challenge/challenge-vault.pdf)

Video: [The Vault Challenge (YouTube)](https://www.youtube.com/watch?v=loNxrgahOc8)

## NFT Raffle

* [Challenge: NFT Raffle](https://github.com/temptemp3/awesome-reach/blob/main/challenge/challenge-nft-raffle.pdf)

Video: [NFT Raffle (YouTube)](https://youtu.be/vqZGqPtIrro)

Questions:

* Should the winning number be selected before or after the raffle?
  * Yes
    * To be trustless
    * Question: Can you cheat by figuring out what the *hidden* number is before it is picked out?  
    * Implementation: See [digest](https://docs.reach.sh/rsh/compute/#rsh_digest)
  * No
    * A real raffle is picked at the end
    * Implementation: consider offchain random selection, onchain oracle call, or both
