# yv202Optimization: Optimizing Service Allocation for Istanbul Rail Transfer Stations

## Overview
This project aims to optimize metro schedules to reduce overcrowding in Istanbul's metro system. It focuses on analyzing passenger demand and trip schedules using IBB transaction data, employing Integer Linear Programming (ILP) and Weighted Integer Linear Programming (WILP) to determine the additional trips needed at transfer stations.

## Objectives
- Reduce overcrowding at key transfer hubs.
- Optimize trip schedules using limited available data.
- Provide a scalable model for future enhancements.

### Optimization
- **ILP Constraints**: Non-negative integer trips ensuring capacity meets or exceeds demand.
- **Weighted ILP**: Prioritized transfer hubs, with minimal difference from unweighted results.

## Discoveries
- Significant overcrowding at several transfer hubs.
- ILP results show balanced additional trips across stations, with weighted ILP slightly favoring transfer hubs.
