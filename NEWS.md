# HPZoneAPI 1.3.0

# HPZoneAPI 1.2.0

* Added automatic sort order to HPZone_request_paginated, since the API doesn't guarantee proper sorting. This allowed a paginated request to return duplicate results, and lack the results that should've existed instead of those duplicates.
* Added a verbose option to the request functions. This will display the used query, including modifications made in the function, and the progress during pagination.

# HPZoneAPI 1.1.0

* Fixed an error where a where-clause containing a number would not be properly formatted.
* Fixed a bug that started as a wrongly swapped argument in the pipe to oldstyle rewrite.

# HPZoneAPI 0.1.0

* Initial CRAN submission.
