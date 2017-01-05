# Apache Hive Cheat Sheet

Here are the commands I frequently use while working with Hive. Presented here for easy reference.

## Generate Create Table Statement

Sometime there is a need to migrate or recreate some table in a different database. This command comes in handy to generate the DDL statements

```sql
SHOW CREATE TABLE myTable;
```

[Document reference](https://cwiki.apache.org/confluence/display/Hive/LanguageManual+DDL#LanguageManualDDL-ShowCreateTable)