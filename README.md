## `SQLinDS` - SQL queries in Data Step

---

The **SQLinDS** package is based on Mike Rhoads' article [*Use the Full Power of SAS in Your Function-Style Macros*](https://support.sas.com/resources/papers/proceedings12/004-2012.pdf). 

The package allows to write SQL queries in the data step, e.g.
```sas
  data class;
    set %SQL(select * from sashelp.class order by age);
  run;
```
SHA256 digest for the latest version of `SQLinDS`: F*42DC179E1D2B946AD519C4EC04A068061B312E021C3F4BC4826D2775E116E1B9

[**Documentation for SQLinDS**](./sqlinds.md "Documentation for SQLinDS")

To work with a package use the [**SAS Packages Framework**](https://github.com/yabwon/SAS_PACKAGES/blob/main/README.md "SPFinit").

