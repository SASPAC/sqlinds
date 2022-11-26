## `SQLinDS` - SQL queries in Data Step

---

The **SQLinDS** package is based on Mike Rhoads' article [*Use the Full Power of SAS in Your Function-Style Macros*](https://support.sas.com/resources/papers/proceedings12/004-2012.pdf). 

The package allows to write SQL queries in the data step, e.g.
```sas
  data class;
    set %SQL(select * from sashelp.class order by age);
  run;
```
SHA256 digest for the latest version of `SQLinDS`: D5A66E60602270E5FB1E592FA3E0C2F2C640BC077FE799A2223CB9BA275F6F47

[**Documentation for SQLinDS**](./sqlinds.md "Documentation for SQLinDS")

