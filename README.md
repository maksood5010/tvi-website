
url

https://tvi.dyndns.biz:2442/api/hms/company_info


HMS Custom API Documentation
Overview
This API provides access to various company and HR related information. It's designed for public access with various endpoints to retrieve data about companies, clinicians, departments, specialities, HR jobs, and employees.

Endpoints
1. Get Company Information
URL: /api/hms/company_info
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their details.

2. Get Trusted Brands
URL: /api/hms/trusted_brands_info
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their name and logo URL.

3. Get Company Logo by ID
URL: /api/hms/company_logo/<int:company_id>
Method: GET
Auth Required: No
Parameters: company_id
Response: Logo image for the provided company ID.

4. Get Company's "About" Information
URL: /api/hms/company_about
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their story, growth milestones, mission, vision, and values.

5. Get Company Statistics
URL: /api/hms/company_statistics
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their statistics.

6. Get Company News
URL: /api/hms/company_news
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their news articles.

7. Get Company News Image by ID
URL: /api/hms/company_news_image/<int:news_id>
Method: GET
Auth Required: No
Parameters: news_id
Response: News image for the provided news ID

8. Get Clinicians
URL: /api/hms/clinicians
Method: GET
Auth Required: No
Parameters: None
Response: List of clinicians with their details.

9. Get Departments
URL: /api/hms/departments
Method: GET
Auth Required: No
Parameters: None
Response: List of departments.

10. Get Specialities
URL: /api/hms/specialities
Method: GET
Auth Required: No
Parameters: None
Response: List of specialities.

11. Get HR Jobs
URL: /api/hr/jobs
Method: GET
Auth Required: No
Parameters: None
Response: List of HR jobs.

12. Get Employees with Job Title containing "group c"
URL: /api/hms/employees/group_c
Method: GET
Auth Required: No
Parameters: None
Response: List of employees with job titles containing "group c" and their details.

13. Get Employee Image by ID
URL: /api/hms/image/hr.employee/<int:record_id>
Method: GET
Auth Required: No
Parameters: record_id
Response: Employee image for the provided employee ID.

Responses

The API endpoints return data in JSON format. For image data (like logos and employee photos), the content type is image/jpeg.

Error Handling
In case of errors or data not found, the API will return an error message in JSON format, along with an appropriate HTTP status code. For instance:

)https://tvi.dyndns.biz:2442/api/hms/company_info


HMS Custom API Documentation
Overview
This API provides access to various company and HR related information. It's designed for public access with various endpoints to retrieve data about companies, clinicians, departments, specialities, HR jobs, and employees.

Endpoints
1. Get Company Information
URL: /api/hms/company_info
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their details.

2. Get Trusted Brands
URL: /api/hms/trusted_brands_info
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their name and logo URL.

3. Get Company Logo by ID
URL: /api/hms/company_logo/<int:company_id>
Method: GET
Auth Required: No
Parameters: company_id
Response: Logo image for the provided company ID.

4. Get Company's "About" Information
URL: /api/hms/company_about
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their story, growth milestones, mission, vision, and values.

5. Get Company Statistics
URL: /api/hms/company_statistics
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their statistics.

6. Get Company News
URL: /api/hms/company_news
Method: GET
Auth Required: No
Parameters: None
Response: List of companies with their news articles.

7. Get Company News Image by ID
URL: /api/hms/company_news_image/<int:news_id>
Method: GET
Auth Required: No
Parameters: news_id
Response: News image for the provided news ID

8. Get Clinicians
URL: /api/hms/clinicians
Method: GET
Auth Required: No
Parameters: None
Response: List of clinicians with their details.

9. Get Departments
URL: /api/hms/departments
Method: GET
Auth Required: No
Parameters: None
Response: List of departments.

10. Get Specialities
URL: /api/hms/specialities
Method: GET
Auth Required: No
Parameters: None
Response: List of specialities.

11. Get HR Jobs
URL: /api/hr/jobs
Method: GET
Auth Required: No
Parameters: None
Response: List of HR jobs.

12. Get Employees with Job Title containing "group c"
URL: /api/hms/employees/group_c
Method: GET
Auth Required: No
Parameters: None
Response: List of employees with job titles containing "group c" and their details.

13. Get Employee Image by ID
URL: /api/hms/image/hr.employee/<int:record_id>
Method: GET
Auth Required: No
Parameters: record_id
Response: Employee image for the provided employee ID.

Responses

The API endpoints return data in JSON format. For image data (like logos and employee photos), the content type is image/jpeg.

Error Handling
In case of errors or data not found, the API will return an error message in JSON format, along with an appropriate HTTP status code. For instance:

