#  API-Automation-on-JsonPlaceHolder-using-Katalon-Studio

This repository focuses on API testing using Katalon Studio. It includes test cases for various HTTP methods like GET, POST, and others, with comprehensive validation for response status codes, body, and JSON schema. The aim is to ensure the API meets the expected functionality and structure by automating testing procedures and integrating schema validation for data integrity.

## Video Output:

https://github.com/user-attachments/assets/ecf6c3ff-822f-4b1f-9ba2-e513a6102d8d

## What is Automation?

Automation is the process of using software tools and scripts to perform tasks that would typically be done manually by a human. In the context of software testing, automation involves using tools to execute test cases and compare the actual results with the expected results automatically.

## Technology used
- Katalon Studio

## How to run this project

- Clone this project
- Open in Katalon Studio
- Press Run Button

## Scenario:

1. **Create Post**:
   - Use `POST` API to send a request to create a new post.
   - Verify the response status code is 201.
   - Validate the response body and ensure all required fields are present.

2. **Read Post**:
   - Use `GET` API to fetch a specific post by ID.
   - Verify the response status code is 200.
   - Validate the response body matches the post structure.

3. **Update Post**:
   - Use `PUT` or `PATCH` API to update an existing post.
   - Verify the response status code is 200.
   - Validate the updated fields in the response body.

4. **Delete Post**:
   - Use `DELETE` API to remove a post by ID.
   - Verify the response status code is 200 or 204.
   - Validate that the post is successfully deleted.

## Screenshot (Report):

![image](https://github.com/user-attachments/assets/1784c188-f91c-447f-af44-d7f133f560e6)

