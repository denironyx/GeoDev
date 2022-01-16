# Part 1 Getting Started with PostGIS:
## What Is PostGIS?
PostGIS is an open source, freely available, and fairly OGC compliant spatial database extender for the PostgreSQL Database Management System. In a nutshell it adds spatial functions such as distance, area, union, intersection, and specialty geometry and raster data types to the database. PostGIS is very similar in functionality to SQL Server Spatial support, ESRI ArcSDE, Oracle Spatial, and DB2 spatial extender except it has more functionality and generally better performance than all of those (and it won't bankrupt you).

## Installing PostgreSQL with PostGIS Functionality
We will not go into too much detail here since the install wizard (at least the windows one) is pretty good. Below are the basic steps.

-   Download the install for your specific platform from the PostgreSQL Binary Download ( http://www.postgresql.org/download/ ) . As of this writing the latest version is PostgreSQL 14 and we will be assuming PostGIS 3.1+. The minimum support PostgreSQL for PostGIS 3.1 is PostgreSQL 9.5 amd PostGIS 3.2 is 9.6 (for windows we build installers for 9.6-14 for the 3.2 series)

-   Launch exe to install PostgreSQL
-   Once PostgreSQL is installed, launch Application Stack Builder from (Start -> Programs -> PostgreSQL)