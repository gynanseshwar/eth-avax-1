# Agriculture Smart Contract 

## Overview

This Solidity smart contract, named "Agriculture," provides a simple implementation for managing plants in an agricultural setting on the Ethereum blockchain. It includes functions for planting seeds, simulating crop growth, and harvesting crops.

## Smart Contract Details

### State Variable

- `numberOfPlants`: Represents the current number of plants in the agricultural system.

### Functions

1. **plantSeeds(uint256 _initialPlants)**
   - Allows users to plant seeds with an initial specified number of plants.
   - Requires the initial number of plants to be a positive value.

2. **simulateCropGrowth()**
   - Simulates crop growth by doubling the current number of plants.
   - Utilizes the `assert` statement to ensure the validity of the growth operation.

3. **harvestCrops()**
   - Enables users to harvest crops by setting the number of plants to zero.
   - Includes a boundary check using `revert` to prevent harvesting when there are no remaining plants.

## Usage

1. **Deploying the Smart Contract:**
   - Deploy the smart contract to the Ethereum blockchain.

2. **Planting Seeds:**
   - Call the `plantSeeds` function with the desired initial number of plants.
   - Ensure the initial number of plants is a positive value.

3. **Simulating Crop Growth:**
   - Invoke the `simulateCropGrowth` function to simulate the growth of crops.
   - The contract uses `assert` to validate the growth operation.

4. **Harvesting Crops:**
   - Call the `harvestCrops` function to harvest the crops.
   - The contract includes a boundary check using `revert` to prevent harvesting when there are no remaining plants.

## License

This smart contract is released under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Disclaimer

This smart contract is a basic example for educational purposes and should be used cautiously in real-world applications. Ensure proper testing and security audits before deploying in production.

## Author

[Gynaneshwar]
[din080ss55@gmail.com]
[07/12/2023]

