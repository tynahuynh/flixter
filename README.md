# [Flixter](https://flixter-tyna-huynh.herokuapp.com/)
A two-sided, video-streaming marketplace platform that features credit card payment capabilities, user role management, complex user interfaces, and advanced database relationships.

![alt tag](https://user-images.githubusercontent.com/14388583/28288867-73a0e6de-6af5-11e7-8254-60bc56a0982d.png)

## Running Locally
Make sure you have Ruby installed.
Clone or download the repository.

Run the following code to install the application's dependencies:
```
bundle install
```
Create initial database:
```
rake db:create
```
Run the migration:
```
rake db:migrate
```

The application should now be running on your localhost.

## Deployment
To deploy on Heroku. Adjust the APP_NAME to your project name.
```
heroku create APP_NAME
```
Now push it up to Heroku with the following command:
```
git push heroku master
```
It should take a few moments to run, and when it finishes it should say "Launching..." along with a URL.

To easily see you heroku url you can type:
```
heroku apps:info
```
The application can now be found at the URL returned.
