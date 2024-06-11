## Pattern 1

| thread_id (PK/GSI-SK) | post_id (SK) | category(GSI-PK) |
| --------------------- | ------------ | ---------------- |
| #{thread_id}          |              | Thread           |
| #{thread_id}          | #{post_id}   | Post             |

## Pattern 2

| category (PK) | id (SK)                 |
| ------------- | ----------------------- |
| Thread        | #{thread_id}            |
| Post          | #{thread_id}/#{post_id} |
