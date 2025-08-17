
# Cluster

Cluster is a web platform for shared wallets built on the Stellar ecosystem, allowing groups of friends, teams, and communities to manage collective funds in a simple, secure, and transparent way. Unlike an individual wallet, Cluster offers native multisig, ensuring that transactions only occur with the authorization defined by the group.

# Languages used
| [![Rust](https://img.shields.io/badge/-Rust-black?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/) | [![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/) | [![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) |
|---|---|---|
| [![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) | [![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) | [![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/) |

# Proposal

The proposal is to create circles of trust in crypto, where each wallet can have multiple participants with distinct roles: administrators, contributors, or viewers. The collective dashboard displays balances, contributions, and withdrawals, while the entire transaction history remains immutably recorded on the Stellar ledger.

# Architecture

The architecture combines Node.js on the backend (API + Stellar SDK), Rust for smart contracts, and PostgreSQL for off-chain management of users and permissions. On the frontend, the interface can be built with HTML, CSS, and JS, or with React for greater fluidity.

# Differential

Cluster prioritizes security with encrypted login, two-factor authentication (2FA), and full audit of operations. Its differential lies in combining modern usability with the power of Stellar, creating a practical solution for groups that want to manage crypto assets collaboratively and reliably.







