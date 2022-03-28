# Five Aces 

Five Aces is a clone of Facebook. It lets users post, like and comment. 

## Demo

Heroku URL: https://morning-brook-76857.herokuapp.com/

## Techonologies Used

Ruby <br> 
Ruby on Rails<br> 
Bootstrap<br> 
CSS/HTML<br> 
PSQL

Testing:
Rspec

Workflow:
Github Actions (CI/CD)


## Initial setup

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```

## Troubleshooting

If you don't have Node.js installed yet, you might run into this error when running rspec:
```
ExecJS::RuntimeUnavailable:
  Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes.
 ```
That is because Rails will use a Javascript runtime (such as Node) under the hood. The easiest way is to install Node by running `brew install node` - 
and then run `bundle exec rspec` again

