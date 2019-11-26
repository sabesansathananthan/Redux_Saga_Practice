# Redux_Saga_Practice

# Important! What to do if REM REST API is down
If you're having issues with REM REST API or if the server is down for some reason, replace your axios default code with this:

//axios.defaults.withCredentials = true;
axios.defaults.baseURL = 'https://cors-anywhere.herokuapp.com/https://rem.dbwebb.se/api';

You'll be able to carry on working as normal with no further modifications required to your code.

- Please note the commented out 'withCredentials' line.
