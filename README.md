# Inventario Room

App Android (Kotlin + Jetpack Compose) del codelab "Persist data with Room".

- `data/Item.kt` -> Entity (@Entity, tabla "items")
- `data/ItemDao.kt` -> DAO (insert, update, delete, getItem, getAllItems)
- `data/InventoryDatabase.kt` -> Base de datos Room (singleton)
- `data/OfflineItemsRepository.kt` -> Repositorio que usa el DAO
- `data/AppContainer.kt` -> Inyeccion de dependencias manual
- `ui/item/ItemEntryViewModel.kt` -> saveItem() guarda el articulo en la base de datos

Para ver los datos guardados: View > Tool Windows > App Inspection > Database Inspector.
