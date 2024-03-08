# Urban Grocers

**Project Overview:**

Urban Grocers, a delivery service, provides a wide selection of grocery items obtained from different warehouses. The back-end API of Urban Grocers functions as a utility for accessing details pertaining to warehouses, grocery products, kits, and orders.

The main goal of the project was to conduct thorough testing of various endpoints. Testing procedures were executed in Postman, and automated tests were developed using the Jest JavaScript testing framework. The emphasis was specifically on GET, POST, PUT, and DELETE requests. 

**Your Role and Contributions:**

In my role as a QA Engineer, my primary responsibilities included:
- Conducting API tests in Postman to verify data integrity and ensure accurate data validation in the received responses.
- Creating automated API tests using the Jest JavaScript testing framework.

**Project Deliverables:**

The testing checklist utilized for tests done with Postman can be found [here](https://docs.google.com/spreadsheets/d/14ELuoP0BIhmx33rg7pzcS5iSrA-fQEJ4/edit?usp=sharing&ouid=117504763605059948253&rtpof=true&sd=true);
The GitHub repository consisting of the Jest API tests can be found [here](https://github.com/kristiingco/hm07-qa-us). 

**Testing Approach:**

Testing predominantly relied on API testing methodologies. Specifically, the focus was placed on scrutinizing the structure of responses and ensuring alignment with the expected results outlined in the API documentation.

**List of Tests Conducted:**

The following endpoints were tested in Postman:
- Adding products to the cart
- Getting products from an order
- Deleting an order
- Adding items to a kit
- Checking availability and cost of Fast Delivery service

Meanwhile, the following endpoints were tested with Jest:
- Getting a kit by name
- Getting a list of deliveries
- Getting a list of warehouses
- Adding items to a kit
- Checking the availability of goods in warehouse
- Checking the quantity of goods in warehouse
- Creating a user account
- Updating the price of grocery items
- Updating a kit
- Deleting a kit

**Test Results:**

For the tests executed with Postman, 360 test cases were created to span over the endpoints that were covered. Of the 360, 90.28% passed (325), while 9.72% failed (35). 

For the tests executed with Jest, 68 tests were created. Out of the 68, 92.6% passed (63) while 7.4% failed (5).
