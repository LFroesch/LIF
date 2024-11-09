# SQLC
go install github.com/sqlc-dev/sqlc/cmd/sqlc@latest
sqlc version
sqlc generate
touch sqlc.yaml
# sqlc.yaml bp
version: "2"
sql:
  - schema: "sql/schema"
    queries: "sql/queries"
    engine: "postgresql"
    gen:
      go:
        out: "internal/database"