Change Log
=========================================================================

All notable changes to this project will be documented in this file.
This project adheres to `Semantic Versioning <http://semver.org/>`_.
Please note that the changes before version 1.10.0 have not been documented.

Unreleased
----------
Changed

- Fixed Issue #174

- Fixed issue with profiler not going into code

- Implemented a Sunburst visualization of the Grouped Profiler

- Improved test coverage

- Improved python-doc


v2.0.0
----------
Changed

- Added a configuration option to prefix a table in the database

- Optimize queries, such that viewing data is faster

- Updated database scheme

- Implemented functionality to customize time window of graphs

- Implemented a profiler for Request profiling

- Implemented a profiler for Endpoint profiling

- Refactored current code, which improves readability

- Refactoring of Test-Monitoring page

- Identify testRun by Travis build number


v1.13.0
----------
Changed

- Added boxplot of CPU loads

- Updated naming scheme of all graphs

- Implemented two configuration options: the local timezone and the option to automatically monitor new endpoints

- Updated the Test-Monitoring initialization

- Updated Database support for MySQL

v1.12.0
-------
Changed

- Removed two graphs: hits per hour and execution time per hour

- New template design

- Refactored backhand of the code

- Updated Bootstrap 3.0 to 4.0

- Setup of Code coverage


v1.11.0
-------
Changed

- Added new graph: Version usage

- Added column (Hits in past 7 days) in Measurements Overview

- Fixed bug with configuration

- Changed rows and column in outlier-table

- Added TODO List

- Updated functionality to retrieve the stacktrace of an Outlier

- Fixed bug with white colors from the config option


v1.10.0
----------
Changed

- Added security for automatic endpoint-data retrieval.

- Added test for export_data-endpoints

- Added MIT License.

- Added documentation
