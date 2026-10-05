# Unidad 6: Persistencia de datos

Repositorio con los entregables de las rutas de aprendizaje asignadas de la Unidad 6 del curso (Ruta 2: Room, Ruta 3: DataStore).

## Estructura del repositorio

```
├── Ruta2_Room/
│   ├── InventoryApp/        (persistencia con Room: crear, leer, actualizar y eliminar datos)
│   └── BusScheduleApp/      (práctica: horarios de buses guardados en Room)
│
└── Ruta3_DataStore/
    └── DessertReleaseApp/   (Preferences DataStore: pares clave-valor)
```

## Ruta 2 — Cómo usar Room para la persistencia de datos

- **InventoryApp**: app de inventario que usa la biblioteca `Room` como capa de abstracción sobre SQLite. Cubre:
  - Definir una entidad y un DAO (Data Access Object) para crear la base de datos.
  - Guardar nuevos ítems en la base de datos.
  - Leer, mostrar en una lista, actualizar y eliminar datos existentes usando `Flow` para que la interfaz se actualice automáticamente cuando cambian los datos.
- **BusScheduleApp**: práctica aplicando los mismos conceptos de Room a una app que muestra horarios de llegada de buses.

## Ruta 3 — Cómo almacenar datos y acceder a ellos mediante claves con DataStore

- **DessertReleaseApp**: app que usa `Preferences DataStore` para guardar una preferencia simple del usuario (en este caso, el tipo de diseño de lista elegido), como una alternativa moderna a `SharedPreferences`, con una API asíncrona basada en corrutinas y `Flow`.

## Estudiante

Mario Huarcaya — Ingeniería de Sistemas

## Curso

Persistencia de datos — Unidad 6