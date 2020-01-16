---
dep: Use the 'layers.data' option instead
default: undefined
type: array | string
---
---
##### notUsedInTheme

##### deprecated
Use the **layers** | [dataSource](/api-reference/20%20Data%20Visualization%20Widgets/70%20dxVectorMap/1%20Configuration/layers/dataSource.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/layers/#dataSource') option instead.

##### shortDescription
Specifies a data source for the map markers.

---
Data you need to provide for map markers depends on the [type](/api-reference/20%20Data%20Visualization%20Widgets/70%20dxVectorMap/1%20Configuration/markerSettings/type.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/markerSettings/#type') of the markers you use. Generally, you need to declare an array of objects, each of which must hold the **coordinates** field specifying geographical coordinates of a marker. Additionally, you need to specify the **value** field (for *bubble* markers), or the **values** field (for *pie* markers), or the **url** field (for *image* markers). To display a label for a marker, specify the **text** field.

For a more comprehensive description of how to provide data for map markers, see the [Data for Markers](/concepts/20%20Data%20Visualization/35%20VectorMap/20%20Providing%20Data/20%20Data%20for%20Markers.md '/Documentation/Guide/Data_Visualization/VectorMap/Providing_Data/#Data_for_Markers') topic.