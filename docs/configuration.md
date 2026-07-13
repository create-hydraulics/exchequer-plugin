# System Configuration

The `config.yml` file dictates base interest coefficients, tax loop intervals, and database connections.

### Database Settings
```yaml
storage:
  type: "SQLITE" # Options: SQLITE, MYSQL
  host: "127.0.0.1"
  port: 3306
  database: "exchequer"
  username: "root"
  password: ""
