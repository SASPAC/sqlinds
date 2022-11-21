## `SQLinDS` - SQL queries in Data Step

---

The **SQLinDS** package is based on Mike Rhoads' article [*Use the Full Power of SAS in Your Function-Style Macros*](https://support.sas.com/resources/papers/proceedings12/004-2012.pdf). 

The package allows to write SQL queries in the data step, e.g.
```sas
  data class;
    set %SQL(select * from sashelp.class order by age);
  run;
```
SHA256 digest for the latest version of `SQLinDS`: 085F0B8BD4A59343E2913FF9635EA6E551ADD54E9678C35F5096D4A0A895B9C5

[**Documentation for SQLinDS**](./sqlinds.md "Documentation for SQLinDS")

