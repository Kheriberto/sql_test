This project uses a test DB with random data simulating a log that records tracks.
The DB is composed of two tables: tracks1 and tracks2. Both tables have the same schema.

SCHEMA:

| Column      | Type         | Null | Key | Default              | Extra             |
|-------------|--------------|------|-----|----------------------|-------------------|
| id          | int          | NO   | PRI | NULL                 | auto_increment    |
| UUID        | varchar(36)  | NO   |     | NULL                 |                   |
| source      | varchar(255) | NO   |     | NULL                 |                   |
| datetime    | datetime(6)  | YES  |     | NULL                 |                   |
| inserted_at | timestamp(6) | YES  |     | CURRENT_TIMESTAMP(6) | DEFAULT_GENERATED |
