# Database

The application uses **Room Database** for local and persistent storage.

## Components

### `RoomDb.kt`

`RoomDb.kt` defines the Room database and provides access to the DAO.

The database is named `NoteApp` and uses the `Notes` entity.

### `MainDAO.kt`

`MainDAO.kt` contains the database operations used by the application.

The DAO supports:

- Insert
- Read
- Update
- Delete
- Pin / unpin

Notes are retrieved from the database and displayed in the main activity.

## Data Flow

```text
User Action
    ↓
MainActivity / NotesTakeActivity
    ↓
MainDAO
    ↓
Room Database
    ↓
Notes Data
    ↓
RecyclerView
```

Using Room allowed the notes to remain available after the application was closed or restarted.
