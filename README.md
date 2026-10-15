# marketplace-fedramp-gov-data
This is the data store for FedRAMP certification data and FedRAMP certification status changes data.

## Repository Contents
For a description of each entity and its corresponding file location, see:
- [Data Dictionary](docs/data-dictionary.md)

## Update frequency
* Legacy FedRAMP certification data and associated agency and assessor mappings (`data.json`) will be uploaded between 2-3 AM ET daily.
* Marketplace status changelog (`fedramp-status-changelog.json`) will be uploaded between 3-4 AM ET daily.
* `fedramp-frc-cso-pkg.json` (Products), `fedramp-mkt-cas-web.json` (Advisors), and `fedramp-mkt-ias-web.json` (Assessors) are updated as needed.

## JSON Schemas
JSON Schemas related to the export artifacts are located on https://github.com/FedRAMP/schemas.
