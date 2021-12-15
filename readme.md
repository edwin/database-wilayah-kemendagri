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

Revisions
-------------------
* 22 Oct 2015 - 34 Province, 514 Regencies, 7094 Sub-Districts and 82505 Villages. File name =`tbl_regions.sql`
* 15 Dec 2021 - 34 Province, 514 Regencies, 7160 Sub-Districts and 82546 Villages. File name =`tbl_regions_bps.sql`

Appreciations
--------------------
* 22 Oct 2015 - List of regional codes are kindly provided by Indonesian Ministry of Internal Affairs and Gozali Kumara's KawalDesa (https://github.com/ghk/kawaldesa)
* 15 Dec 2021 - List are taken from BPS data (https://sig.bps.go.id/bridging-kode/index)