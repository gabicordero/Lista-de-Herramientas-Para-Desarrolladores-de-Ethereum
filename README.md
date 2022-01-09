# Lista de Herramientas Para Desarrolladores de Ethereum
Una guía de herramientas, componentes, patrones y plataformas disponibles para desarrollar aplicaciones en Ethereum.

La creación de esta lista fue impulsada por los gerentes de producto de ConsenSys que vieron la necesidad de compartir mejor las herramientas, los patrones de desarrollo y los componentes entre los desarrolladores de blockchain, tanto nuevos como experimentados.

Este recurso se centra en las herramientas para desarrolladores, pero el repositorio también incluye:
-  <a href="https://github.com/ConsenSys/ethereum-developer-tools-list/blob/master/EcosystemResources.md" class="ecosystem-resources" target="_blank" alt="ecosystem-resources">Recursos del Ecosistema Ethereum</a> para DApps útiles, recursos educativos, carteras y servicios.

## Nuevos desarrolladores empiezan aqui

- <a href="https://soliditylang.org/">Solidity</a> - El lenguaje de contratos inteligentes más popular.
- <a href="https://metamask.io/">Metamask</a> - Monedero de extensión del navegador para interactuar con Dapps.
- <a href="https://trufflesuite.com/">Truffle</a> - El marco más popular de desarrollo, prueba y despliegue de contratos inteligentes. Instala el cli vía npm y comienza aquí a escribir tus primeros contratos inteligentes.
- <a href="https://trufflesuite.com/boxes">Cajas Truffle</a> - Componentes empaquetados para el ecosistema Ethereum.
- <a href="https://hardhat.org/">Hardhat</a> - Entorno de desarrollo de Ethereum flexible, extensible y rápido.
- <a href="https://cryptotux.org/">Cryptotux</a> - Una imagen de Linux lista para ser importada en VirtualBox que incluye las herramientas de desarrollo mencionadas anteriormente
- <a href="https://openzeppelin.com/starter-kits/">OpenZeppelin Starter Kits</a> - Una caja de inicio todo en uno para que los desarrolladores inicien sus aplicaciones respaldadas por contratos inteligentes. Incluye Truffle, OpenZeppelin SDK, el paquete OpenZeppelin/contracts-ethereum-package EVM de contrato inteligente auditado, una react-app y rimble para facilitar el estilo.
- <a href="https://docs.ethhub.io/">EthHub.io</a> - Visión general completa de Ethereum, su historia, gobierno, planes futuros y recursos de desarrollo.
- <a href="https://ethereumdev.io/">EthereumDev.io</a> - La guía definitiva para iniciarse en la programación de contratos inteligentes de Ethereum.
- <a href="https://github.com/eth-brownie/brownie">Brownie</a> - Brownie es un marco de trabajo en Python para desplegar, probar e interactuar con los contratos inteligentes de Ethereum.
- <a href="https://ethereum.stackexchange.com/">Ethereum Stack Exchange</a> - Publique y busque preguntas para ayudar a su ciclo de vida de desarrollo.
- <a href="https://streamingfast.io/">dfuse</a> - APIs de blockchain para construir aplicaciones de clase mundial.
- <a href="https://www.biconomy.io/">Biconomy</a> - Realiza transacciones sin gas en tu dapp habilitando meta-transacciones utilizando un SDK sencillo de usar.
- <a href="https://www.blocknative.com/">Blocknative</a> - Eventos de blockchain antes de que ocurran. La cartera de herramientas para desarrolladores de Blocknative facilita la construcción con datos de mempool.
- <a href="https://www.useweb3.xyz/">useWeb3.xyz</a> - Un resumen curado de los mejores y más recientes recursos sobre Ethereum, blockchain y desarrollo Web3.

## Herramientas de desarrollo
### Desarrollando Smart Contracts
#### Lenguajes de Smart Contract

* [Solidity](https://docs.soliditylang.org/en/latest/) - Lenguaje de contratos inteligentes de Ethereum
* [Vyper](https://vyper.readthedocs.io/en/latest/) - Nuevo lenguaje de programación experimental

#### Frameworks
* [Truffle](https://trufflesuite.com/) - El framework de implementación, prueba y desarrollo de contratos inteligentes más popular. La suite Truffle incluye Truffle, [Ganache](https://github.com/trufflesuite/ganache), y [Drizzle](https://github.com/truffle-box/drizzle-box). [Sumérgete en Truffle aquí](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Hardhat](https://hardhat.org/) - Entorno de desarrollo Ethereum flexible, extensible y rápido.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Brownie es un framework de Python para implementar, probar e interactuar con contratos inteligentes de Ethereum.
* [Embark](https://github.com/embark-framework/embark) - Framework para desarrollo de DApp.
* [Waffle](https://getwaffle.io/) - Framework para pruebas y desarrollo de contratos inteligentes avanzados, pequeño, flexible, rápido (basado en ethers.js)
* [Dapp](https://dapp.tools/dapp/) - Framework para el desarrollo de DApp, sucesor de DApple.
* [Etherlime](https://github.com/LimeChain/etherlime) - Framework basado en ethers.js para la implementación de Dapp.
* [Parasol](https://github.com/Lamarkaz/parasol) - Framework ágil de desarrollo de contratos inteligentes con pruebas, implementación de INFURA, documentación automática de contratos y más. Cuenta con un diseño flexible y sin pinzas con personalización ilimitada.
* [0xcert](https://github.com/0xcert/framework/) - JavaScript framework para la construcción de aplicaciones descentralizadas
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - OpenZeppelin SDK: Un conjunto de herramientas para ayudarlo a desarrollar, compilar, actualizar, implementar e interactuar con contratos inteligentes.
* [sbt-ethereum](https://sbt-ethereum.io/) - Una consola basada en texto y con pestañas para la interacción y el desarrollo de contratos inteligentes, que incluye administración de billetera y ABI, soporte ENS e integración avanzada de Scala.
* [Cobra](https://github.com/cobraframework/cobra) - Un framework de entorno de desarrollo rápido, flexible y simple para el smart contract, las pruebas y la implementación de Ethereum en la máquina virtual de Ethereum (EVM).
* [Epirus](https://docs.epirus.io/sdk/) - Java framework para la construcción de contratos inteligentes.

#### IDEs
* [Remix](https://remix.ethereum.org/) - Web IDE con análisis estático integrado, prueba blockchain VM.
* [Ethereum Studio](https://studio.ethereum.org/) - IDE web. VM blockchain del navegador integrado, integración de Metamask (implementaciones con un clic en Testnet / Mainnet), registrador de transacciones y código en vivo de su aplicación web, entre muchas otras características.
* [Atom](https://atom.io/) - Atom editor con [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity), y [language-solidity](https://atom.io/packages/language-solidity) packages
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Archivo de sintaxis de Vim para solidity.
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Extensión de Visual Studio Code que agrega soporte para Solidity
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=quantanetwork.ethcode) - Extensión de Visual Studio Code para compilar, ejecutar y depurar programas Solidity y Vyper
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - Complemento de código abierto para [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/) (gratis / comercial) con resaltado de sintaxis, formateo, finalización de código, etc.
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - IDE basado en Eclipse. Incluye ayuda y finalización de código sensible al contexto, navegación de código, coloración de sintaxis, compilador integrado, arreglos rápidos y plantillas.
* [Eth Fiddle](https://ethfiddle.com/) - IDE desarrollado por [The Loom Network](https://loomx.io/) que le permite escribir, compilar y depurar su contrato inteligente. Fácil de compartir y encontrar fragmentos de código.

### Otras herramientas
* [Atra Blockchain Services](https://console.atra.io) - Atra proporciona servicios web para ayudarlo a construir, implementar y mantener aplicaciones descentralizadas en la cadena de bloques Ethereum.
* [Azure Blockchain Dev Kit for Ethereum for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain) - Extensión VSCode que permite crear contratos inteligentes e implementarlos dentro de Visual Studio Code.

### Probar Redes Blockchain
* [ethnode](https://github.com/vrde/ethnode) - Ejecute un nodo Ethereum (Geth o Parity) para el desarrollo, tan fácil como `npm i -g ethnode && ethnode`.
* [Ganache](https://github.com/trufflesuite/ganache) - Aplicación para probar la cadena de bloques Ethereum con interfaz de usuario visual y registros.
* [Kaleido](https://kaleido.io/) - Utilice Kaleido para poner en marcha una red de cadena de bloques de consorcio. Ideal para pruebas y PoC.
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Ejecute una red privada de nodos Besu en un contenedor Docker
** [Orion](https://github.com/PegaSysEng/orion) - Componente para realizar transacciones privadas por PegaSys
** [Artemis](https://github.com/PegaSysEng/artemis) - Implementación Java de la cadena de balizas Ethereum 2.0 de PegaSys
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifica la integración y la aceptación de pruebas de aplicaciones de contrato inteligente con instancias de Docker que se asemeja mucho a una red blockchain real.
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Ejecute una red local de Raiden en contenedores de Docker con fines de demostración y prueba
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Scripts de implementación listos para usar para redes PoA privadas
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Scripts de implementación listos para usar para redes privadas de PoW
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain/templates/ethereum-poa-deployment) - Despliegue y gobernanza de las redes de PoA del consorcio Ethereum
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - Construya una red Ethereum basada en Prueba de trabajo
* [Infura](https://infura.io/) - Acceso de la API de Ethereum a las redes de Ethereum (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
* [CloudFlare Distributed Web Gateway](https://cloudflare.com/distributed-web-gateway/) - Proporciona acceso a la red Ethereum a través de Cloudflare en lugar de ejecutar su propio nodo
* [Chainstack](https://chainstack.com/) - Nodos de Ethereum compartidos y dedicados como servicio (Mainnet, Ropsten)
* [Alchemy](https://alchemyapi.io/) - Plataforma de desarrollo Blockchain, API Ethereum y servicio de nodo (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
* [ZMOK](https://zmok.io/) - JSON-RPC Ethereum API (Mainnet, Rinkeby, Mainnet de ejecución frontal)

#### Test Ether Faucets
* [Rinkeby faucet](https://faucet.rinkeby.io/)
* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Ropsten faucet (MetaMask)](https://faucet.metamask.io/)
* [Ropsten faucet (rpanic)](https://faucet.rpanic.com)
* [Goerli faucet](https://goerli-faucet.slock.it/)
* [Universal faucet](https://faucets.blockxlabs.com/)
* [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) - A C#/.NET faucet

### Comunicarse con Ethereum
#### Frontend Ethereum APIs
* [Web3.js](https://github.com/ethereum/web3.js/) - Javascript Web3
* [Eth.js](https://github.com/ethjs) - Javascript Web3 alternativa
* [Ethers.js](https://github.com/ethers-io/ethers.js/) - Javascript Web3 alternativa, utilidades y funciones de billetera
* [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) Una biblioteca JS reactiva de alto nivel optimizada para clientes ligeros.
* [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper) - Alternativa de TypeScript Web3
* [Ethereumjs](https://github.com/ethereumjs/) - Una colección de funciones de utilidad para Ethereum como [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) y [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
* [Alchemy-web3.js](https://github.com/alchemyplatform/alchemy-web3) - Contenedor de Javascript Web3 con reintentos automáticos, acceso a las [API mejoradas de Alchemy](https://docs.alchemyapi.io/documentation/alchemy-web3/enhanced-web3-api), y robustas conexiones websocket.
* [flex-contract](https://github.com/merklejerk/flex-contract) y [flex-ether](https://github.com/merklejerk/flex-ether) - Bibliotecas modernas, de configuración cero y de alto nivel para interactuar con contratos inteligentes y realizar transacciones.
* [ez-ens](https://github.com/merklejerk/ez-ens) - Resolución de direcciones de Ethereum Name Service simple y sin configuración.
* [web3x](https://github.com/xf00f/web3x) - Un puerto TypeScript de web3.js. Los beneficios incluyen construcciones pequeñas y seguridad de tipo completo, incluso al interactuar con contratos.
* [Nethereum](https://github.com/Nethereum/) - Framework de desarrollo de Ethereum multiplataforma
* [dfuse](https://github.com/dfuse-io/client-js) - Una biblioteca de TypeScript para usar [dfuse Ethereum API](https://dfuse.io)
* [Drizzle](https://github.com/truffle-box/drizzle-box) - Biblioteca Redux para conectar una interfaz a una cadena de bloques
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - Un SDK de JavaScript para hacer dapps de Ethereum móviles nativas usando React Native
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - un React Hook personalizado para administrar Metamask en proyectos Ethereum ĐApp
* [WalletConnect](https://walletconnect.org/) - Protocolo abierto para conectar Wallets a Dapps
* [Subproviders](https://0x.org/docs/tools/subproviders) - Varios subproveedores útiles para usar junto con [Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine) (incluido un LedgerSubprovider para agregar soporte de billetera de hardware Ledger a su dApp)
* [ethvtx](https://github.com/ticket721/ethvtx) - Configuración de tienda redux lista para ethereum y agnóstica de framework. [docs](https://ticket721.github.io/ethvtx/)
* Estrictamente mecanografiado: alternativas a Javascript
    * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
    * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - Comuníquese con diferentes cadenas de bloques (incluido Ethereum) utilizando una única interfaz.
* [Delphereum](https://github.com/svanas/delphereum) - una interfaz Delphi a la cadena de bloques Ethereum que permite el desarrollo de dApps nativas para Windows, macOS, iOS y Android.
* [Torus](https://tor.us/) - SDK de código abierto para crear dapps con una experiencia de usuario integrada perfecta
* [Fortmatic](https://fortmatic.com/) - Un SDK fácil de usar para crear dApps web3 sin extensiones ni descargas.
* [Portis](https://portis.io/) - Una billetera sin custodia con un SDK que permite una fácil interacción con DApps sin instalar nada.
* [create-eth-app](https://github.com/paulrberg/create-eth-app) - Cree aplicaciones front-end impulsadas por Ethereum con un solo comando.
* [Scaffold-ETH](https://github.com/austintgriffith/scaffold-eth) - Github apto para principiantes para comenzar a construir contratos inteligentes.
* [Notify.js](https://blocknative.com/notify) - Entregue notificaciones en tiempo real a sus usuarios. Con soporte integrado para aceleraciones y cancelaciones, Blocknative Notify.js ayuda a los usuarios a realizar transacciones con confianza. Notify.js es fácil de integrar y rápido de personalizar.

#### Backend Ethereum APIs

