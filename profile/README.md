![img](./profile/bg.png)

WeaveVM (WVM) is the first EVM-compatible protocol engineered to manage complex, large-scale data computation without the high gas fees typically associated with on-chain state storage on EVM chains. WVM is also the first EVM-compatible protocol that fully relies on Arweave for DA, enabling atomicity of source code and data storage on the same ledger. WVM incorporates the principles of [VACP](https://docs.wvm.dev/discover-weavevm/weavevm-and-vacp), bolstering its ability to handle complex data structures efficiently and gaslessly.

![img](./profile/diagram.png)

WVM is a hyperscalable, lazy-evaluated EVM protocol with near-instant finality and full onchain storage.

## Protocol, not a network
WeaveVM operates as a protocol employing a customized Ethereum Virtual Machine (EVM) capable of interfacing with Arweave. WVM functions through algorithmic sets that assess codes and generate a subsequent state. Notably, transaction finality in this protocol is optimistic, facilitated by centralized indexers responsible for evaluating the EVM state instead of relying on a nodes-consensus model within a network.

The WeaveVM (WVM) protocol name signifies the integration of Arweave with the Ethereum Virtual Machine. WVM unites Arweave's data storage capabilities ("weave") with the functionalities of the EVM ("VM").

## EVM compatibility type: SEE-EVM
WeaveVM introduces a new category of EVM compatibility known as SEE-EVM-Compatible. SEE, or Specialized Execution Environment, forms the fundamental engine of WVM.

It functions as a specialized execution environment utilizing the EVM as its core machine while leveraging Arweave for data storage. However, it's important to note that due to certain adjustments, complete compatibility with all EVM features might currently be restricted.

![img](./profile/scale.png)

To understand that graphic better, let's define EVM equivalence and EVM compatibility:

1. EVM Equivalence: Ensures strict alignment with Ethereum Virtual Machine (EVM) specifications, enabling seamless operation of Ethereum mainnet applications on EVM-equivalent Layer 2 networks without modifications. Ideal for exact replication of Ethereum's mainnet functionalities on Layer 2 platforms.
2. EVM Compatibility: Allows Ethereum-based applications to function on Layer 2 networks, but doesn't guarantee complete adherence to EVM standards. While supporting most Ethereum functionalities, some adjustments in applications may be necessary due to slight variations. Beneficial for applications adaptable to these differences to leverage specific Layer 2 network features.

## Can WeaveVM be labeled as an L2?
Before determining whether WeaveVM fits the criteria for being classified as an L2 (Layer 2) solution, let's check the accurate definition for a layer 2 (L2):

> "A layer 2 refers to any off-chain network, system, or technology built on top of a blockchain (commonly known as a layer-1 network) that helps extend the capabilities of the underlying base layer network. Layer-2 networks can support any blockchain to introduce enhancements such as higher transaction throughputs." - [Chainlink docs](https://chain.link/education-hub/what-is-layer-2)

Presently, numerous networks leveraging Ethereum or EVM are labeled as L2 despite not meeting this fundamental prerequisite:

> "One core requirement for a network, system, or technology to be considered a layer 2 is that it inherits the security of the blockchain it is built on top of. Transaction data must, in some shape or form, be verified and confirmed by the underlying blockchain network rather than a separate set of nodes."
Therefore, WeaveVM might not strictly fit the definition of a traditional Layer 2 solution within the Ethereum ecosystem. However, It operates as an EVM-compatible protocol utilizing Arweave for data storage and inheriting its security.
