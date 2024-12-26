> [!Important]  
> This repository is using Unity SDK v4, superseeded by [v5](https://portal.thirdweb.com/unity/v5)

# unity-blockventure
Unity SDK Starter Template showcasing inventory, shop and marketplace systems

## Features
- Marketplace V3
- ERC20
- ERC1155

## Scenes
  
Contains a single scene:
- `00_Scene_Main`: Contains all game and blockchain elements, including gathering (ERC20, shopping (ERC1155), and trading (MarketplaceV3) systems.

Platforms supported: Standalone.

 ## Setup Instructions
 1. Clone this repository.
 2. Open in Unity 2022.3.17f1
 3. Create a [thirdweb api key](https://thirdweb.com/create-api-key)
 4. Make sure `com.thirdweb.blockventure` is an allowlisted bundle id for your API key, and enable Smart Wallets.
 5. Find your `ThirdwebManager` in `00_Scene_Main` and set the client id there.
 7. Press Play!

To build the game, make sure you follow our build instructions [here](https://github.com/thirdweb-dev/unity-sdk#build).

_Note: loading might take a little longer for first time users as the game sets up all approvals required for all systems using the smart wallet._

## Screenshots

![blockventure](https://github.com/thirdweb-example/blockventure/assets/43042585/206d94fa-b363-4093-ba8b-ff753ecf00b2)


## Documentation

- To build the game, follow the [build instructions](https://github.com/thirdweb-dev/unity-sdk#build)
- Learn more from the [Unity SDK Documentation](https://portal.thirdweb.com/unity)


## Contributing

Contributions are always welcome! See our [open source page](https://thirdweb.com/open-source) for more information. 


## Support 

For help or feedback, please [visit our support site](https://thirdweb.com/support)
