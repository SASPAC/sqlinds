## `SQLinDS` - SQL queries in Data Step

---

The **SQLinDS** package is based on Mike Rhoads' article [*Use the Full Power of SAS in Your Function-Style Macros*](https://support.sas.com/resources/papers/proceedings12/004-2012.pdf). 

The package allows to write SQL queries in the data step, e.g.
```sas
  data class;
    set %SQL(select name, age from sashelp.class order by age);
  run;
```
SHA256 digest for the latest version of `SQLinDS`: F*CEAA4C90515F6E8AACBFFD55ABA6544E399EDBE0A7081107B62DCEE6F5430A1D

[**Documentation for SQLinDS**](./sqlinds.md "Documentation for SQLinDS")

To work with a package use the [**SAS Packages Framework**](https://github.com/yabwon/SAS_PACKAGES/blob/main/README.md "SPFinit").

