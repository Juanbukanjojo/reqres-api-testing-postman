**Reqres API Testing Project**
📌 Overview

This project contains API test scenarios built using Postman to validate the functionality of the Reqres mock API service.

**🌐 Base URL**

https://reqres.in/api

**🔐 Authentication**

Almost all endpoints require an API Key for authorization.
To obtain the API Key, users must first access the Reqres application dashboard and request API access. Once approved, the API Key can be used in request headers as:

x-api-key: <your_api_key>

Requests without a valid API Key may return an unauthorized response depending on the endpoint configuration.

**🧪 Test Coverage**
- Authentication (Register & Login)
- Users Endpoint Testing
- Positive Scenarios
- Negative Scenarios

Response Validation (Status Code, Headers, Response Time, Schema)

**⚠️ Limitation**
Reqres is a mock API and does not persist created or updated data.
All POST, PUT, and DELETE responses are simulated.

**🛠 Tools Used**
- Postman
- JavaScript (Postman Test Script)
- GitHub
