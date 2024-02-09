# calgary311

Data Dictionary

311 Service Requests
| **Column Name**          |  **Data Type**       | **Description**                                                    | 
|--------------------------|----------------------|--------------------------------------------------------------------|
| service_request_id       | Text                 | The unique identifier for an individual request.                   |
| requested_date           | Floating Timestamp   | The date the request was submitted.                                |
| updated_date             | Floating Timestamp   | The most recent date the request was updated.                      |
| closed_date              | Floating Timestamp   | The date the request was closed.                                   |
| status_description       | Text                 | The current status of the request (e.g. open, closed).             |
| source                   | Text                 | The channel used to submit the request.                            |
| agency_responsible       | Text                 | The type of service requested.                                     |
| address                  | Text                 | The location of the service request (if applicable).               |
| comm_code                | Text                 | The community code associated with the service request location.   |
| comm_name                | Text                 | The community name associated with the service request location.   |
| location_type            | Text                 | The type of location information provided. (None, Community Centrepoint, or Service Request Location |
| longitude                | Text                 | The longitude of the service request.                              |
| latitude                 | Text                 | The latitude of the service request.                               |
| point                    | Text                 | The spatial coordinates based on latitude and longitude.           |
