# Veracode CycloneDX Property Taxonomy

This is the official Veracode CycloneDX property namespace and name taxonomy. It documents all custom key/value `properties` that may be added to components in CycloneDX SBOMs created using the Veracode software.

For more information about CycloneDX property taxonomies, refer to the [official documentation](https://github.com/CycloneDX/cyclonedx-property-taxonomy).

## `Veracode` Namespace Taxonomy

| Namespace              | Description                                                                                                             |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `veracode:metadata`    | Namespace for all Veracode-specific properties dealing with top-level metadata values about bill of materials           |
| `veracode:component`   | Namespace for all Veracode-specific properties related to components.                                                   |

## `veracode:metadata` Namespace Taxonomy

| Property Name                              | Description                                                                                         |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| `veracode:metadata:linked`                 | True/False API parameter supplied by API user whether results from linked projects were included    |

## `veracode:component` Namespace Taxonomy

| Property Name                          | Description                                                                                             |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| `veracode:component:app_id`            | GUID for application                                                                                    |
| `veracode:component:project_id`        | GUID for project                                                                                        |
| `veracode:component:scan_id`           | GUID for latest scan                                                                                    |
| `veracode:component:scan_name`         | Name of latest scan                                                                                    |
| `veracode:component:last_scan_date`    | Date application or project was last scanned                                                            |
| `veracode:component:first_found_date`  | Date component was first found in application or project                                                |
