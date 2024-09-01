# Shipping-Route-Cost-Optimization
#Project Overview

This analysis focuses on optimizing the assignment of orders to plants and carriers to minimize overall shipping costs. The primary objectives are:

- Plant Selection: Identify the most suitable plant to process each order.
- Port Selection: Determine the optimal port for dispatching orders to their destinations.

#Constraints and Considerations
The optimization process takes into account the following constraints:

- Product-Plant Compatibility: Each plant is specialized to process only certain products.
- Plant-Port Connectivity: Each plant is connected to specific ports, limiting routing options.
- Vendor Managed Inventory (VMI): Certain customers operate under a VMI system, requiring their orders to be serviced by designated plants.
- Customer-Specific Plant Assignment: Some customers can only be serviced by specific plants.
- Physical Connectivity: Plants and ports must have an existing physical connection.
- Item Handling: Plants are limited to handling specific items, further constraining the assignment process.

#Data Source:
The dataset used for this analysis is sourced from Kaggle and was provided by Laurin Brechter. You can find the dataset here: https://www.kaggle.com/datasets/laurinbrechter/supply-chain-data/data.
