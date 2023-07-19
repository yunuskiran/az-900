### Redundancy Options

## Single Region
    - Locally Redundant Storage (LRS): Three copies in single location (datacenter/zone), Lowest cost option, Protect againist single disk failure, does not protect againist zone or regional outage
    - Zone-Redundant Storage(ZRS): Three copies across three availability zones, One copy in each zone, Protect againist zone outage but not regional outage

## Multi Region
    - Geo-Redundant Storage(GRS): Three copies in two different regions, Protect againist primary region failure but no primary region zone redundancy, Can configure read access from seconday region for high availability
    = Geo-Zone-Redundant Storage(GZRS): Maximum redundancy, Copy across three availability zones in primary region, Three copies in secondary region pyhsical location/zone, Protect againist primary region failure and primary zone failure, can also read access from seconday region high availability.