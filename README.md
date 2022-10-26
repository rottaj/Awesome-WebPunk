# Awesome-WebPunk
#### Not-so curated list of things I've read over the years. Want to contribute? Open a PR or send me a message!

## Me:
- [0x402d8602ef11324bfbb53f7b7ad3acf2c02875e5](https://etherscan.io/address/0x402d8602ef11324bfbb53f7b7ad3acf2c02875e5) - ERC20 & ETH
- [rotta.eth](https://etherscan.io/enslookup-search?search=rotta.eth) - ENS 

- [Website](https://rottaj.github.io/)
- [PGP]()
- [GPG]()
- [Config](https://github.com/rottaj/config)

## Awesome Reading List
#### Books
- [Cryptonomicon](https://en.wikipedia.org/wiki/Cryptonomicon)
- [Snow Crash](https://en.wikipedia.org/wiki/Snow_Crash)
- [Siddhartha](https://en.wikipedia.org/wiki/Siddhartha_(novel))
- [On The Road](https://en.wikipedia.org/wiki/On_the_Road)
- [Dharma Bums](https://en.wikipedia.org/wiki/The_Dharma_Bums)
- [Greenlights](https://greenlights.com/)

#### Research Papers
- [How to read a paper](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf) - Helpful tips
(Will update this, gonna take a while)

#### Blogs & Other
- [xkcd](https://xkcd.com/)
- [Pluriverse](https://www.ehu.eus/documents/6902252/12061123/Ashish+Kothari+et+al-Pluriverse+A+Post-Development+Dictionary-2019.pdf/c9f05ea0-d2e7-8874-d91c-09d11a4578a2) A Post-Development Dictionary
- [Unqualified Reservations](https://www.unqualified-reservations.org/) 



## Basics
- [OSI Model](https://www.imperva.com/learn/application-security/osi-model/#:~:text=What%20Is%20the%20OSI%20Model,companies%20in%20the%20early%201980s)
- [Concurrency](https://web.mit.edu/6.005/www/fa14/classes/17-concurrency/#:~:text=There%20are%20two%20common%20models,writing%20shared%20objects%20in%20memory.)

#### Design Implementations / Patterns
- [Stateful Vs. Stateless](https://www.thegeeksclan.com/being-stateful-and-stateless/)




## Cryptography

#### Asymmetric Encryption
- [Elliptic Curve (ECC)](https://medium.com/coinmonks/learn-how-to-code-elliptic-curve-cryptography-a952dfdc20ab) - Public-key cryptosystems based on the algebraic structure of elliptic curves over finite fields.
- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) - One of the first practical public-key cryptosystems and is widely used for secure data transmission. In RSA, this asymmetry is based on the practical difficulty of factoring the product of two large prime numbers, the factoring problem.

#### Symmetric Encryption
- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - Symmetric-key block cipher (or Triple Data Encryption Algorithm (TDEA or Triple DEA), which applies the Data Encryption Standard (DES) cipher algorithm three times to each data block.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - Symmetric-key block cipher algorithm and U.S. government standard for secure and classified data encryption and decryption (also known as Rijndael).
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher)) - Symmetric-key block cipher, designed in 1993 by Bruce Schneier. Notable features of the design include key-dependent S-boxes and a highly complex key schedule.


#### Digital Signatures
- [ECDSA]()
- [Schnorr Digigal Signature]()

#### Hash Functions
- [MD5](https://en.wikipedia.org/wiki/MD5) - Widely used hash function producing a 128-bit hash value. MD5 was initially designed to be used as a cryptographic hash function, but it has been found to suffer from extensive vulnerabilities. It can still be used as a checksum to verify data integrity, but only against unintentional corruption.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1) -  Cryptographic hash function designed by the NSA. SHA-1 produces a 160-bit hash value known as a message digest. SHA-1 is no longer considered secure against well-funded opponents.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2) - Set of hash functions designed by the NSA. SHA-256 and SHA-512 are novel hash functions computed with 32-bit and 64-bit words, respectively. They use different shift amounts and additive constants, but their structures are otherwise virtually identical, differing only in the number of rounds.

#### Other
- [Merkle Tree Whitepaper](https://people.eecs.berkeley.edu/~raluca/cs261-f15/readings/merkleodb.pdf) 
- [Signatures in Ethereum](https://medium.com/immunefi/intro-to-cryptography-and-signatures-in-ethereum-2025b6a4a33d#:~:text=elliptic%20curve%20cryptography.-,Digital%20Signatures,the%20hash%20of%20the%20message) - Intro to cryptography & signatures in Ethereum



## Zero-Knowledge
- [Zero Knowledge Proofs](https://ethereum.org/en/zero-knowledge-proofs/) - Ethereum.org's "What are zero-knowledge proofs?"
- [Shafi Goldwasser - Interactive Proofs](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.419.8132&rep=rep1&type=pdf)
- [Pinocchio Protocol](https://eprint.iacr.org/2013/279.pdf) - First usable implementation of a Zk-Snark
- [STARKS vs SNARKS](https://consensys.net/blog/blockchain-explained/zero-knowledge-proofs-starks-vs-snarks/)
- [Dark Forest ZKPs](https://blog.zkga.me/intro-to-zksnarks) - ZDKGA's Introduction to Zero Knowledge Proofs
- [ZkSnarks in a nutshell](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell) - Ethereum Foundations Introduction to ZkSnarks
- [Serving up ZKP's](https://blog.trailofbits.com/2021/02/19/serving-up-zero-knowledge-proofs/) - Trail of Bits ZKP Blog Post
- [Fiat-Shamir Heururistic](https://eprint.iacr.org/2016/771.pdf) - Interesting paper on ZKP's & Fiat-Shamir Heuristic
- [Vitalik.ca Pt.1](https://vitalik.ca/general/2017/11/09/starks_part_1.html) - Vitalik Buterin's STARK Blog Pt. 1
- [Vitalik.ca Pt.2](https://vitalik.ca/general/2017/11/22/starks_part_2.html) - Vitalik Buterin's STARK Blog Pt. 2
- [Vitalik.ca Pt.3](https://vitalik.ca/general/2018/07/21/starks_part_3.html) - Vitalik Buterins's STARK Blog Pt.3
- [Why & How zk-SNARK Works](https://arxiv.org/pdf/1906.07221.pdf) - Definitive Explanation of zk-SNARK Technology

- [Zero Knowledge Blog](https://www.zeroknowledgeblog.com/) - Great blog for Zero Knowledge
- [Dark Forest Blog](https://blog.zkga.me/) - Dark Forest's Blog on ZKP's
- [Makysym - Medium](https://medium.com/@imolfar) - More great blog posts for Zero Knowledge

#### ZkEVM
- [What is a ZkEVM?](https://www.alchemy.com/overviews/zkevm) - Alchemy introduction.
- [Different types of ZkEVMS](https://www.alchemy.com/overviews/zkevm) - Vitaliks blog.
- [Popular zKEVM Solutions](https://hackernoon.com/exploring-popular-zkevm-solutions-appliedzkp-matter-labs-hermez-and-sin7y-quick-publication-ltq37ah)



#### Validity (Zk) Rollup Solutions
- [Scroll](https://scroll.io/)
-- [How scroll works](https://twitter.com/ChrisYicheng/status/1569266811635642369) - Thread
- [ZkSync](https://zksync.io/)
- [Starkware](https://starknet.io/docs/)
- [Polygon Zero](https://polygon.technology/solutions/polygon-zero/)

## Optimistic Rollup Solutions
- [Arbitrum](https://bridge.arbitrum.io/)
- [Optimism](https://www.optimism.io/)
- [Boba Network](https://boba.network/)

## More Solutions
- [ZkPorter](https://blog.matter-labs.io/zkporter-a-breakthrough-in-l2-scaling-ed5e48842fbf)
- [Proto-Danksharding](https://notes.ethereum.org/@vbuterin/proto_danksharding_faq)

- ## MEV





## Tokens
- [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Token contract for fungible assets.
- [ERC-721](https://github.com/ethereum/eips/issues/721) - Token standard for non-fungible assets.
- [ERC-1155](https://eips.ethereum.org/EIPS/eip-1155) - Multi Token standard for semi-fungible tokens.
- [ERC-1363](https://eips.ethereum.org/EIPS/eip-1363) - Payable Token Standard.
- [ERC-4626](https://eips.ethereum.org/EIPS/eip-4626) - Tokenized Vault Standard.
- [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - A standard interface for a simple proxy account.

## Other
- [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559) - Fee Market change for efficient transactions.
- [EIP-4337](https://eips.ethereum.org/EIPS/eip-4337) - Account Abstraction using alternate mempool.
- [EIP-3675](https://eips.ethereum.org/EIPS/eip-3675) - Upgrade consensus to Proof-of-Stake.
- [EIP-4844](https://www.eip4844.com/) - Proto-Danksharding


## Frameworks
#### Ethereum
- [Hardhat](https://hardhat.org/) - Ethereum Toolskit (Javascript)
- [Foundry](https://github.com/foundry-rs/foundry) - Ethereum Toolkit (Rust)

#### Frontend
- [NextJS](https://nextjs.org/) - Full-Stack React & NodeJs Framework
- [React](https://reactjs.org/) - Javascript Library 
- [ChakraUI](https://chakra-ui.com/) - Components for react
- [React Query](https://tanstack.com/query/v4/?from=reactQueryV3&original=https://react-query-v3.tanstack.com/) - State managment tooling.

## Fun 
#### Blockchain
- [Degenscore](https://degenscore.com/) - Show off your degen profile
- [Dark Forest](https://zkga.me/) - zkSNARK Space Warfare RTS
- [0xdead burn address](https://etherscan.io/address/0x000000000000000000000000000000000000dead) - etherscan
- [PoS validator deposit contract](https://etherscan.io/address/0x00000000219ab540356cbb839cbe05303d7705fa) - etherscan
- [Time challenge](https://twitter.com/paladin_marco/status/1584538632810942464) - Twitter thread
#### Other
- [Pablo The Flamingo](https://pablotheflamingo.com/) - Too cool 4 school


## CTF's
- [Ethernaut](https://ethernaut.openzeppelin.com/) - OpenZeppelin Ethernaut Challenges
- [Proto Hackers](https://protohackers.com/problems) - ProtoHackers CTF Challenges
- [H4CK1NG GOOGLE](https://h4ck1ng.google/home) - 2022 Google CTF Challenges

## Ethereum Clients
- [Geth](https://geth.ethereum.org/docs/) - Golang Execution client

## Communities, Teams, & Labs
#### Telegram channels
- [Netsec](https://t.me/RNetsec)
- [RektHQ](https://t.me/Rekt_HQ)
- [CIA Officers X-Files](https://t.me/Rekt_HQ)
- [Hacker News](https://t.me/hackernewslive)

#### Sites
- [Matter Labs](https://matter-labs.io/) - Creators of zKSync.
- [0xPark](https://0xpark.com/) - Metaverse creative studio. (Creators of Dark Forest).
- [Pluriverse.wtf](https://pluriverse.wtf/) - Creators of Moloch DAO (Baal).

