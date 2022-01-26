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
* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [rust-web3](https://github.com/tomusdrw/rust-web3) - Rust Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [Eventeum](https://github.com/ConsenSys/eventeum) - Un puente entre los eventos de contratos inteligentes de Ethereum y los microservicios backend, escrito en Java por Kauri
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - Elixir JSON-RPC cliente para la cadena de bloques Ethereum
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - Una puerta de enlace que le permite ejecutar varios nodos de Ethereum con fines de redundancia y equilibrio de carga. Se puede ejecutar como una alternativa a (o encima de) Infura. Escrito en Golang. 
* [EthContract](https://github.com/AgileAlpha/eth_contract) - Un conjunto de métodos auxiliares para ayudar a consultar contratos inteligentes de ETH en Elixir
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - Un Servicio MESG para interactuar con cualquier contrato de Ethereum basado en su dirección y ABI.
* [Ethereum Service](https://github.com/mesg-foundation/service-ethereum) - Un servicio MESG para interactuar con eventos de Ethereum e interactuar con él.
* [Marmo](https://marmo.io/) - Python, JS y Java SDK para simplificar las interacciones con Ethereum. Utiliza retransmisores para descargar los costos de transacción a los retransmisores.
* [Ethereum Logging Framework](https://bitbucket.csiro.au/users/kli039/repos/ethereum-logging-framework/browse) - proporciona capacidades de registro avanzadas para aplicaciones y redes de Ethereum, incluido un lenguaje de consulta, un procesador de consultas y generación de código de registro

#### Herramientas Bootstrap/listas para usar
* [Truffle boxes](https://trufflesuite.com/boxes) - Componentes empaquetados para el ecosistema Ethereum
* [Create Eth App](https://github.com/paulrberg/create-eth-app) - Cree aplicaciones frontend impulsadas por Ethereum con un solo comando
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Ejecute una red privada de nodos Besu en un contenedor Docker
* [Testchains](https://github.com/Nethereum/TestChains) - Cadenas de desarrollo .NET preconfiguradas para una respuesta rápida (PoA)
** [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Wasm blockchain explorer (muestra funcional)
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Ejecute una red Raiden local en contenedores docker para fines de demostración y prueba
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Scripts de implementación listos para usar para redes PoA privadas
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Tutorial paso a paso para construir una cadena de prueba PoA con 2 nodos con consenso de ronda de autoridad de paridad
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Scripts de implementación listos para usar para redes PoW privadas
* [Kaleido](https://kaleido.io/) - Use Kaleido para poner en marcha una red de cadena de bloques de consorcio. Excelente para PoC y pruebas
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - Una implementación de sandbox local de la API de CryptoKitties y contratos inteligentes, disponible como Truffle Box
* [aragonCLI](https://github.com/aragon/aragon-cli) - aragonCLI se utiliza para crear y desarrollar aplicaciones y organizaciones de Aragon.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - Cliente de JavaScript que proporciona una API para interactuar con los contratos inteligentes de Colony Network.
* [ArcJS](https://github.com/daostack/arc.js) - Biblioteca que facilita el acceso de la aplicación javascript a los contratos inteligentes DAOstack Arc ethereum.
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - Cliente de JavaScript que proporciona una API para interactuar con Arkane Network, un proveedor de billetera para crear dapps fáciles de usar.
* [Onboard.js](https://blocknative.com/onboard) - Blocknative Onboard es la manera rápida y fácil de agregar compatibilidad con múltiples billeteras a su proyecto. Con módulos integrados para más de 20 carteras únicas de hardware y software, Onboard le ahorra tiempo y dolores de cabeza.
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - React framework para construir dApps de Ethereum de una sola página

#### Ethereum ABI (Interfaz binaria de aplicación) herramientas
* [Online ABI encoder](https://github.com/HashEx/abiencoder) - Servicio gratuito de codificador ABI en línea que le permite codificar las funciones y los argumentos del constructor de su contrato Solidity.
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - biblioteca para decodificar parámetros de datos y eventos de transacciones de Ethereum
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - Generar envoltorios de contrato TypeScript a partir de ABI de contrato
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Generar automáticamente definiciones de campo de formulario de interfaz de usuario y validadores asociados a partir de un contrato ABI de Ethereum
* [headlong](https://github.com/esaulpaugh/headlong/) - Biblioteca de prefijos de longitud recursiva y ABI de contrato de tipo seguro en Java
* [EasyDapper](https://www.easydapper.com) - Genere dapps a partir de artefactos de Truffle, implemente contratos en redes públicas/privadas, ofrezca una página pública personalizable en vivo para interactuar con los contratos.
* [One Click dApp](https://oneclickdapp.com) - Cree instantáneamente una dApp en una URL única utilizando la ABI.
* [Truffle Pig](https://npmjs.com/package/trufflepig) - una herramienta de desarrollo que proporciona una API HTTP simple para buscar y leer archivos de contrato generados por Truffle, para usar durante el desarrollo local. Sirve ABI de contrato nuevo a través de http.
* [Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) - Un Servicio MESG para interactuar con cualquier contrato de Ethereum en función de su dirección y ABI.
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - Un generador basado en la web que crea una interfaz y un servicio C# basados ​​en Nethereum basados ​​en Solidity Smart Contracts.
* [EVMConnector](https://evmconnector.dev) - Cree paneles de contratos compartibles e interactúe con funciones arbitrarias de blockchain basadas en EVM, con o sin ABI.

#### Patrones y Mejores Prácticas

##### Patrones para el desarrollo de contratos inteligentes
* [Dappsys: Bloques de construcción de contratos Ethereum seguros, simples y flexibles](https://github.com/dapphub/dappsys)
    * iene soluciones para problemas comunes en Ethereum/Solidity, p.
        * [Whitelisting](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Upgradable ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Authentication (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...several more...](https://github.com/dapphub/dappsys)
    * proporciona bloques de construcción para la [MakerDAO](https://github.com/makerdao/maker-otc) o [The TAO](https://github.com/ryepdx/the-tao)
    * debe consultarse antes de crear soluciones propias, no probadas
    * el uso se describe en [Dapp-a-day 1-10](https://steemit.com/@nikolai) y [Dapp-a-day 11-25](https://steemit.com/@nexusdev)
* [Contratos OpenZeppelin: un marco abierto de contratos inteligentes reutilizables y seguros en el lenguaje Solidity.](https://github.com/OpenZeppelin/openzeppelin-contracts)
    * Probablemente las bibliotecas y los contratos inteligentes más utilizados
    * Similar a Dappsys, más integrado en el marco de Truffle
    * [Blog about Best Practices with Security Audits](https://blog.openzeppelin.com/)
* [Advanced Workshop with Assembly](https://github.com/androlo/solidity-workshop)
* [Simpler Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - especially section _Benefits_
* [CryptoFin Solidity Auditing Checklist](https://github.com/cryptofinlabs/audit-checklist) - A checklist of common findings, and issues to watch out for when auditing a contract for a mainnet launch.
* [aragonOS: A smart contract framework for building DAOs, Dapps and protocols](https://hack.aragon.org/docs/aragonos-intro.html)
    * Upgradeability: Smart contracts can be upgraded to a newer version
    * Permission control: By using the `auth` and `authP` modifiers, you can protect functionality so only other apps or entities can access it
    * Forwarders: aragonOS apps can send their intent to perform an action to other apps, so that intent is forwarded if a set of requirements are met
* [EIP-2535 Diamond Standard](https://eips.ethereum.org/EIPS/eip-2535)
    * Organize contracts so they share the same contract storage and Ethereum address.
    * Solves the 24KB max contract size limit.
    * Upgrade diamonds by adding/replacing/removing any number of functions in a single transaction.
    * Upgrades are transparent by recording them with a standard event.
    * Get information about a diamond with events and/or four standard functions.
* [Clean Contracts - A guide to writing clean code](https://www.wslyvh.com/clean-contracts/)

##### Upgradeability
* [Blog von Elena Dimitrova, Dev at colony.io](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Aragon research blog](https://blog.aragon.org/tag/research/)
    * [Library driven development](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [Advanced Solidity code deployment techniques](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin on Proxy Libraries](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### Infrastructure
#### Ethereum Clients
* [Besu](https://besu.hyperledger.org/en/latest/) - an open-source Ethereum client developed under the Apache 2.0 license and written in Java. The project is hosted by Hyperledger.
* [Geth](https://geth.ethereum.org/docs/) - Go client
* [OpenEthereum](https://github.com/openethereum/openethereum) - Rust client, formerly called Parity
* [Aleth](https://github.com/ethereum/aleth) - C++ client
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core client
* [Infura](https://infura.io/) - A managed service providing Ethereum client standards-compliant APIs
* [Trinity](https://trinity.ethereum.org/) - Python client using [py-evm](https://github.com/ethereum/py-evm)
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - JS client using [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm)
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth is an Ethereum client tool—like a "MetaMask for the command line"
* [Mustekala](https://github.com/musteka-la/mustekala) - Ethereum Light Client project of Metamask
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir client
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - Energy Web Foundation client for the Tobalaba test network
* [Quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy by [JP Morgan](https://jpmorgan.com/quorum)
* [Mana](https://github.com/mana-ethereum/mana) - Ethereum full node implementation written in Elixir.
* [Chainstack](https://chainstack.com/) - A managed service providing shared and dedicated Geth nodes
* [QuickNode](https://quicknode.com/) - Blockchain developer cloud with API access and node-as-a-service.


#### Storage
* [IPFS](https://ipfs.io/) - Decentralised storage and file referencing
   * [Mahuta](https://github.com/ConsenSys/Mahuta) - IPFS Storage service with added search capability, formerly IPFS-Store
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - Decentralised database on top of IPFS
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - A client library for the IPFS HTTP API, implemented in JavaScript
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - Easy to use API into IPFS and other distributed/decentralised storage protocols
   * [PINATA](https://pinata.cloud) - The Easiest Way to Use IPFS
* [Swarm](https://swarm-gateways.net/) - Distributed storage platform and content distribution service, a native base layer service of the Ethereum web3 stack
* [Infura](https://infura.io/) - A managed IPFS API Gateway and pinning service
* [3Box Storage](https://docs.3box.io/api/storage) - An api for user controlled, distrubuted storage. Built on top of IPFS and Orbitdb.
* [Aleph.im](https://aleph.im/) - an offchain incentivized peer-to-peer cloud project (database, file storage, computing and DID) compatible with Ethereum and IPFS.


#### Messaging
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack
* [DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - Peer-to-peer communications between nodes running Ethereum/Whisper
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - Python implementation of the RLPx network layer
* [3Box Threads](https://docs.3box.io/api/messaging) - API to allow developers to implement IPFS persisted, or in memory peer to peer messaging.

### Testing Tools
* [Truffle Teams](https://trufflesuite.com/teams) - Zero-Config continuous integration for truffle projects
* [Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity code coverage tool
* [Solidity coverage](https://github.com/sc-forks/solidity-coverage) - Alternative code coverage for Solidity smart-contracts
* [Solidity function profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Alternative and updated Solidity smart contract profiler
* [Espresso](https://github.com/hillstreetlabs/espresso) - Speedy, parallelised, hot-reloading solidity test framework
* [Eth tester](https://github.com/ethereum/eth-tester) - Tool suite for testing Ethereum applications
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network
* [Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) - The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts
* [Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) - Solidity graphical debugger
* [Tenderly CLI](https://github.com/Tenderly/tenderly-cli) - Speed up your development with human readable stack traces
* [Solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation
* [Ethlint](https://github.com/duaraghav8/Ethlint) - Linter to identify and fix style & security issues in Solidity, formerly Solium
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [truffle-assertions](https://github.com/rkalis/truffle-assertions) - An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have (not) been emitted.
* [Psol](https://github.com/Lamarkaz/psol) - Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.
* [solpp](https://github.com/merklejerk/solpp) - Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.
* [Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) – Decode and publish raw ethereum tx. Similar to https://live.blockcypher.com/btc-testnet/decodetx/
* [Doppelgänger](https://getdoppelganger.io/) - a library for mocking smart contract dependencies during unit testing.
* [rocketh](https://github.com/wighawag/rocketh) - A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.
* [pytest-cobra](https://github.com/cobraframework/pytest-cobra) - PyTest plugin for testing smart contracts for Ethereum blockchain.

### Security Tools
* [MythX](https://mythx.io/) - Security verification platform and tools ecosystem for Ethereum developers
* [Mythril](https://github.com/ConsenSys/mythril) - Open-source EVM bytecode security analysis tool
* [Oyente](https://github.com/melonproject/oyente) - Alternative static smart contract security analysis
* [Securify](https://securify.chainsecurity.com/) - Security scanner for Ethereum smart contracts
* [SmartCheck](https://tool.smartdec.net/) - Static smart contract security analyzer
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternative EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Framework for cryptoeconomic contract security, decentralised security bounties
* [Solgraph](https://github.com/raineorshine/solgraph) - Visualise Solidity control flow for smart contract security analysis
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool on Smart Contracts and Binaries
* [Slither](https://github.com/crytic/slither) - A Solidity static analysis framework
* [Adelaide](https://github.com/sec-bit/adelaide) - The SECBIT static analysis extension to Solidity compiler
* [solc-verify](https://github.com/SRI-CSL/solidity/) - A modular verifier for Solidity smart contracts
* [Solidity security blog](https://github.com/sigp/solidity-security-blog) - Comprehensive list of known attack vectors and common anti-patterns
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected
* [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) - Free smart contract security audits from Callisto Network
* [Piet](https://piet.slock.it) - A visual Solidity architecture analyzer

### Monitoring
* [Alethio](https://aleth.io/) - An advanced Ethereum analytics platform that provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search. Real-time market information and trading activities across Ethereum's decentralized exchanges can also be explored.
* [amberdata.io](https://amberdata.io) - Provides live monitoring, insights and anomaly detection, token metrics, smart contract audits, graph visualization and blockchain search.
* [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) - A tool to monitor a number of smart contracts and transactions
* [Scout](https://scout.cool/) - A live data feed of the activities and event logs of your smart contracts on Ethereum
* [Tenderly](https://tenderly.co/) - A platform that gives users reliable smart contract monitoring and alerting in the form of a web dashboard without requiring users to host or maintain infrastructure
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Explore smart contracts with decoded transaction data, see how the contract is used and search transactions with specific function calls
* [BlockScout](https://github.com/poanetwork/blockscout) - A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks.
* [Terminal](https://terminal.co/) - A control panel for monitoring dapps. Terminal can be used to monitor your users, dapp, blockchain infrastructure, transactions and more.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - An extensible framework written in Golang for listening to on-chain events and doing something in response.
* [Alchemy Notify](https://docs.alchemyapi.io/guides/alchemy-notify) - Notifications for mined and dropped transactions, gas price changes, and address activity for desired addresses. 
* [Blocknatve Mempool Explorer](https://www.blocknative.com/explorer) — Monitor any contract or wallet address and get streaming mempool events for every lifecycle stage — including drops, confirms, speedups, cancels, and more. Automatically decode confirmed internal transactions. And filter exactly how you want. Recieve events in our visual, no-code, interface or associate them with your API key to get events via a webhook. Mempool Explorer helps exchanges, protocols, wallets, and traders monitor and act on transactions in real-time.
* [Ethernal](https://www.tryethernal.com) - Ethereum block explorer for private chain. Browse transactions, decode function calls, event data or contract variables values on your locally running chain.

### Other Miscellaneous Tools
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - Packaged components for building DApps fast.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box
* [Solc](https://docs.soliditylang.org/en/latest/using-the-compiler.html) - Solidity compiler
* [Sol-compiler](https://sol-compiler.com/) - Project-level Solidity compiler
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Compile solidity-code faster, easier and more reliable
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternative, merges all imports into single file for solidity contracts
* [RLP](https://github.com/ethereumjs/rlp) - Recursive Length Prefix Encoding in JavaScript
* [eth-cli](https://github.com/protofire/eth-cli) - A collection of CLI tools to help with ethereum learning and development
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereal is a command line tool for managing common tasks in Ethereum
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity
* [Parity Signer](https://github.com/paritytech/parity-signer) - mobile app allows signing transactions
* [py-eth](http://py-eth.com) - Collection of Python tools for the Ethereum ecosystem
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Concats solidity files developed under Truffle with all of their dependencies
* [Decode](https://github.com/hacker-DOM/decode) - npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Typescript bindings for Ethereum smartcontracts
* [EthSum](https://ethsum.netlify.com) - A Simple Ethereum Address Checksum Tool
* [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) - allows indexing blocks or listening to Events in PHP
* [Purser](https://github.com/JoinColony/purser) - JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - Connect to MetaMask from node.js
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Documentation generator for Solidity projects
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Export Ethereum blockchain data to CSV or JSON files
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Prettier plugin for formatting Solidity code
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum and Unity integration demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum and Unity integration demo/sample
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum business rules engine demo/sample
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - A set of tools to standarize Solidity import and artifact resolution in frameworks.
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - A node and browser tool to inspect transactions - decoding where possible the method, event logs and any revert reasons using ABIs found online. 
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - A useful library written in Golang to reliably send a transaction — abstracting away some of the tricky low level details such as gas optimization, nonce calculations, synchronization, and retries.
* [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Seamlessly verify contract source code on Etherscan from the Truffle command line.
* [Blocknative Gas Platform](https://www.blocknative.com/gas) — Gas estimation for builders, by builders. Gas Platform harnesses Blocknative's real-time mempool data infrastructure to accurately and consistently estimate Ethereum transaction fees. This provides builders and traders with an up-to-the-moment gas fee API. 
* [ETH Gas.watch](https://ethgas.watch/) - A gas price watcher with email notifications on price change

### Smart Contract Standards & Libraries
#### [ERCs](https://eips.ethereum.org/erc) - The Ethereum Request for Comment repository
* Tokens
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Original token contract for fungible assets
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - Token standard for non-fungible assets
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - An improved token standard for fungible assets
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Mineable Token Standard
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - Creates a standard method to publish and detect what interfaces a smart contract implements.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - Proxy contract for key management and execution, to establish a Blockchain identity.
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - A standard interface for ownership of contracts

#### Popular Smart Contract Libraries
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - Contains tested reusable smart contracts like SafeMath and OpenZeppelin SDK [library](https://github.com/OpenZeppelin/openzeppelin-sdk) for smart contract upgradeability
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum.
* [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) - A group of packages built for use on blockchains utilising the Ethereum Virtual Machine
* [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - A gas-efficient Solidity date and time library
* [Aragon](https://github.com/aragon/aragon) - DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance
* [ARC](https://github.com/daostack/arc) - an operating system for DAOs and the base layer of the DAO stack.
* [0x](https://github.com/0xProject) - DEX protocol
* [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) - Contains correctness proofs of token contracts wrt. given specifications and high-level properties
* [Provable API](https://github.com/provable-things/ethereum-api) - Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation
* [ABDK Libraries for Solidity](https://github.com/abdk-consulting/abdk-libraries-solidity) - Fixed-point (64.64 bit) and IEEE-754 compliant quad precision (128 bit) floating-point math libraries for Solidity


### Developer Guides for 2nd Layer Infrastructure

#### Scalability



#### Payment/State Channels
* [Ethereum Payment Channel](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - Ethereum Payment Channel in 50 lines of code
* [µRaiden Documentation](https://microraiden.readthedocs.io) - Guides and Samples for µRaiden Sender/Receiver Use Cases

#### Plasma
* [Learn Plasma](https://github.com/ethsociety/learn-plasma) - Website as Node application that was started at the 2018 IC3-Ethereum Crypto Boot Camp at Cornell University, covering all Plasma variants (MVP/Cash/Debit)
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - OmiseGO's research implementation of Minimal Viable Plasma
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Golang implementation and extension of the Minimum Viable Plasma specification
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - Automatically watch and challenge or exit from Omisego Plasma Network when needed.
* [Plasma OmiseGo Watcher](https://github.com/mesg-foundation/service-plasma-omisego-watcher) - Interact with Plasma OmiseGo network and notifies for any byzantine events.

#### Side-Chains
* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Contracts](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### Privacy / Confidentiality

##### ZK-SNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - A toolbox for zkSNARKS on Ethereum
* [The AZTEC Protocol](https://github.com/AztecProtocol/AZTEC) - Confidential transactions on the Ethereum network, implementation is live on the Ethereum main-net
* [Nightfall](https://github.com/EYBlockchain/nightfall) - Make any ERC-20 / ERC-721 token private - open source tools & microservices
* Proxy Re-encryption (PRE)
** [NuCypher Network](https://github.com/nucypher/nucypher) - A proxy re-encryption network to empower data privacy in decentralized systems
** [pyUmbral](https://github.com/nucypher/pyumbral) - Threshold proxy re-encryption cryptographic library
* Fully Homomorphic Encryption (FHE)
** [NuFHE](https://github.com/nucypher/nufhe) - GPU accelerated FHE library

#### Scalability + Privacy

#### ZK-STARKs
* [StarkWare](https://github.com/starkware-industries) and [StarkWare Resources](https://github.com/starkware-libs) - StarkEx scalability engine storing state transitions on-chain

#### Prebuilt UI Components
* [aragonUI](https://ui.aragon.org) - A React library including Dapp components
* [components.bounties.network](https://components.bounties.network) - A React library including Dapp components
* [ui.decentraland.org](https://github.com/decentraland/ui) - A React library including Dapp components
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Reusable React Dapp components
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React Components
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - A cross-platform hybrid hosting mechanism for web based decentralised applications
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Cross-platform desktop wallet sample
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist donation button
* [Rimble Design System](https://rimble.consensys.design/) - Adaptable components and design standards for decentralized applications.
* [3Box Plugins](https://docs.3box.io/build/plugins) - Drop in react components for social functionality. Including comments, profiles and messaging.
