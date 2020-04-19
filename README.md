Verge Flask API (Python)
=====================

 for storing and retrieving
different versions of software.
Verge allows a user to:
- Create a new Application (for example, "Google Chrome")
- Create a new Version (for example, "1.0.0")
- Upload Google-Chrome-1.0.0.exe and associate it with this Version
- View a list of Applications
- View a list of Versions for a given Application


Backend Specification
Using Flask, write a simple API application that has the following routes:
Create Application ​POST /apps
Creates an Application.
Request:
{
​"id" ​: ​"google-chrome" ​,
​"name" ​: ​"Google Chrome"
}
Response (200 OK):
{
​"id" ​: ​"google-chrome" ​,
​"name" ​: ​"Google Chrome"
}

and some more API you can see in the code.

