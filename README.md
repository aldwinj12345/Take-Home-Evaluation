# Take-Home-Evaluation
ALDWIN S. JUMAO-AS

Personal Note: I admit that API testing is something I have not done for awhile and so I when did this, I made a research and surprise in one of the test cases regarding the malformed JSON response which happens to be the valid credentials.
I was about to send email and ask for a valid credentials.
Also, I uploaded a document of the test plan which is quite similar to the text below

1.Scope and Objectives
	1.1	Test Scope
A test assessment was given and I have to create a series of test cases specifically for one endpoint given. https://mockapi.rapidextras.com/login.

1.2	Test Objectives:
Is part of the test assessment to showcase the ability to design test cases, to execute the created test cases at POSTMAN and provide results.


2.Environment:
	2.1 Environment Setup:
	Windows 11 64 Bit setup
	Ryzen 7 5700G
	48GB RAM
	512GB NVME Storage Device
	
	Installed POSTMAN Application version 11.42.5
	
3.Test Cases:
Design test cases for the POST https://mockapi.rapidextras.com/login endpoint considering various scenarios, including edge cases and invalid inputs.
Ensure coverage for positive and negative test cases.
Some responses may be intentionally delayed or incorrect to test the candidate's ability to handle such scenarios.
Consider edge cases like empty inputs, special characters, and long inputs.

3.1 Test Cases:
	1. Empty Username and Password: Verify that the API response status code is 400 Bad Request with the message "Username and password are required.".
	2. Invalid Login: Verify that the API response status is 401 401 Unauthorized.
	3. Malformed JSON Response: Verify that the API response status code is and will return a malformed JSON response.
	4. Server Error username containing “error”: Verify that the API response status code is 500 Internal Server Error.  
	5. Slow Response: Verify that the API response status code is and will introduce a delay of 2 seconds before returning a response.
	6. Successful Login: Verify that the API response status code is 200 OK and with a JWT token in the response.

4.Test Execution:
4.1 Test Execution Schedule:
Since this is a one-time test assessment and so there will be no timeline target other than the deadline stated on the email.

4.2 Test Prioritization:
In actuality, this will be based on risk, critical, and business impact. 
4.3 Test Result Logging:
In actuality, this will be based on the maintaining of the test case executions result. 


5.Test Reports:
	Summarize the results of the testing process, including the number of tests executed, passed, and failed, as well as any identified defects.
