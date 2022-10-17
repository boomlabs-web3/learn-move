# learn-move
This repository is for developers willing to learn move-language, aptos, or sui themselves.

This repository is inspired by [Teach Yourself Move] and [Awesome Move].

## Roadmap for Onboarding in Aptos & Sui

### Recommended sequence

* Items marked `read` are to be completed before the beginning of the next item, but may be begun before the prior item.
  * It may be easier to break up reading and start early, interspersing with tutorials.
* When a tutorial is marked `do`, re-write all code.
  * Do not download sample code.
  * Do not copy-paste.
  * If necessary, running from within a provided repo is necessary as long as it is solely in the interest of duplicating behavior to be expected from the already re-written repo.
* When an item is marked `explore`, consider the following:
  * Re-implement examples but with modifications.
  * Create your own new examples using the provided library/framework.
  * Read whatever seems interesting!

| Move                                                            | Aptos                               | Sui                                            |
|-----------------------------------------------------------------|-------------------------------------|------------------------------------------------|
| **Introduce to Move**                                           |                                     |                                                | 
| [x] `read` [This Roadmap's instructions](#recommended-sequence) |                                     |                                                | 
| [ ] `do` [Move official tutorial]                               |                                     |                                                |
| [ ] `read` [Move Prover User Guide]                             |                                     |                                                |
| [ ] `read` [Move Specification Language]                        |                                     |                                                |
| [ ] `do` [Zellic's Move  Prover tutorial]                       |                                     |                                                |
| [ ] `explore` the [Move prover][move-prover]                    |                                     |                                                |
| [ ] `read` [Xangle’s Comparison Article (KR)]                   |                                     |                                                |
| [ ] `read` [Aptos Labs' Block-STM Article]                      |                                     |                                                |
| [ ] `read` [Block-STM paper] (sections 1 & 2)                   |                                     |                                                |
| **Installation**                                                |                                     |                                                | 
|                                                                 | [ ] `do` [Getting started]          | [ ] `do` [Building Sui]                        |
| **Using CLI tools**                                             |                                     |                                                | 
|                                                                 | [ ] `do` [Using Aptos CLI]          | [ ] `do` [Use Sui CLI]                         |
| **Creating Transaction via RPC**                                |                                     |                                                | 
|                                                                 | [ ] `read` [Transactions and states]| [ ] `do` [Connect to Sui Devnet]               |
|                                                                 | [ ] `do` [Your first transaction]   | [ ] `do` [Sui TicTacToe]                       |
|                                                                 | [ ] `read` [Accounts]               |                                                |
|                                                                 | [ ] `do` [Your first NFT]           |                                                |
| **Build Move Module**                                           |                                     |                                                | 
| [ ] `read` [Move book] (Introduction-4)                         |                                     |                                                |
| [ ] `do` [move-cli] embedded tutorial                           |                                     |                                                |
| [ ] `read` [Move book] (chapters 5-9)                           | [ ] `do` [Your first Move module]   | [ ] `do` [Write Smart Contracts with Sui Move] |
| [ ] `read` [Move book] (chapters 10-14)                         | [ ] `do` [Your first dApp]          | [ ] `do` [Programming Objects Tutorial]        |
| [ ] `read` [Move book] (chapters 15-19)                         | [ ] `do` [Your first coin]          |                                                |
| [ ] `read` [Move book] (chapters 20-23)                         | [ ] `explore` the [Aptos framework] |                                                |
| [ ] `read` [Move book] (chapters 24-27)                         |                                     |                                                |
| **Node Operation**                                              |                                     |                                                |
|                                                                 | [ ] `explore` [Nodes Home]          | [ ] `do` [Talk with Sui]                       |

<!-- Alphabetized reference links -->

[Accounts]:                             https://aptos.dev/concepts/basics-accounts
[Aptos Labs' Block-STM Article]:        https://medium.com/aptoslabs/block-stm-how-we-execute-over-160k-transactions-per-second-on-the-aptos-blockchain-3b003657e4ba
[Awesome Move]:                         https://github.com/MystenLabs/awesome-move
[Block-STM paper]:                      https://arxiv.org/pdf/2203.06871.pdf
[Building Sui]                          https://docs.sui.io/build
[Connect to Sui Devnet]                 https://docs.sui.io/build/devnet
[Getting started]:                      https://aptos.dev/guides/getting-started
[Move book]:                            https://move-language.github.io/move/introduction.html
[move-cli]:                             https://github.com/move-language/move/tree/main/language/tools/move-cli
[move-prover]:                          https://github.com/move-language/move/tree/main/language/move-prover
[Move official tutorial]:               https://github.com/move-language/move/tree/main/language/documentation/tutorial
[Move Prover User Guide]:               https://github.com/move-language/move/blob/main/language/move-prover/doc/user/prover-guide.md
[Move Specification Language]:          https://github.com/move-language/move/blob/main/language/move-prover/doc/user/spec-lang.md
[Nodes Home]                            https://aptos.dev/nodes/nodes-landing/
[Sui TicTacToe]                         https://docs.sui.io/explore/tutorials
[Talk with Sui]                         https://docs.sui.io/build/comms
[Teach Yourself Move]:                  https://github.com/econia-labs/teach-yourself-move
[Transactions and states]:              https://aptos.dev/concepts/basics-txns-states
[Use Sui CLI]|                          https://docs.sui.io/devnet/build/cli-client
[Using Aptos CLI]                       https://aptos.dev/cli-tools/aptos-cli-tool/use-aptos-cli/
[Write Smart Contracts with Sui Move]:  https://docs.sui.io/build/move
[Xangle’s Comparison Article (KR)]:     https://xangle.io/insight/research/62e34d357a80905a1f4749c5
[Your first coin]:                      https://aptos.dev/tutorials/your-first-coin
[Your first dApp]:                      https://aptos.dev/tutorials/your-first-dapp/
[Your first transaction]:               https://aptos.dev/tutorials/your-first-transaction
[Your first Move module]:               https://aptos.dev/tutorials/first-move-module
[Your first NFT]:                       https://aptos.dev/tutorials/your-first-nft/
[Zellic's Move Prover tutorial]:        https://github.com/zellic/move-prover-examples
