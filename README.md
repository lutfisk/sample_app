# Ruby on Rails Tutorial sample application
This is the sample application based on
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/) by [Michael Hartl](http://www.michaelhartl.com/).
## License
All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/) is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```
If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```
<br/>

**To activate a created user, an actual email will *not* be sent to you.
Check the console where you ran the server to copy and paste the
activation link in order to get your created account activated.**

<br/>
<br/>

For more information on the Ruby on Rails Tutorial, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
