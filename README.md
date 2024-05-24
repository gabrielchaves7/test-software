# Introduction
We decided to use a small challenge provided by a financial company to do our TP. The challenge was developed by Origin, which is a financial company. They provided a figma [link](https://www.figma.com/design/eysSLDJFaEgGRWqHTFVehu/Take-Home-Assignment-v3?node-id=0-1&t=SZQYc41b7BNITDkA-0.) to be used as reference. The system is basically a calculator to show a financial score based on the user income and expenses. 

# Tests
We splited the system into two folders, ui and backend. Each folder have it's own tests.
## UI tests
The UI tests can be found at the paths bellow:
- ui/packages/domain/test. Here you will find the domain tests for the UI.
- ui/integration_test. Here you will find the integration tests for the UI.
- uit/test. Here you will find the interface tests for the UI.
## Backend tests
- backend/test_e2e. Here you will find the integration tests for the backend.
- backend/*/service/*. Here you will find a test for each service class, which is responsible for the business logic.

## CI
Our CI will run both (ui and backend) unit tests and generate a coverage report, which you can see at the CI itself.
