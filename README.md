# padrino-sidekiq-example

This is an example of a bare-bones padrino app trying to mount Sidekiq version 3.4.2 at `/sidekiq`. This works with Sidekiq version 3.4.1 but produces a RuntimeError with 3.4.2. 

To start:
```
$ bundle install
$ padrino s
```

Navigate to `localhost:3000/sidekiq` to view full dump.
