icu4c on Heroku
=================

Installation
------------

  * Create your heroku application
  * Supply the `BUILDPACK_URL` env variable 

```
heroku config:add BUILDPACK_URL="https://github.com/atmos/heroku-buildpack-icu4c.git"
```

Modify your configuration file to suit your needs.  Enjoi.
