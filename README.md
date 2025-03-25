# Some Salesforce Apex Tools

## soqlTemplate
Simple SOQL query to retrieve an object and print it to the debug view.

## addBonusProduct / orderTrigger
Trigger that intercepts new purchases and adds a free bonus product.

## DailyLeadProcessor / Test
Schedulable Apex class that checks daily for Leads without a source and updates them. Includes a test class.

## AddPrimaryContact / Test
Queueable Apex that updates an account's primary contact based on criteria (in this case, its state billing account). Includes a test class.

## AnimalsCallouts / Test
Performs a GET request, deserializes the JSON response, and creates an object from it. Also performs a POST callout to insert new data. Includes a test class.

## AnimalLocator / Mock / Test
Makes a GET request with an ID argument and returns a string. Includes a test class and a mock result for the request.

## MaintenanceRequestHelper / Trigger / Test
Triggered whenever a repair case is closed, creating a new routine maintenance case based on the shortest maintenance cycle among the involved equipment. Includes a trigger and a test class.

## WarehouseCalloutService / Mock / Test
Queueable Apex that calls a REST API via a GET request to check for updates in an external database. If updates exist, it fetches, deserializes the JSON data, creates an object, and upserts it into the database. Includes a mock class and a test class.

## WarehouseSyncSchedule / Test
Turns `WarehouseCalloutService` into a schedulable Apex job by calling it from a class implementing the `Schedulable` interface. Includes a test class.

