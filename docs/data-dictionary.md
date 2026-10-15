# Data Dictionary

## Contents

| Entity | Alternative Name | Description | Locations |
| ------ | ---------------- | ----------- | --------- |
| Product | Cloud Service Offering (CSO) | A specific cloud IaaS/PaaS/SaaS product operated by a Cloud Service Provider (CSP) that is intending to be FedRAMP Certified or is undergoing FedRAMP Certification. | `fedramp-frc-cso-pkg.json` |
| Assessor | Independent Assessment Service (IAS) | An organization that is accredited by the American Association for Laboratory Accreditation (A2LA) and is recognized by FedRAMP to perform FedRAMP assessment services. | `fedramp-mkt-ias-web.json` |
| Advisor | Advisory Service | Non-endorsed non-government organization that provides advisory services to other organizations around FedRAMP. | `fedramp-mkt-cas-web.json` |
| Agency | U.S. Federal Agency | A U.S. federal government agency or sub-agency/bureau with at least one Authorization to Operate (ATO) letter with a FedRAMP Certified CSO. | `fedramp-agencies.json` |
| ATO | Authority to Operate / Authorization to Operate | A letter issued by an agency’s Authorizing Official (AO) to accept the risk of having an external system interact with said agency’s information systems. | `fedramp-atos.json` |
| CertProcessChangeLog | Certification Process Change Log | A changelog managed by the FedRAMP office on the changes to a FedRAMP Certification over time. | `fedramp-status-changelog.json` |

### Directories
| Folder | Description | Schema |
| ------ | ----------- | ------ |
| `/advisors` | Contains JSON files from advisors which follow the FedRAMP Advisor Information (MKT-CAS-WEB) schema. File names are derived from advisor names. | https://github.com/FedRAMP/schemas/blob/main/fedramp-advisor-information-schema-2026-06-24.json
| `/assessors` | Contains JSON files from assessors which follow the FedRAMP Assessor Information (MKT-IAS-WEB) schema. File names are derived from assessor A2LA IDs. | https://github.com/FedRAMP/schemas/blob/main/fedramp-assessor-information-schema-2026-06-24.json
| `/products` | Contains JSON files from Cloud Service Providers which follow the FedRAMP Certification Package Overview (FRC-CSO-PKG) schema. File names are derived from their FedRAMP ID. | https://github.com/FedRAMP/schemas/blob/main/fedramp-certification-package-overview-schema-2026-06-24.json

## Schemas
See https://github.com/FedRAMP/schemas
