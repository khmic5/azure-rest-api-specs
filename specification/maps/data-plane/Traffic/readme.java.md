## Java

``` yaml $(java)

directive:
  - rename-model:
      from: TrafficFlowSegmentData
      to: TrafficFlowSegmentDataPrivate

java:
    namespace: com.azure.maps.traffic
    license-header: MICROSOFT_MIT_NO_CODEGEN
    payload-flattening-threshold: 0
    output-folder: $(azure-libraries-for-java-folder)/azure-maps-traffic
    add-context-parameter: true
    context-client-method-parameter: true
    client-logger: true
    generate-client-as-impl: true
    sync-methods: all
    generate-sync-async-clients: false
    polling: {}
    models-subpackage: implementation.models
    custom-types-subpackage: models
    custom-types: TileFormat,TrafficFlowTileStyle,TileIndex,ErrorAdditionalInfo,ErrorDetail,ErrorResponse,ErrorResponseException,DelayMagnitude,IconCategory,IncidentDetailStyle,IncidentGeometryType,ProjectionStandard,ResponseFormat,SpeedUnit,TileFormat,TrafficFlowSegmentStyle,TrafficFlowTileStyle,TrafficIncidentTileStyle,TrafficIncidentPointOfInterest
```