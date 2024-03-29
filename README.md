# Awesome Raiden

### Contents

- [⚡ Raiden Network](#-raiden-network)
  - [Specifications](#specifications)
  - [Explorers](#explorers)
- [⚡ Developer Resources](#-developer-resources)
  - [Tools](#tools)
  - [RApps](#rapps)
  - [Ether Faucets](#ether-faucets)
    - [ERC20 Faucets](#erc20-faucets)
    - [Hackathon](#hackathon)
- [⚡ Starting a Raiden Full Node](#-starting-a-raiden-full-node)
  - [Testnet](#mainnet)
  - [Mainnet](#mainnet)
  - [Connectivity](#connectivity)
- [⚡ Learning Resources](#-learning-resources)
  - [Talks](#talks)
  - [Research Calls](#research-calls)
  - [Pulse](#pulse)
  - [dApp Testing](#dapp-testing)
- [⚡ Community](#-community)
  - [Community Channels](#community-channels)
- [⚡ Raiden Trust](#-raiden-trust)
- [⚡ MicroRaiden](#-microraiden)
- [⚡ Other Resources](#-other-resources)

# ⚡ Raiden Network

- [Website](https://raiden.network/)
- [Github](https://github.com/raiden-network/)
- [Dev Chat](https://gitter.im/raiden-network/raiden)
- [Reddit](https://www.reddit.com/r/raidennetwork)
- [Twitter](https://twitter.com/raiden_network)

### Specifications

- [Raiden Network Documentation (stable)](https://raiden-network.readthedocs.io/en/stable/)
- [Raiden Network Specification (latest)](https://media.readthedocs.org/pdf/raiden-network-specification/latest/raiden-network-specification.pdf)
- [Raiden Services Documentation (latest)](https://raiden-services.readthedocs.io/en/latest/)
  - [Monitoring Service](https://raiden-network-specification.readthedocs.io/en/latest/monitoring_service.html)
  - [Pathfinding Service](https://raiden-network-specification.readthedocs.io/en/latest/pathfinding_service.html)
  - [Smart contracts for Raiden Services](https://raiden-network-specification.readthedocs.io/en/latest/service_contracts.html)

### Explorers

- [Mainnet](https://explorer.raiden.network)
- [Kovan](https://kovan.explorer.raiden.network)
- [Ropsten](https://ropsten.explorer.raiden.network)
- [Goerli](https://goerli.explorer.raiden.network)
- [Rinkeby](https://rinkeby.explorer.raiden.network)

## ⚡ Developer Resources

- [Releases List](https://github.com/raiden-network/raiden/releases) (+[nightly releases](https://raiden-nightlies.ams3.digitaloceanspaces.com/index.html))

<sub><sup>Note: The following sections include WIP and demo projects.</sup></sub>

### Tools

- [EthArmbian](http://ethraspbian.com/) - turns NanoPC-T4 or RockPro64 into a full Ethereum node. Includes components of the Ethereum ecosystem such as Raiden Network([version check](https://github.com/diglos/userpatches#ethereum-framework)), Trinity, Status.im, IPFS, Swarm and Vipnode. Initial support for Eth2.0 clients.
- [Raiden Burner](https://github.com/johngrantuk/raidenburner), [demo](https://youtu.be/Pn0gsljGalo) - add an easy to use Raiden payment option to the [Burner Wallet](https://github.com/austintgriffith/burner-wallet)
- [Grid Ethereum Plugin](https://github.com/PhilippLgh/ethereum-grid-tutorials/blob/cfb3b205374a34550e43cdbdbb4ec7e90a2d4bf4/Raiden.md) - the functionality with a plugin and a Web UI
- [Raiden Ticker](https://github.com/pisuthd/raiden-ticker) - integrate Raiden's payment channel with IoT devices
- [Docker Hub](https://hub.docker.com/r/raidennetwork/raiden) and Use Docker, Infura.io to [Build Raiden Network on Ubuntu 18.04](https://medium.com/@szhao_31738/use-docker-infura-io-to-build-raiden-network-on-ubuntu-18-04-a5eae7357f61) tutorial
- PyPI for [Raiden](https://pypi.org/project/raiden/) and [Raiden Services](https://pypi.org/project/raiden-services/)
- [DAppNode](https://github.com/dappnode/DAppNodePackage-raiden) (+[DAppNode docs](https://dappnode.github.io/DAppNodeDocs/install/) +[testnet version](https://github.com/vdo/DAppnodePackage-raiden-testnet)) - DAppNode package for the Raiden network
- [Raiden Scenario Player](https://github.com/raiden-network/scenario-player) - integration testing tool
- [Homebrew Tap](https://github.com/raiden-network/homebrew-raiden) for Raiden
- [WebUI](https://github.com/raiden-network/webui) - Raiden Web User Interface
- [Test environment scripts](https://github.com/kelsos/test-environment-scripts) - a collection of scripts used to bootstrap a test raiden environment
- [Raiden Express Server](https://github.com/TarCode/raiden-express-server) and [Raiden React Client](https://github.com/TarCode/raiden-react-client) - an Express Server that connects to a Raiden Client
- [Parity Docker Raiden dev env](https://github.com/calinchiper/parity-docker-raiden-dev-env) - Dockerized POA Parity blockchain + Raiden network contracts deployment scripts & config generator
- [Token Network's Channels](https://github.com/manuelwedler/token-network-channels) - Small dApp displaying Token Network's Channels (part of the Raiden network)
- [Raiden Invoice](https://github.com/ChaeByunghoon/raiden-invoice) and [Invoice Server](https://github.com/ChaeByunghoon/raiden-invoice-server) - A library for encoding and decoding Raiden network payment requests
- [Go Raiden Client](https://github.com/cpurta/go-raiden-client) - A Raiden node client written in Go
- [PyRaiden](https://github.com/nanspro/PyRaiden) - A client library to interact with Raiden Network written in python
- [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Run a local Raiden network in docker containers for demo and testing purposes

### RApps

- [Fairspot](https://github.com/ilinzweilin/ethCapeTown) - WiFi internet access on the go (in 100kb chunks) using Raiden
- [NUtube](https://nutube.network/#/), [Github](https://github.com/CryptoManiacsZone/nuTube.network), [demo](https://www.youtube.com/watch?v=Tx-j0TubY7k) - decentralized P2P live streaming w/ micropayments
- [DTok](https://github.com/ethcapetown/burner-wallet/tree/dtok-raiden), [demo](https://www.youtube.com/watch?v=2CFAJCfKs-8) - decentralized streaming and tipping platform w/ Raiden, BurnerWallet ([link](https://github.com/austintgriffith/burner-wallet)) and ENS domains
- [Raiden Light Client](https://github.com/raiden-network/light-client) - Raiden Light Client SDK and dApp
- [The Raiden dApp](http://lightclient.raiden.network) - a reference implementation of the Raiden Light Client SDK
- [XUD](https://github.com/ExchangeUnion/xud/) - a decentralized exchange built on the Lightning and Raiden networks to enable instant and trustless cryptocurrency swaps
- [Raiden Maps](https://medium.com/raiden-map/raiden-map-mockups-5586082693bf), [Github](https://github.com/raiden-map)
- [Storj](https://github.com/stefanbenten/raiden-on-storj), [Medium post](https://storj.io/blog/2018/12/taking-payments-to-the-next-level-with-raiden/) - decentralized cloud storage
- [CryptoBotWars](https://cryptoplayer.one), [GitHub](https://github.com/cryptoplayerone/cryptobotwars), Medium posts [Part 1](https://medium.com/@loredana.cirstea/cryptobotwars-or-how-to-build-shitty-demos-and-why-19b5ecf60c76) and [Part 2](https://medium.com/@loredana.cirstea/cryptobotwars-part-2-conclusions-ebde6fa716f6) - Tic Tac Toe w/ micropayments and a Game Guardian
- [Team SCG](https://github.com/StupidCatGentlemen/Ether) - buying and supplying electricity on an open marketplace using Raiden for payments.
- [Cryptogrannies](https://github.com/swops-io/ETHSingapore-project) - pushing crypto to be simple enough to be used by the oldies
- [Raidenooh](https://github.com/pisuthd/raiden-dooh) - decentralized digital signage platform

### Ether Faucets

🏃Need testnet Ether?!
- [Ropsten](https://faucet.ropsten.be/)
- [Rinkeby](https://faucet.rinkeby.io/)
- [Kovan](https://faucet.kovan.network/)
- [Goerli](https://faucet.goerli.mudit.blog/)

Or if you have MetaMask installed then try the [MetaMask faucets](https://faucet.metamask.io).

#### ERC20 Faucets

Wrap ether on [0x protocol](https://0x.org/portal). 🏃Need testnet ERC20 tokens quick?! Try [bokkypoobah](https://github.com/bokkypoobah/WeenusTokenFaucet)'s ERC20 token faucet. For example, send a 0 value transaction from your account to the address below on your preferred network and you'll get 1,000 XEENUS tokens:
- [Ropsten](https://ropsten.etherscan.io/address/0x7E0480Ca9fD50EB7A3855Cf53c347A1b4d6A2FF5#code): 0x7E0480Ca9fD50EB7A3855Cf53c347A1b4d6A2FF5
- [Rinkeby](https://rinkeby.etherscan.io/address/0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c#code): 0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c
- [Kovan](https://kovan.etherscan.io/address/0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c#code): 0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c
- [Goerli](https://goerli.etherscan.io/address/0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c#code): 0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c

### Hackathon

The [GROW ETHEREUM](https://gitcoin.co/hackathon/grow-ethereum) hackathon. Jul 29, 2019 - Aug 15, 2019. A three-week virtual hackathon where global developers and entrepreneurs will collaborate to push blockchain applications to new frontiers of business + technology + social change.
- [Join the Gitcoin hackathon discord channel](https://discord.gg/jzmb2y)
- [Raiden specific hackathon repo](https://github.com/raiden-network/hackathons/issues)
- RECOMMENDED to use [v0.100.3](https://github.com/raiden-network/raiden/releases/tag/v0.100.3) of Raiden Network for hacking!
- Bounties:
  - [Build A Raiden Library In Your Favorite Programming Language](https://gitcoin.co/issue/raiden-network/hackathons/4/3284)
  - [Build The Raiden UI 2.0!](https://gitcoin.co/issue/raiden-network/hackathons/5/3285)
  - [BWYL (Build Whatever You Like!) / Open Bounty: Raiden + X = 🔥](https://gitcoin.co/issue/raiden-network/hackathons/6/3286)
[![RaidenHack](https://user-images.githubusercontent.com/35585644/62123517-70cce880-b30b-11e9-9a36-fa16ef362b32.jpeg)](https://twitter.com/raiden_network/status/1156121197660319744)

Need ideas?! Check out [RApps](#rapps) and [Tools](#tools). Additionally, here's some resources from the previous hack:
- Winners: [Golang client library](https://github.com/cpurta/go-raiden-client) and [Raiden Ticker](https://github.com/pisuthd/raiden-ticker)
- Video: ["Beyond Blockchain Hackathon: Raiden"](https://youtu.be/wdz8M3RXJQs)
- Unfinished idea: Integrate Raiden support into Zerynth. [Idea TL;DR here](https://github.com/raiden-network/hackathons/issues/2#issuecomment-509925857)

## ⚡ Starting a Raiden Full Node

[System Requirements and Installation Guide](https://raiden-network.readthedocs.io/en/latest/overview_and_guide.html). You should usually try new things on Ethereum on testnet before mainnet so you can get a hang of it, this includes trying Raiden Network.

### Testnet

🏃Need to try a Raiden node quick on testnet?! Option 1: Use [Raiden Wizard](https://medium.com/raiden-network/introducing-the-raiden-wizard-6c7c61c5b695) to get a testnet node started in just a couple of minutes.

Option 2: Follow the [workshop](https://github.com/raiden-network/workshop/tree/tu-berlin-blockchain-labs). If you happen to be on Windows, [this community video](https://youtu.be/RpaAS64dI6k) includes the added steps with using WSL ([if you get stuck](https://t.me/RaidenNetworkCommunity)). You can skip signing up for Infura on Goerli by adding `--eth-rpc-endpoint https://rpc.slock.it/goerli`. So replacement node start command (from [this](https://github.com/raiden-network/workshop/tree/tu-berlin-blockchain-labs#running-raiden)) becomes:
```
./raiden-v0.100.3-linux-x86_64 --keystore-path keystore --network-id goerli --gas-price fast --environment-type development --eth-rpc-endpoint https://rpc.slock.it/goerli
```
Your node is now running on Goerli testnet. Open your web browser and put `127.0.0.1:5001` to open the WebUI.

### Mainnet

Follow the [Raiden Red Eyes Mainnet Tutorial](https://raiden-network.readthedocs.io/en/latest/red_eyes_mainnet_tutorial.html). 🏃Need to try Raiden quick on mainnet?! If you've already completed the workshop steps above, Infura will work great! You can always switch to using your own Eth Node later on. To get an Infura key you'll need to:
- Visit [infura.io](https://infura.io/) and click to sign up for a new account.
- Then, choose to create a new project.
- Now, view your project and you'll find the Project ID under the __KEYS__ section ("<MAINNET_INFURA_KEY>" used below).
- Start your node with:
```
./raiden-v0.100.3-linux-x86_64 --keystore-path keystore --eth-rpc-endpoint eth-rpc-endpoint https://mainnet.infura.io/v3/<MAINNET_INFURA_KEY>
```

A great permanent mainnet option is to use Raiden with [DAppNode](https://medium.com/raiden-network/run-raiden-on-dappnode-a45a1f63609b)! It will take some extra time to setup and sync for the first time if you don't have an Eth Node synced already.

### Connectivity

Want to find some Raiden nodes online already to connect to? Here's a few :)
- [Mainnet](https://etherscan.io/address/0x865b332B0B058C472Ee3B46C5a66b8D1699740E1)
- [Ropsten](https://ropsten.etherscan.io/address/0x5257964ef9b81fba7276af2a97c111aad7b840d6)
- Goerli: [1](https://goerli.etherscan.io/address/0xef0BCf6BBE8E67DEcc1F395CA67922663529F4F4), [2](https://goerli.etherscan.io/address/0xD4945bC6D538709B3431A84c4bEf24be341FbacB), [3](https://goerli.etherscan.io/address/0x2cCEfE5eCEc08A8de5bA96A064d789C0ABa50558), [4](https://goerli.etherscan.io/address/0x83c761f7ABa11A840c59d461921504603d8fc6e8) (connected 1<->4 on the [XEENUS token network](https://goerli.explorer.raiden.network/tokens/0x022E292b44B5a146F2e8ee36Ff44D3dd863C915c/), if you want to try multi-hop payments quickly)

🏃Need multiple accounts of your own to test with?! Use [Geth](https://github.com/ethereum/go-ethereum/wiki/Installing-Geth) `geth account new` to create them quickly. They will be stored in `~/.ethereum/keystore/`. List them with `geth account list` (alternatively, if you don't have Geth, rerun the [Workshop onboarder](https://github.com/raiden-network/workshop/#on-boarding)). You can open as many nodes as you want on your local machine by giving different port numbers when starting Raiden. For example `--api-address http://127.0.0.1:5002` starts a Raiden node on port 5002 instead of the default 5001.

## ⚡ Learning Resources

- [Raiden FAQ](https://raiden.network/faq.html)
- [Medium Publications](https://medium.com/@raiden_network) / [Blog](https://medium.com/raiden-network)
- [Reddit Weekly Update](https://www.reddit.com/r/raidennetwork/search?q=GIT&restrict_sr=1&sort=new)
- [Raiden Network WebUI Demo](https://youtu.be/ASWeFdHDK-E)
- [Raiden youtube channel](https://youtube.com/channel/UCoUP_hnjUddEvbxmtNCcApg)
- [How to install a Raiden node on the Ethereum Mainnet](https://youtu.be/fy2ctCQHfD4)
- [Raiden Service Bundle Explained](https://medium.com/raiden-network/raiden-service-bundle-explained-f9bd3f6f358d) - fees to Monitoring Services and Pathfinding Services paid in RDN
- Research Calls:
  - [Layer 2 Community Call #1: Routing in state channel networks](https://youtu.be/SUxe_WJw5Yw)
  - [State Channel Researchers Call #6](https://youtu.be/YzomDzpLW_o)
- Send "/videos" to [RaidenInfoBot](https://t.me/RaidenInfoBot) for more videos!
- Send "/events" to [RaidenInfoBot](https://t.me/RaidenInfoBot) for upcoming community events!

### Pulse

- [Raiden Pulse #6:](https://medium.com/raiden-network/raiden-pulse-6-news-from-may-and-june-f519818e7650) News from May and June
- [Raiden Pulse #5:](https://medium.com/raiden-network/raiden-pulse-5-news-from-march-and-april-56e781aea7c) News from March and April
- [Raiden Pulse #4:](https://medium.com/raiden-network/raiden-pulse-4-news-from-january-and-february-a25dbee298de) News from January and February
- [Raiden Pulse #3:](https://medium.com/raiden-network/raiden-pulse-3-news-from-november-and-december-dd0da04961d3) News from November and December
- [Raiden Pulse #2:](https://medium.com/raiden-network/raiden-pulse-2-news-from-september-and-october-6a6c6be8ad67) News from September and October
- [Raiden Pulse #1:](https://medium.com/raiden-network/raiden-pulse-1-news-from-july-and-august-423fae4e9d3e) News from July and August

### dApp Testing

Resources for trying the WIP Raiden dApp in your browser. The Light Client works on Ropsten/Rinkeby/Goerli/Kovan, here we'll use Ropsten.
1. Make sure you have MetaMask installed and connected to Ropsten Test Network
![ropsten](https://user-images.githubusercontent.com/35585644/61182722-b5edeb00-a67a-11e9-9930-bfa4db704244.png).
2. Get testnet Ether on [Ropsten](https://faucet.ropsten.be/) (going off-chain with Raiden requires on-chain interactions, i.e. Gas).
3. Wrap Ether using the [0x Portal](https://0x.org/portal/weth). MetaMask might not show the correct wrapped Ether on testnet after you've wrapped it. If so, click on MetaMask and add Custom Token 0xc778417e063141139fce010982780140aa0cd5ab
![addweth](https://user-images.githubusercontent.com/35585644/61182725-c43c0700-a67a-11e9-9ca5-19cb67341cf5.png)
4. Start the Raiden dApp [here](http://lightclient.raiden.network). You can now use the dApp to open, close and settle channels.

note: The dApp user interface is very early WIP<sup>[explained more here](https://t.me/RaidenNetworkCommunity/28310)</sup>, the first milestone will enable sending tokens and not receiving them. If you're interested to get the full experience of Raiden you will want to run a full Raiden node and use the WebUI to get a good experience.

## ⚡ Community

[Raiden Workshop Configurator](https://workshops.raiden.network/) - host a Raiden workshop or meetup! 😃

- [Emerging Tech for Beginners: Convergence of Emerging Technologies with Brett Robertson of Ethereum](https://youtu.be/81_pz2J5zRs)
- [Meeting Raiden @ Web3Summit](http://reddit.com/r/raidennetwork/comments/9red2i/meeting_raiden_web3summit/) and [Raiden: Ethereum's Payment Channel Network](https://medium.com/@surferfc/raiden-ethereums-payment-channel-network-acc6e5c709b0)
- [Non-profit 3D printed Raiden model](https://www.shapeways.com/shops/raiden)
- [Red Eyes on testnet](https://youtu.be/RpaAS64dI6k)
- [Github Visualization](https://youtu.be/xqxTGF--Bhk)
- Watchtower scaling: Lightning VS Raiden [#1](https://medium.com/crypto-punks/lightning-vs-raiden-watchtowers-monitoring-services-differences-c8eb0f724e68), [#2](https://medium.com/crypto-punks/lightning-vs-raiden-watchtowers-monitoring-services-solutions-e243f7793d19) and [#3](https://medium.com/crypto-punks/lightning-vs-raiden-watchtowers-accountability-business-models-celer-pisa-833384f01ad0)
- [Messari Raiden Network profile report](https://messari.io/asset/raiden-network#profile)
- [Community built FAQ on Reddit](https://www.reddit.com/r/raidennetwork/comments/7hhkv5/work_in_progress_raiden_network_and_token_faq/)
- [Raiden PFS in action!](https://twitter.com/mat77ias/status/1148921006863466497)
- [RaidenInfoBot](https://t.me/RaidenInfoBot) Telegram bot ([Github](https://github.com/mat7ias/RaidenResourcesBot/)) with a collection of resources about Raiden Network (and some misc. features). Currently running in https://t.me/RaidenNetworkCommunity (unofficial)

### Community Channels

- [RNC Telegram](https://t.me/RaidenNetworkCommunity) - where RaidenInfoBot lives
- [Discord](https://discord.gg/zZjYJ6e) - bridge and feeds (most maintained)
- [Slack](https://join.slack.com/t/raidencommunity/shared_invite/enQtNTQwMTM5MjY4MTQ4LTBlOTQzMjUyOGFkMTgwOGQyMmMyNTE0MmI0YmI4OTQ5MjY3N2FkYTVlNWRkODdkNmIwMWQzZDBjODAyZGFhOWI) - bridge and feeds
- [Matrix/Riot](https://riot.im/app/#/room/#raidencommunity:matrix.org) - bridge

<sub><sup>note: community channels are run by the community</sup></sub>

## ⚡ Raiden Trust
- [Raiden Trust Website](https://www.raidentrust.li/)
- [Twitter](https://twitter.com/raiden_trust)
- Announcement [Introducing Raiden Trust](https://medium.com/raiden-network/introducing-the-raiden-trust-cd47db60146)
- [Apply now](https://medium.com/raiden-network/apply-now-for-a-raiden-trust-grant-aca7d3e1e908) for the first wave of Raiden Trust grants

## ⚡ MicroRaiden

- [MicroRaiden Website](https://micro.raiden.network/)
- [MicroRaiden Github repo](https://github.com/raiden-network/microraiden)
- [MicroRaiden Docs](https://microraiden.readthedocs.io/en/docs-develop/)
- [MicroRaiden Dev Chat](https://gitter.im/raiden-network/microraiden)

### MicroTalks

- [Devcon3](https://youtu.be/yx0__aFvjzk?t=9m35s)
- [Berlin Meetup drone demo](https://youtube.com/watch?v=E6CIgJPxgpQ)
- [ScalingNOW!](https://youtu.be/81gK-5qLFeg)

### MicroRApps

- [AppStoreFoundation](https://hackernoon.com/anu-2-app-store-foundation-and-dev-status-a3de6d144e5f), [Github](https://github.com/AppStoreFoundation/asf-sdk) - sell in-app items for AppCoins
- [SmartMesh/SmartRaiden](https://smartmesh.io/) - internet-free digital payments and transactions
- [RightMesh](https://www.rightmesh.io/) - ad hoc mobile mesh networking platform and protocol

## ⚡ Other Resources

Resources indirectly related to Raiden Network
- [dxDAO Vote Staking Interface](https://dxdao.daostack.io) - lock RDN tokens to earn voting power for the [@dxDAO](https://twitter.com/_dx_dao). Staking period has finished.
- [dxDAO Alchemy](https://alchemy.daostack.io/dao/0x519b70055af55a007110b4ff99b0ea33071c720a)
