# Unit Testing - What It Is, What to Test, and Useful Tools

## What Is Unit Testing?
Unit testing focuses on verifying the smallest parts of an application, such as individual functions, methods, or classes, to ensure they work as intended. It is typically performed by developers and aims to catch bugs at an early stage of development.

## What Is Tested in Unit Testing?
1. **Functionality**:
   - Ensuring individual methods or functions produce the expected output for given inputs.
2. **Edge Cases**:
   - Testing boundary values and unusual inputs to validate robustness.
3. **Error Handling**:
   - Verifying that exceptions are thrown and handled correctly.
4. **Dependencies**:
   - Mocking or stubbing external dependencies to isolate the unit being tested.
5. **Return Values**:
   - Checking the accuracy of returned data and side effects.
6. **State Changes**:
   - Validating changes to internal or external states caused by a unit.

## Tools Useful for Unit Testing
1. **Frameworks for Various Languages**:
   - **JUnit** (Java)
   - **NUnit** (.NET)
   - **PyTest** (Python)
   - **RSpec** (Ruby)
   - **Jest** (JavaScript/TypeScript)
   - **Go Test** (Go)
2. **Mocking and Stubbing Tools**:
   - **Mockito** (Java)
   - **FakeItEasy**, **Moq** (.NET)
   - **unittest.mock** (Python)
3. **Assertion Libraries**:
   - **Chai** (JavaScript)
   - **Hamcrest** (Java)
   - **AssertJ** (Java)
4. **Code Coverage Tools**:
   - **JaCoCo** (Java)
   - **Coverage.py** (Python)
   - **Istanbul** (JavaScript)
5. **Test Automation**:
   - Integrated testing tools in IDEs (e.g., IntelliJ IDEA, Visual Studio).
6. **CI/CD Integration**:
   - **Jenkins**, **GitHub Actions**, **Travis CI** for automating unit tests as part of the build process.