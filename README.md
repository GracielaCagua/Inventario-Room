# Inventario Room

App Android (Kotlin + Jetpack Compose) de los codelabs "Persist data with Room" y
"Read and update data with Room".

- Entity `Item`, DAO `ItemDao`, base de datos `InventoryDatabase`
- Repositorio `OfflineItemsRepository` e inyeccion de dependencias manual (`AppContainer`)
- `HomeScreen`: lista de articulos (LazyColumn) con StateFlow
- `ItemDetailsScreen`: detalle, boton Sell (reduce cantidad) y Delete (elimina)
- `ItemEditScreen`: edicion de un articulo
- Pruebas instrumentadas del DAO: `androidTest/.../ItemDaoTest.kt`
