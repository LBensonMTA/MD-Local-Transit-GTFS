# Maryland Local Transit GTFS Feeds

This repository contains General Transit Feed Specification (GTFS) feeds for Maryland local transit systems, managed and updated by the Office of Local Transit Support at the Maryland Transit Administration (MTA).

## About GTFS

The General Transit Feed Specification (GTFS) is a common format for public transportation schedules and associated geographic information. GTFS feeds allow public transit agencies to publish their transit data in a format that can be consumed by a wide variety of software applications.

## Repository Structure

```
├── feeds/
│   ├── current/     # Active GTFS feeds currently in use
│   └── archived/    # Historical GTFS feeds for reference
├── documentation/   # Documentation about feed management and processes
└── tools/          # Validation scripts and utilities
```

## Using These Feeds

The `feeds/current/` directory contains the most up-to-date GTFS feeds for Maryland local transit systems. Each transit system has its own subdirectory containing the GTFS feed files.

Archived feeds can be found in the `feeds/archived/` directory, organized by transit system and date.

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on updating feeds and maintaining this repository.

## Contact

This repository is maintained by the Office of Local Transit Support at the Maryland Transit Administration.

For questions or issues regarding these feeds, please open an issue in this repository.

---

**Last Updated:** 2026-02-10
