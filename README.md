## Usage

```sql
mysql> install plugin server_audit soname "server_audit.so";
mysql> set @@global.server_audit_events="QUERY_DML_ONLY_SELECT";
mysql> set @@global.server_audit_incl_tables="order,sbtest";
mysql> set @@global.server_audit_logging=1;
```


## Update
1. `QUERY_DML_ONLY_SELECT`: only match `select` SQL.
2. `server_audit_incl_tables`: match tables that you want.  


