# Auditor Tooling Suite

Welcome to the Auditor Tooling Suite repository. This repository serves as a resource for ranking auditors based on their tooling suite for auditing cryptocurrency protocols. The Auditor Tooling Suite is an essential part of our comprehensive auditor ranking process.

## Introduction

The Auditor Tooling Suite is a collection of tools used by auditors to assess the security of crypto projects. This repository provides a matrix that ranks different tool categories within the suite. It is important to note that the Auditor Tooling Suite is only one aspect of our overall auditor ranking process. As we continue to develop and expand this project, we will be adding more resources to enhance the auditor ranking process.


## Auditor Tooling Suite Matrix

The matrix below outlines the ranking and utilization of different tool categories within the Auditor Tooling Suite:


 | Functional Testing   |                    |                    | Integration Testing | Static Tools   |                    |                    | Dynamic Tools |                    | System Testing |
| -------------------- | ------------------ | ------------------ | ------------------- | -------------- | ------------------ | ------------------ | -------------- | ------------------ | -------------- |
|  1             |  2           |  3           |  4            | 5       |  6           | 7           | 8       | 9           | 10      |
| Tool Utilization | Single Use           | Single             | Two Used           | Three Used          | Single Use     | Two Used           | Two + One          | Single         | Single + One       | Single + One + One |
| Manual               | Solidity-Coverage  |             |                     | Echidna        |                    |                    | Slither        |                    |                  |
|                      |                    |                    |                     |                |                    |                    | Harvey         |                    |                  |
|                      |                    |                    |                     |                |                    |                    | Rattle         |                    |                  |
|                      |                    |                    |                     |                |                    |                    | Manticore      |                    |                  |
|                      |                    |                    |                     |                |                    |                    | Mythril               |                    |                  |
|  Arithmetic Bugs                            |                    |                    |                     | Slither        |            | Improper Token Handling            |                |                    |   Architectural Logic    |
| Authentication & Access Control Vulnerabilities |                    |                    |                     | Incorrect constructor name |                    |                    |                |                    | Price Manipulation                 |
| * Exception & Error Handling Disorders       |                    |                    |                     | Deletion of a mapping with structure |                    |                    |                |                    |  Oracle Manipulation                |
| Authorization via Transaction Origin         |                    |                    |                     | Uninitialized state variables |                    |                    |                |                    |                  |
| Bad Random Number Generation                 |                    |                    |                     | Missing return value check |                    |                    |                |                    |                  |
| Improper Data Validation                     |                    |                    |                     | Reentrancy     |                    |                    |                |                    |                  |
| Coding Error                                 |                    |                    |                     | Missing return value |                    |                    |                |                    |                  |
| Exact Balance Dependency                     |                    |                    |                     | Reentrancy (events out of order) |                    |                    |                |                    |                  |
| Integer Bugs or Arithmetic Issues            |                    |                    |                     | Reentrancies   |                    |                    |                |                    |                  |
| Integer Over / Under Flow                    |                    |                    |                     | Dangerous strict equality |                    |                    |                |                    |                  |
| Lack of Validation                           |                    |                    |                     | Empty return value |                    |                    |                |                    |                  |
| Missing Checks / Callable Initialization Variable |                    |                    |                     | Modifier can return the default value |                    |                    |                |                    |                  |
| Missing Logic                                |                    |                    |                     | Dangerous strict equality allows the contract to be trapped |                    |                    |                |                    |                  |
| Rugpull - Disable transfer                   |                    |                    |                     | Abi encodedPacked collision |                    |                    |                |                    |                  |
| Rugpull - Liquidity                          |                    |                    |                     | msg.value is used two times to compute a price |                    |                    |                |                    |                  |
| Rugpull - Protocol Contract mint/drain       |                    |                    |                     | Dangerous block.timestamp usage |                    |                    |                |                    |                  |
| Unauthorized Accessibility Due to Wrong Function or State Variable Visibility |                    |                    |                     | Uninitialized state variable |                    |                    |                |                    |                  |
| Unchecked High Level Call/Send Return Values  |                    |                    |                     | State variable shadowing |                    |                    |                |                    |                  |
| Unchecked Low Level Call/Send Return Values   |                    |                    |                     | Duplicate contract name |                    |                    |                |                    |                  |
| Vulnerable DelegateCall                      |                    |                    |                     | Multiple reentrancies |                    |                    |                |                    |                  |
| Rugpull - User Tokens                        |                    |                    |                     | Lack of return value check |                    |                    |                |                    |                  |
| Reentrancy                                   |                    |                    |                     | Contract locking ethers |                    |                    |                |                    |                  |
| Pricing Mechanism                            |                    |                    |                     | Dangerous divide before multiply operations |                    |                    |                |                    |                  |
| * Environment Configuration Issues           |                    |                    |                     | Variable shadowing |                    |                    |                |                    |                  |
| | |
|             |                    |    |              |   Mythril               |                    |                    |                |                    |                  |
|                      |                    |                    |                     |                |                    |                    |                |                    |                  |
|            |                    |                    |                     |  Delegate Call To Untrusted Contract              |                    |                    |                |                    |                  |
|                               |                    |                    |                     |  Weak Randomness              |                    |                    |                |                    |                  |
|                          |                    |                    |                     | Deprecated Opcodes                |                    |                    |                |                    |                  |
|                              |                    |                    |                     |    Ether Thief                 |                    |                    |                |                    |                  |
|                                    |                    |                    |                     |  Exceptions              |                    |                    |                |                    |                  |
|                                |                    |                    |                     |  External Calls              |                    |                    |                |                    |                  |
|                      |                    |                    |                     | Integer Over/Under Flow                |                    |                    |                |                    |                  |
|             |                    |                    |                     | Denial of Service With Failed Call               |                    |                    |                |                    |                  |
|                                     |                    |                    |                     |  Suicide                |                    |                    |                |                    |                  |
|      |                    |                    |                     |    State Change External Calls (Reentrancy)             |                    |                    |                |                    |                  |
|                   |                    |                    |                     | Unchecked Return Call Value                |                    |                    |                |                    |                  |
|                   |                    |                    |                     |   User Supplied assertion                  |                    |                    |                |                    |                  |
|                     |                    |                    |                     | Arbitrary Storage Write                  |                    |                    |                |                    |                  |
|                          |                    |                    |                     | Arbitrary Jump                     |                    |                    |                |                    |                  |
|                       |                    |                    |                     |  Timestamp Dependence                 |                    |                    |                |                    |                  |




## Contributing

We welcome contributions from the community to improve and enhance the Auditor Tooling Suite repository. If you have suggestions, bug reports, or would like to contribute new features or tool categories, please feel free to submit a pull request. 

### How to Contribute

To contribute to the Auditor Tooling Suite repository, follow these steps:

1. Fork this repository to your GitHub account.
2. Create a new branch for your contribution.
3. Make your changes, whether it's adding new tools, improving existing ones, or suggesting enhancements.
4. Commit your changes and push them to your forked repository.
5. Submit a pull request to the original Auditor Tooling Suite repository.

Once your pull request is submitted, it will be reviewed by the maintainers. We appreciate your contributions and will work together to ensure the quality and relevance of the Auditor Tooling Suite.



