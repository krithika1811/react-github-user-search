In this project, we will use an input's value to search for users in GitHub using their username or email.

How to build it

You will first store the value typed into the input in a state value called query. After that, you will perform an HTTP request to a GitHub API endpoint to then fetch the users' profile which once again uses the browser fetch API. The request URL will use the input value.

Once the results are fetched, we'll see how to display all the relevant info such as their name, avatar, and a link to go to their profile.

