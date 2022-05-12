## Java

``` yaml $(java)
java:
    namespace: com.azure.maps.timezone
    license-header: MICROSOFT_MIT_NO_CODEGEN
    payload-flattening-threshold: 0
    output-folder: $(azure-libraries-for-java-folder)/azure-maps-timezone
    add-context-parameter: true
    context-client-method-parameter: true
    client-logger: true
    generate-client-as-impl: true
    sync-methods: all
    generate-sync-async-clients: false
    polling: {}
    models-subpackage: implementation.models
    custom-types-subpackage: models
    custom-types: ErrorAdditionalInfo,ErrorDetail,ErrorResponse,ErrorResponseException,CountryRecord,IanaId,TimezoneWindows,TimezoneResult,TimezoneOptions,TimezoneNames
```