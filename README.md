## Challenge Developer Junior ##
1. You're building a high-throughput API for a cryptocurrency trading
platform. For this platform, time is extremely important because
microseconds count when processing high-volume trade orders. For
communicating with the API, you want to choose the verb that is fastest
for read-only operations.
What verb should you choose for retrieving trade orders with the API
server?
SELECT ONLY ONE:
- GET
- UPDATE
- DELETE
- POST

## ANSWER : GET##

2. You work for a Customer Relationship Management (CRM) company. The
company's clients gain CRM access through a RESTful API. The CRM allows
clients to add contact information for customers, prospects, and related persons
(e.g., virtual assistants or marketing directors). You want to choose an
appropriate API request path so clients can easily retrieve information for a
single contact while also being flexible for future software changes.

- /customers/{customer_id}
- /contacts/{contact_id}
- /contacts/{contact_type}/all
- /customers/all

## ANSWER : /contacts/{contact_id} because it can refer to different types of contacts##

3. You work for a large social media network, and you've been tasked witherror
handling for the API. You're trying to decide on an appropriate errorcode for
authentication failures based on non-existent users and incorrect passwords. You
want to balance security against brute force attacks with providing descriptive
and true error codes.

Which HTTP error code(s) should you use to keep the system secure and still report
that an error occurred?
SELECT ONLY ONE_
- 404 if the user doesn't exist, and 403 if the password is wrong.
- 403 if the user doesn't exist, and 401 if the password is wrong.
- 500 if the user doesn't exist or if the password is wrong.
- 401 if the user doesn't exist or if the password is wrong

## ANSWER : 403 if the user doesn't exist, and 401 if the password is wrong. Because 403 means Forbidden and 401 Unauthorized.##