# AutoDiagnosis

For test runs, the H2 database is used - it is deployed and filled when the application is launched.

You can connect to it while the application is running:

```
driver: H2
Connection type: Remote
Host: localhost
Port: 9092
User: sa
Password: sa
Database: mem
URL: jdbc:h2:tcp://localhost:9092/mem:db
```

There is a known issue with the project running on Java 11. I recommend using version 8.
