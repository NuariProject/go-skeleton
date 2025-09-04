## `migration` Folder

This folder contains database migration scripts for managing schema changes.

Each migration consists of two files:
- `.up.sql`: Applies schema changes (forward migration)
- `.down.sql`: Reverts schema changes (rollback)

### Example Structure

```
migration/
├── 001_create_users_table.up.sql
├── 001_create_users_table.down.sql
├── 002_create_orders_table.up.sql
├── 002_create_orders_table.down.sql
```
