# Unit Testing - What It Is, What to Test, and Useful Tools

<div align="center">
<a href=https://github.com/Prime2390/Prime2390/blob/main/Notes/MyNote.md>
    <img src="https://raw.githubusercontent.com/Prime2390/Prime2390/refs/heads/main/Icons/DALL·E%202024-11-11%2022.20.53%20-%20A%20minimalistic%20and%20modern%20icon%20representing%20'Back%20to%20Menu'.%20The%20icon%20should%20feature%20an%20arrow%20pointing%20to%20a%20menu%20or%20list%20symbol%2C%20indicating%20navigation%20.webp" alt="Back to Menu" style="width:100px;height:100px;">
</a>
</div>


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
