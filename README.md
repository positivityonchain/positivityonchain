### Hi there 👋

<!--
**positivityonchain/positivityonchain** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


This repo contains the contract files needed to deploy positivityOnChain.

It's important to note the compiler config settings. 'viaIR: true' had to be used in order to enable the optimizer without getting the 'stack too deep' error. 

Because of this, it appears to be difficult to verify the contract on Etherscan.

Constructor argument used for _adminSigner: 0x5A9fDefaf662aA7B309a83F8a423eeD086547091

The mainnet contract is deployed here: 0x3b0878e96950c3F7f94689a9C83c0E7608b1F26C
