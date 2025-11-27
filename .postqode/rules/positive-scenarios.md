## Brief overview
This rule is to ensure that when generating test scenarios, the focus is on positive cases, also known as "happy paths".

## Scenario Generation Guidelines
- **Prioritize Positive Scenarios:** When creating tests, the primary goal is to validate that the system works as expected under normal conditions. This means generating test cases that use valid and expected inputs to produce successful outcomes.
- **Avoid Negative Scenarios:** Unless explicitly requested, do not generate negative test scenarios (e.g., tests with invalid data, error conditions, or edge cases).
- **Example:** For an API endpoint that creates a new user, a positive scenario would be to provide all required fields with valid data and expect a successful creation response (e.g., HTTP 201). A negative scenario, which should be avoided, would be to send a request with missing data to check for an error response.
