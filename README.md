# postgres-service-dump

- Creates a postgres service container and mounts a volume between host and container
- Executes `pg_dump` on the container and outputs the file into the mounted volume
- Host can access the file on the container directly from the `github.workspace` directory.
