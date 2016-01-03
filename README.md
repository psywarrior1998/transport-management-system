[![License: AGPL-3](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0-standalone.html)
[![Build Status](https://travis-ci.org/odoo-jarsa/transport-management-system.svg?branch=9.0)](https://travis-ci.org/odoo-jarsa/transport-management-system)
[![Coverage Status](https://coveralls.io/repos/odoo-jarsa/transport-management-system/badge.svg?branch=9.0&service=github)](https://coveralls.io/github/odoo-jarsa/transport-management-system?branch=9.0)

Freight Management System
==========================

This application allows you to manage Truckload Freights and Less-than-truckload freight. It also can help Companies such as owner-operators, carriers, brokers and shippers.

It handles full Travel workflow:

Transport Requirement => Waybill => Freight => Delivery

Managing:
- Driver Cash advance (Payment & Conciliation)
- Fuel Voucher Management
- Checking Travel Expenses
- Freight Invoicing (Trucks of the company or third parties)

It also can manage:
- Trucks Red Tapes
- Truck Odometers
- Events during travel (Example: Arrival delay, Missing Cargo, etc)
- Kits
- Places (Linked with Google Maps)
- Routes (Visible in Google Maps)
- Easy integration with GPS System

This project is still work in progress, tms module will be split in several modules to make it easier to manage.

[//]: # (addons)
The list of proposed modules is:
--------------------------------
addon | version | summary
--- | --- | ---
[tms](tms/) | 0.1 (unported) | this module is the base module, it contains fleet, travel, waybills and travel expenses.
[tms_maintenance](tms_maintenance/) | 0.1 (unported) | this module make maintainance program to vehicles.
[tms_second_driver](tms_second_driver/) | 0.1 (unported) | this module allow to select a second driver in the travels and control travel expenses with it.
[tms_operations](tms_operations/) | 0.1 (unported) | this module allow to create operations to group all freight related objects in one place.
[tms_gps_base](tms_gps_base/) | 0.1 (unported) | this module contains a base framework ease the development of gps connectors.
[tms_operating_units](tms_operating_units/) | 0.1 (unported) | this module allow to use operating units with TMS read more at [OCA Operating Units](https://github.com/oca/operating-unit)
[tms_toll_stations](tms_toll_stations/) | 0.1 (unported) | this module improve add tolls to route and automate travel expenses.
[tms_driver_loan](tms_driver_loan/) | 0.1 (unported) | this module allow to make loans to drivers and then charge it in travel expenses.
[tms_analysis](tms_analysis/) | 0.1 (unported) | this module add BI functionalities to TMS.
[tms_driver_license](tms_driver_license/) | 0.1 (unported) | this module manage expiry of Driver license.
[tms_vehicle_insurance](tms_vehicle_insurance/) | 0.1 (unported) | this module adds insurance expiry to Vehicle.
[tms_internal_fuel](tms_internal_fuel/) | 0.1 (unported) | this module allow to use internal fuel, connected with warehouse.
[tms_agreement](tms_agreement/) | 0.1 (unported) | this module automate the flow based on a contract.

[//]: # (end addons)

Credits
-------

This project is made from forks of other projects:
- Israel Cruz (Argilsoft) - https://code.launchpad.net/~argilsoft
- German Ponce - https://code.launchpad.net/~german-ponce

Maintainer
----------

[![Jarsa Sistemas, S.A. de C.V.](http://www.jarsa.com.mx/logo.png)](http://www.jarsa.com.mx)

This modules are maintained by Jarsa Sistemas, S.A. de C.V.