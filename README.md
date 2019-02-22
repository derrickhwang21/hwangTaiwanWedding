# Taiwanese Wedding

## Project Structure

### React + Redux Project Structure ###

All source code for the React + React app is located in `/src` folders. Inside the src folder there is a folder per feature (App, HomePage, LoginPage, RegisterPage) and a bunch of folders for non-feature code that can be shared across different parts of the app (_actions, _components, _constants, _helpers, _reducers, _services).

Non-featured folders with an underscore "_" are prefixed to group them together and make it easy to distinguish between features and non-features.

The index.js files in each folder are barrel files that group all the exported modules together so they can be imported using the folder path instead of the full module path and to enable importin multiple modules in a single import

### ASP.NET Core API ###

API is organized into the following folders:

* Controllers -  define endpoints / routes for the web api, controlleres are the entry poin into the web api from client application via http requets

* Services - contain business logic, validation and database access code

* Entities - represent the application data that is stored in the database

* Dtos - data transfer objects used by controllers to expose a limited set of entity data via the api, and for model binding data from HTTP requests to controller action methods.

* Helpers - anything that doesn't fit into the above folders.





## Credit/Sources

React + Redux - User Registration and Login Tutorial & Example

For documentation and further details go to http://jasonwatmore.com/post/2017/09/16/react-redux-user-registration-and-login-tutorial-example