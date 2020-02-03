# liquibase-snowflake-db-build

Parent pom for building [liquibase](https://www.liquibase.org/index.html) [snowflake](https://www.snowflake.com/) projects.

# Overview

This project configures the plugins used to apply liquibase changesets to snowflake databases.  It uses the [db-props](https://github.com/bruce-szalwinski/liquibase-snowflake-db-props) project to allow for reuse of database configurations across multiple projects.  It also uses a bit of maven magic to allow developers to specify their own version of database properties for local development.

# Install

```bash
mvn install
```
