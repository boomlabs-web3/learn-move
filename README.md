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

| Move                                                                     | Aptos                                         | Sui                                                     |
|--------------------------------------------------------------------------|-----------------------------------------------|---------------------------------------------------------|
| **Introduce to Move**                                                    |                                               |                                                         | 
| <li>[x] `read` [This Roadmap's instructions](#recommended-sequence)</li> |                                               |                                                         | 
| <li>[ ] `do` [Move official tutorial]</li>                               |                                               |                                                         |
| <li>[ ] `read` [Move Prover User Guide]</li>                             |                                               |                                                         |
| <li>[ ] `read` [Move Specification Language]</li>                        |                                               |                                                         |
| <li>[ ] `do` [Zellic's Move  Prover tutorial]</li>                       |                                               |                                                         |
| <li>[ ] `explore` the [Move prover][move-prover]</li>                    |                                               |                                                         |
| <li>[ ] `read` [Xangle’s Comparison Article (KR)]</li>                   |                                               |                                                         |
| <li>[ ] `read` [Aptos Labs' Block-STM Article]</li>                      |                                               |                                                         |
| <li>[ ] `read` [Block-STM paper] (sections 1 & 2)</li>                   |                                               |                                                         |
|                                                                          |                                               |                                                         |
| **Installation**                                                         |                                               |                                                         | 
|                                                                          | <li>[ ] `do` [Getting started]</li>           | <li>[ ] `do` [Building Sui]</li>                        |
|                                                                          |                                               |                                                         |
| **Using CLI tools**                                                      |                                               |                                                         | 
|                                                                          | <li>[ ] `do` [Using Aptos CLI]</li>           | <li>[ ] `do` [Use Sui CLI]</li>                         |
|                                                                          |                                               |                                                         |
| **Creating Transaction via RPC**                                         |                                               |                                                         | 
|                                                                          | <li>[ ] `read` [Transactions and states]</li> | <li>[ ] `do` [Connect to Sui Devnet]</li>               |
|                                                                          | <li>[ ] `do` [Your first transaction]</li>    | <li>[ ] `do` [Sui TicTacToe]</li>                       |
|                                                                          | <li>[ ] `read` [Accounts]</li>                |                                                         |
|                                                                          | <li>[ ] `do` [Your first NFT]</li>            |                                                         |
|                                                                          |                                               |                                                         |
| **Build Move Module**                                                    |                                               |                                                         | 
| <li>[ ] `read` [Move book] (Introduction-4)</li>                         |                                               |                                                         |
| <li>[ ] `do` [move-cli] embedded tutorial</li>                           |                                               |                                                         |
| <li>[ ] `read` [Move book] (chapters 5-9)</li>                           | <li>[ ] `do` [Your first Move module]</li>    | <li>[ ] `do` [Write Smart Contracts with Sui Move]</li> |
| <li>[ ] `read` [Move book] (chapters 10-14)</li>                         | <li>[ ] `do` [Your first dApp]</li>           | <li>[ ] `do` [Programming Objects Tutorial]</li>        |
| <li>[ ] `read` [Move book] (chapters 15-19)</li>                         | <li>[ ] `do` [Your first coin]</li>           |                                                         |
| <li>[ ] `read` [Move book] (chapters 20-23)</li>                         | <li>[ ] `explore` the [Aptos framework]</li>  |                                                         |
| <li>[ ] `read` [Move book] (chapters 24-27)</li>                         |                                               |                                                         |
|                                                                          |                                               |                                                         |
| **Node Operation**                                                       |                                               |                                                         |
|                                                                          | <li>[ ] `explore` [Nodes Home]</li>           | <li>[ ] `do` [Talk with Sui]</li>                       |


<!-- Alphabetized reference links -->

[Accounts]:                             https://aptos.dev/concepts/basics-accounts
[Aptos framework]:                      https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/framework
[Aptos Labs' Block-STM Article]:        https://medium.com/aptoslabs/block-stm-how-we-execute-over-160k-transactions-per-second-on-the-aptos-blockchain-3b003657e4ba
[Awesome Move]:                         https://github.com/MystenLabs/awesome-move
[Block-STM paper]:                      https://arxiv.org/pdf/2203.06871.pdf
[Building Sui]:                         https://docs.sui.io/build
[Connect to Sui Devnet]:                https://docs.sui.io/build/devnet
[Getting started]:                      https://aptos.dev/guides/getting-started
[Move book]:                            https://move-language.github.io/move/introduction.html
[move-cli]:                             https://github.com/move-language/move/tree/main/language/tools/move-cli
[move-prover]:                          https://github.com/move-language/move/tree/main/language/move-prover
[Move official tutorial]:               https://github.com/move-language/move/tree/main/language/documentation/tutorial
[Move Prover User Guide]:               https://github.com/move-language/move/blob/main/language/move-prover/doc/user/prover-guide.md
[Move Specification Language]:          https://github.com/move-language/move/blob/main/language/move-prover/doc/user/spec-lang.md
[Nodes Home]:                           https://aptos.dev/nodes/nodes-landing/
[Programming Objects Tutorial]:         https://docs.sui.io/build/programming-with-objects
[Sui TicTacToe]:                        https://docs.sui.io/explore/tutorials
[Talk with Sui]:                        https://docs.sui.io/build/comms
[Teach Yourself Move]:                  https://github.com/econia-labs/teach-yourself-move
[Transactions and states]:              https://aptos.dev/concepts/basics-txns-states
[Use Sui CLI]:                          https://docs.sui.io/devnet/build/cli-client
[Using Aptos CLI]:                      https://aptos.dev/cli-tools/aptos-cli-tool/use-aptos-cli/
[Write Smart Contracts with Sui Move]:  https://docs.sui.io/build/move
[Xangle’s Comparison Article (KR)]:     https://xangle.io/insight/research/62e34d357a80905a1f4749c5
[Your first coin]:                      https://aptos.dev/tutorials/your-first-coin
[Your first dApp]:                      https://aptos.dev/tutorials/your-first-dapp/
[Your first transaction]:               https://aptos.dev/tutorials/your-first-transaction
[Your first Move module]:               https://aptos.dev/tutorials/first-move-module
[Your first NFT]:                       https://aptos.dev/tutorials/your-first-nft/
[Zellic's Move Prover tutorial]:        https://github.com/zellic/move-prover-examples
