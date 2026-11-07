MS1 MockMvc Lab - Spring Boot project

REQUIREMENTS
- JDK 17 or later
- Maven 3.6.3 or later
- STS4 or Eclipse (optional)

OPEN IN STS4 / ECLIPSE
1. Extract this ZIP file.
2. Open STS4/Eclipse.
3. Select File > Import > Maven > Existing Maven Projects.
4. Browse to the extracted MS1-MockMvc-Lab folder.
5. Select the project and click Finish.
6. Wait for Maven dependencies to download.

RUN THE APPLICATION
1. Open MS1Application.java.
2. Right-click > Run As > Spring Boot App.
3. The application runs on port 8081.
4. Open this URL in a browser:
   http://localhost:8081/ms1/add?a=5&b=10

Expected response:
MS 1.1 - Additon = 15

RUN THE JUNIT TEST
1. Right-click MS1ControllerTest.java.
2. Select Run As > JUnit Test.
3. Expected: 1 test, 0 failures, 0 errors.

IMPORTANT
- The JUnit test uses @WebMvcTest and MockMvc. It does not start an embedded
  server or require the main application to be running.
- The spelling "Additon" is intentionally retained to match the question's
  exact expected response.
- This example has no separate service dependency, so no mocked dependency
  is needed in the test class.
