## `SQLinDS` - SQL queries in Data Step

---

The **SQLinDS** package is based on Mike Rhoads' article [*Use the Full Power of SAS in Your Function-Style Macros*](https://support.sas.com/resources/papers/proceedings12/004-2012.pdf). 

The package allows to write SQL queries in the data step, e.g.
```sas
  data class;
    set %SQL(select * from sashelp.class order by age);
  run;
```
SHA256 digest for the latest version of `SQLinDS`: 42677CEBB0778A6B72DE9C0071B66A345811EE470289E3847D7737F782E709E0

[**Documentation for SQLinDS**](./sqlinds.md "Documentation for SQLinDS")

