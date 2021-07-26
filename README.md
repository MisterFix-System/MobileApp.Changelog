# MobileApp.Changelog
** All of updated or new feature also update/create new API Endpoint to the server **


## v.1.0.3
* Add forgot password feature
* Update banner image (login, register, AC register)
* Update google maps API Key


## v.1.0.2
* Add action to pick location on Google Maps when creating new customer AC data
* Update form when Technician update Customer AC info - adding AC Brand and AC PK dropdown option form (only when customer create a new order from main web)
* Add action to Order Detail - Make Technician have access to update Qr Code data when order created from main web

-----------------------------------------------------------------------------------------------

## v.1.0.0-rc.11
* Add DONE action button
* Make order detail is enable when service date > or = current date
* Add new page to update new customer AC data when scanning the Qr Code
* Add Cancel Request button

## v.1.0.0-rc.9
BUGFIX - https://github.com/MisterFix-System/MobileApp.Changelog/issues/3
* Fix logic to show available service order
* Fix logic to show order information after the Technician scanning the Qr Code

## v.1.0.0-rc.7
NEW FEATURE
* Show Technician income balance
* Add feature to submit technician notes after service
* Show AC Service history

UPDATE FEATURE
* Change AC Register form - use dropdown data to populate AC data (brand, type, freon)
* Show Product price discount in order detail


## v.1.0.0-rc.6
NEW FEATURE
* Fetch New Order and Accepted Order from database to mobile app
* Order detail information
* Update Order feature
* Search Products
* Accept Order feature
* Order Notification
* Scan Qr Code to show AC information
* User Profile feature (read and update worker profile)

UPDATE FEATURE
* Fix NaN error
* Update dashboard design
* Fetch Worker name and profile pict to the dashboard

## v.1.0.0-rc.4
UPDATE FEATURE
* Register Customer AC - Make the Worker to be able search and use existing data (customer/building/room info) when adding new AC

NEW FEATURE
* Register Company AC - The Worker only can search existing Company data and add new AC information. Company data must be added by Admin


## v.1.0.0-rc.3
NEW FEATURE
* Worker Dashboard & Bottom Navigation Design Layout
* Register new Customer AC
* Qr Code Scanner

UPDATE UI
* Update Login & Register Design

## Initial
Available Features:
* Login
* Register
