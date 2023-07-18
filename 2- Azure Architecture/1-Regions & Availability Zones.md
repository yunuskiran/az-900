### Regions & Availability Zones

## Regions
A region is a set of datacenters deployed withing a latency-defined perimeter and connected through a dedicated regional low-latency network.

## How to choose region
  - Location: Choose a region closest to your users to minimize latency
  - Features: Some features aren't in all regions. If you neeed a specific feature, some regions must be unavilable.
  - Price: The price of services vary from region to region.

## Paired Region
  - Paired within same geographic area except Brazil South.
  - If the primary region has an outage you can failover to the secondary region.
  - Only one region in a pair is updated at any one time.
  - Some services used paired for replication.

## Availabilty Zones
  - Each Availability zone is a pysical location within a region.
  - Each zone has its own power, cooling and networking.
  - Each region has a minumum of three zones.
