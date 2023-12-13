# Postman Usage Guide

## Folders and Variables
1. **Folders and Authorization:**
   - Folders have their own variables and authorization settings, allowing for better organization and control.

## Request Data Handling
2. **Postman Console for Script Debugging:**
   - Utilize the Postman Console for debugging scripts, providing insights into script execution.

3. **Passing Data Between Requests:**
   - Set data as variables to pass them from one request to another.

4. **Setting Variables from Scripts:**
   - Use the `set` method in scripts to dynamically set variables during execution.

## Collection Management
5. **Collection IDs:**
   - Each collection has an ID, conveniently located in the Right Sidebar.

6. **API Key Generation:**
   - Generate an API key from your account settings for authentication purposes.

## Testing and Validation
7. **Properties Assertions:**
   - Leverage various properties assertions like `to.have.property`, `to.match`, `to.be.a`, and `to.be.greaterThan` in tests.

8. **JSON Schema Validation:**
   - Validate JSON responses against a schema for consistency.

9. **Mock Servers:**
   - Create Mock Servers to simulate API endpoints for thorough testing.

10. **Header Testing:**
    - Test headers to ensure proper communication.

## Collection Execution
11. **Collection Runner:**
    - Run entire collections using the Collection Runner, progressing through folders and requests. Check the "persist response" option for result retention.

12. **Scheduled Runs:**
    - Schedule runs to execute at specific intervals on the Postman cloud. Set the initial value as the current value for cloud execution.

## Command Line Interface (CLI)
13. **Postman CLI:**
    - Download the CLI, login using the API key, and execute commands to save data on the Postman cloud.

## Continuous Integration/Continuous Deployment (CI/CD)
14. **CI/CD Pipeline:**
    - CI: New Code ➔ Tests ➔ Package.
    - CD: Package ➔ Test Environment ➔ Tests ➔ Production Environment ➔ Tests.
    - Make sure to keep the API key secure in your CI/CD Vault.

By following these guidelines, you can effectively use Postman for API testing, debugging, and incorporating it into your CI/CD workflows.
