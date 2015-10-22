Indonesian Ministry of Internal Affairs Region Code and Region Name Database
===================

Tools
-------------------
* DB - MySql

Query
--------------------
``` sql
SELECT
	region_code,
	region_name
FROM
	tbl_regions
WHERE
	parent_code = ?
```

Appreciations
--------------------
List of regional codes are kindly provided by Indonesian Ministry of Internal Affairs and Gozali Kumara's KawalDesa (https://github.com/ghk/kawaldesa)