# SpreeCasts Episode #6: Shop from scratch to deployment

Setup Rails app:

```
gem install rails
rails new mtgspree -m http://railswizard.org/fb4911f700fd7f21213d.rb -T
```

Add cloud66 manifest file `.cloud66/manifest.yml`
```
production:
  rails:
    server:
      unique_name: spree_web
      extra_packages:
        - imagemagick
```

* [Postgresapp](http://www.postgresapp.com)
* [Cloud66](http://cloud66.com)
* [Digital Ocean](http://digitalocean.com)