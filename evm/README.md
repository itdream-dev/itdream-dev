
### **Smart Contracts**

Different blockchains might employ various languages to develop smart contracts, such as Solidity, Move, Rust, Vyper, Cairo, C++, etc. Currently, Solidity remains the most popular and beginner-friendly smart contract language for EVM-compatible chains. It's essential to thoroughly read its language documentation. Moreover, one should understand the design standards of token contracts running on Ethereum and their specific contract implementations. Building on this foundation, it's crucial to understand how smart contracts can be made upgradable and to practically master the writing and testing of smart contracts.

Resources and Tools for Mastering Smart Contracts with Solidity

- [Solidity Official Documentation](https://docs.soliditylang.org/en/latest/)

- Essential Reading "[Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)"
  - Emphasis on reading the remaining chapters
  
- Understanding Ethereum's Standard Proposals ([ERC](https://eips.ethereum.org/erc))
  - [ERC20](https://eips.ethereum.org/EIPS/eip-20): Standard for fungible tokens
  - [ERC165](https://eips.ethereum.org/EIPS/eip-165): Interface standard
  - [ERC173](https://eips.ethereum.org/EIPS/eip-173): Contract ownership standard
  - [ERC191](https://eips.ethereum.org/EIPS/eip-191): Data signature standard
  - [ERC601](https://eips.ethereum.org/EIPS/eip-601): Deterministic wallet hierarchical structure standard
  - [ERC721](https://eips.ethereum.org/EIPS/eip-721): Non-fungible token standard
  - [ERC777](https://eips.ethereum.org/EIPS/eip-777): Interoperable token standard
  - [ERC1155](https://eips.ethereum.org/EIPS/eip-1155): Multi-token standard
  - [ERC1167](https://eips.ethereum.org/EIPS/eip-1167): Minimal proxy contract
  - [ERC1967](https://eips.ethereum.org/EIPS/eip-1967): Proxy data storage slots
  - [ERC2612](https://eips.ethereum.org/EIPS/eip-2612): Token permit signature
  - [ERC4626](https://eips.ethereum.org/EIPS/eip-4626): Token vault standard
  
- Studying OpenZeppelin's [token](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token) implementations

- Understanding what upgradable contracts/proxy contracts are
  
  * [Introduction to different proxy contract patterns](https://ethereum-blockchain-developer.com/110-upgrade-smart-contracts/00-project/)
  * [Proxies Deep Dive](https://proxies.yacademy.dev/pages/Proxies-List/)
  * [OpenZeppelin Proxy](https://docs.openzeppelin.com/contracts/4.x/api/proxy) implementation documentation
  
- Learning to Write Smart Contracts
  - [WTF Solidity Smart Contract Tutorials](https://www.wtf.academy/en/)
  - [Crypto Zombies](https://cryptozombies.io/en/course/)
  - [Smart Contract Engineer](https://www.smartcontract.engineer/)
  - [Solidity by Example](https://solidity-by-example.org/)

- Utilizing Smart Contract Build Tools
  - Popular Online IDEs
    - [Remix](https://remix.ethereum.org/)
    - [ChainIDE](https://chainide.com/)
    - [Tenderly Sandbox](https://sandbox.tenderly.co/)
    
  - Familiarization with Package Managers
    - [npm](https://www.npmjs.com/)
    - [yarn](https://yarnpkg.com/)
    - [pnpm](https://pnpm.io/)
    
  - Popular Smart Contract Testing and Debugging Frameworks
    - [Foundry](https://book.getfoundry.sh/)
      * Convenient [testing](https://book.getfoundry.sh/forge/tests) tools
      * [Cheatcodes](https://book.getfoundry.sh/cheatcodes/)
      * [Best practices](https://book.getfoundry.sh/tutorials/best-practices)
    
    * [Hardhat](https://hardhat.org/hardhat-runner/docs/getting-started#overview)
      * Leveraging its potent [plugins](https://hardhat.org/hardhat-runner/plugins)
    
    * [Brownie](https://eth-brownie.readthedocs.io/en/stable/)
    * [Tenderly](https://tenderly.co/)
      * [Convenient DevNet development testing environment](https://docs.tenderly.co/devnets/intro-to-devnets)
      * [Quick transaction simulations](https://docs.tenderly.co/simulations-and-forks/intro-to-simulations)
      * [Visual transaction debugging tools](https://docs.tenderly.co/debugger/how-to-use-tenderly-debugger)
    * [Sentio](https://app.sentio.xyz/explorer)
      * [Online debugging with code insight](https://docs.sentio.xyz/docs/code-insight) 
      * [Simulation with contract overrides](https://docs.sentio.xyz/docs/simulation#override-contract)
  * Interacting with Smart Contracts
    * Understanding [JSON-RPC](https://ethereum.org/en/developers/docs/apis/json-rpc/)
    * [ethers.js](https://docs.ethers.org/)
    * [Web3.js](https://web3js.readthedocs.io/)
    * [Web3.py](https://web3py.readthedocs.io/)
    * [viem](https://viem.sh/)

### **3. Best Practices and Security Standards**

As auditors, it's crucial to be familiar with the best practices and security standards of smart contracts. Best practices serve as a reference in identifying security issues during an audit, while security standards provide a basis for any security issues raised.

- [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)
- [Solcurity](https://github.com/transmissions11/solcurity)
- [ConsenSys Smart Contract Best Practices](https://github.com/Consensys/smart-contract-best-practices/blob/master/README.md) 
- [Solidity Security Pitfalls and Best Practices 101](https://secureum.substack.com/p/security-pitfalls-and-best-practices-101)
- [Solidity Security Pitfalls and Best Practices 201](https://secureum.substack.com/p/security-pitfalls-and-best-practices-201)
- [SCSVSv2](https://github.com/securing/SCSVS/tree/prerelease/SCSVSv2)
- [EEA EthTrust Certification](https://entethalliance.org/specs/ethtrust-sl/)
- [Foundry Testing Best Practices](https://book.getfoundry.sh/tutorials/best-practices)

# note: please study defi and back to here.

### **4. Deep Dive into EVM**

The EVM (Ethereum Virtual Machine) is responsible for executing smart contract instructions. A comprehensive understanding of the EVM aids in a more in-depth grasp of the deployment, invocation, execution, and data storage of smart contracts. This foundational knowledge is also pivotal for Gas optimization and discovering vulnerabilities.

- [About EVM](https://www.evm.codes/about)
- [The EVM From Scratch Book](https://evm-from-scratch.xyz/content/01_intro.html)
- Noxx's [In-depth Research on EVM](https://noxx.substack.com/p/evm-deep-dives-the-path-to-shadowy) 
- [Parsing Solidity Slot Data](https://ethdebug.github.io/solidity-data-representation/) 
- [Ethereum Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)
  - [Simplified Version](https://github.com/chronaeon/beigepaper) 
- [Quillhash EVM Mastery](https://github.com/Quillhash/EVM-Mastery)
- [EVM Implementation Examples](https://github.com/noxx3xxon/evm-by-example) 

### **5. Gas Optimization Design**

All on-chain transactions incur Gas costs. For complex contracts, optimizing Gas can reduce user interaction costs, thereby attracting more users. This demands that auditors have a certain understanding of Gas optimization design.

- [Gas Optimization References 1](https://www.alchemy.com/overviews/solidity-gas-optimization)
- [Gas Optimization References 2](https://www.rareskills.io/post/gas-optimization)
- [Gas Optimization References 3](https://coinsbench.com/structs-in-solidity-best-practices-for-gas-efficiency-by-0xlazard-4e984a7485cf)