# Veracode CycloneDX Property Taxonomy

This is the official Veracode CycloneDX property namespace and name taxonomy. It documents all custom key/value `properties` that may be added to components in CycloneDX SBOMs created using the Veracode software.

For more information about CycloneDX property taxonomies, refer to the [official documentation](https://github.com/CycloneDX/cyclonedx-property-taxonomy).

## `Veracode` Namespace Taxonomy

| Namespace              | Description                                                                                                             |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| `veracode:metadata`    | Namespace for all Veracode-specific properties dealing with top-level metadata values about applications and projects.  |
| `veracode:component`   | Namespace for all Veracode-specific properties related to components.                                                   |

## `veracode:metadata` Namespace Taxonomy

| Property Name                              | Description                                                                              |
| ------------------------------------------ | ---------------------------------------------------------------------------------------- |
| `veracode:metadata:type`                   | Veracode scan type (application, agent) supplied by API user via API parameter           |
| `veracode:metadata:version`                | Application/project version supplied by API user via API parameter                       |

## `veracode:component` Namespace Taxonomy

| Property Name                     | Description                                                                                                            |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| `veracode:component:first_found`       | Date component was first found in application.                                                                         |
| `veracode:component:last_seen`         | Date component was last seen in application.                                                                           |
