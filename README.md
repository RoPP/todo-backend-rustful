To deploy this application to Heroku, use this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Or, if you'd prefer to use the command line, try running:

``` sh
git clone https://github.com/RoPP/todo-backend-rustful.git
cd todo-backend-rustful
heroku create --buildpack https://github.com/emk/heroku-buildpack-rust.git
git push heroku master
```

This should make a local copy of this application and deploy it to Heroku.

For further instructions, see
[Deploying Rust applications to Heroku, with example code for Iron][instructions].
You may also be interested in the [source code for the buildpack][buildpack].

[instructions]: http://www.randomhacks.net/2014/09/17/deploying-rust-heroku-iron/
[buildpack]: https://github.com/emk/heroku-buildpack-rust
