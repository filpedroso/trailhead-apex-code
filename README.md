# trailhead-apex-code

Code from projects in Salesforce's Trailhead by myself

# soqlTemplate: simple SOQL for retrieving an object and printing to debug view.

# addBonusProduct/ orderTrigger: trigger to intercept new purchases and add a free bonus product to it.

# DailyLeadProcessor/ Test: applies schedulable apex to check daily for Leads without source and updates them. Also a test for this class.

# AddPrimaryContact/ Test: implements queueable apex to update accounts's primary contact based on criteria. In this case, its state billing account. Also a test for this class

# AnimalsCallouts/ Test: makes a GET request, deserializes JSON response, creates an object with response. Makes a POST callout, inserting new data. Also a test for this class

# AnimalLocator/ Mock/ Test: makes a GET request by passing and ID argument and returning a string. Also has a test class and its mock result for the request

# MaintenanceRequestHelper/ Trigger/ Test: class is triggered every time a repair case is closed and creates a new routine maintenance case based on the shortest maintenance cycle among the equipments involved in that case. Has also a trigger class and a Test

# WarehouseCalloutService/ Mock/ Test: queueable Apex that calls a service via REST API's GET method to check for updates into external database, fetchs data if there are any, deserialises the JSON data, creates an object from it and upserts into database. Has a mock class for testing and a Test class.

# WarehouseSyncSchedule/ Test: turns WarehouseCalloutService into schedulable Apex by calling it from a schedulable-implemented class. Has also its test.