## Maryland Transit Administration (maryland-transit-administration)

The Maryland Transit Administration (MDOT MTA) supports open transit data initiatives and makes resources available to developers and applications. It primarily uses the General Transit Feed Specification (GTFS) and GTFS-RT to convey schedule, geographic, fare, vehicle position, and trip update data for Local Bus, Light Rail, Metro Subway, MARC Train, and Commuter Bus services in a standardized format.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/maryland-transit-administration/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Government, GTFS, GTFS-RT, Public Transportation, Transit, Bus, Rail, Subway

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-04-28

## APIs

### MDOT MTA Local Bus GTFS

Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Local Bus service. Includes GTFS-Fares V2 fare data.

- **Base URL:** `https://feeds.mta.maryland.gov/gtfs/local-bus`

### MDOT MTA Light Rail GTFS

Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Light Rail service. Includes GTFS-Fares V2 fare data.

- **Base URL:** `https://feeds.mta.maryland.gov/gtfs/light-rail`

### MDOT MTA Metro Subway GTFS

Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Metro Subway service. Includes GTFS-Fares V2 fare data.

- **Base URL:** `https://feeds.mta.maryland.gov/gtfs/metro`

### MDOT MTA MARC Train GTFS

Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA MARC commuter rail service.

- **Base URL:** `https://feeds.mta.maryland.gov/gtfs/marc`
- **GTFS-RT Trip Updates:** `https://mdotmta-gtfs-rt.s3.amazonaws.com/MARC+RT/marc-tu.pb`
- **GTFS-RT Vehicle Positions:** `https://mdotmta-gtfs-rt.s3.amazonaws.com/MARC+RT/marc-vp.pb`

### MDOT MTA Commuter Bus GTFS

Static GTFS feed and GTFS-RT vehicle positions and trip updates for MDOT MTA Commuter Bus service.

- **Base URL:** `https://feeds.mta.maryland.gov/gtfs/commuter-bus`

### MDOT MTA Service Alerts

System-wide GTFS-RT service alerts feed for all MDOT MTA modes.

- **Base URL:** `https://feeds.mta.maryland.gov/alerts.pb`

## Common Properties

- [Portal](https://www.mta.maryland.gov/developer-resources)
- [Website](https://www.mta.maryland.gov/)
- [GTFS Specification](https://gtfs.org/)
- [Swiftly Documentation](https://swiftly-inc.stoplight.io/docs/realtime-standalone/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
