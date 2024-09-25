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

4. You're writing documentation for requesting information about a given user in
your system. Your system uses UUIDS (universally unique identifiers) as user
identifiers. In your documentation, you want to show an example.
True or false: You should put a fake UUID into the example code (instead of just the
text "UUID") as a placeholder.
SELECT ONLY ONE
- TRUE
- FALSE

## ANSWER : TRUE because it is safest in that way##

5. You're building code to handle errors issued from a remote API server. The
response may or may not have an error.
How much work should your method, handleErrors(response),
handle?
SELECT ONLY ONE
- Check for the presence of an error. If it exists, then set a class property to the error.
- Check for the presence of an error. If it exists, throw an exception with the error.
- Check for the presence of an error. If it exists, set a class property to the error, then throw an exception.
## ANSWER : Check for the presence of an error. If it exists, throw an exception with the error, because a handler must be clear with the error but easy at the same time.##

6. You have two classes: a database driver and an email driver. Both classes need
to set errors so that your front-end interface displays any errors that transpire on
your platform.
Which way should you implement this error handling?
SELECT ONLY ONE
- Write the error handling the same way in both classes, but keep it to one line of code.
- Make a trait to handle errors so it'll collect errors in any class that uses it.
- Make a driver-based error provider to handle errors in all classes that can issue errors.

## ANSWER : Make a trait to handle errors so it'll collect errors in any class that uses it, because it's more practical to have a handler for multiple error collections of different classes. ##