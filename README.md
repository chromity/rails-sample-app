# Ruby on Rails Tutorial sample application

This is the sample application for [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/) by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/) is available jointly under th MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting Started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails stest
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the [*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
