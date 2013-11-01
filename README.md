# Bower registry


## Create package
```bash
curl <PATH_TO_REGISTRY> -v -F 'name=jquery' -F 'url=git://github.com/jquery/jquery.git'
```
## Find package
```bash
curl http://bower.heroku.com/packages/jquery
  {"name":"jquery","url":"git://github.com/jquery/jquery.git"}
```
## Unregister package
```bash
curl -X DELETE <PATH_TO_REGISTRY>/packages/jquery
```

## License

Copyright 2012 Twitter, Inc.

Licensed under the MIT License
