# Bower registry


## Create package
```bash
curl http://bower.heroku.com/packages -v -F 'name=jquery' -F 'url=git://github.com/jquery/jquery.git'
```
## Find package
```bash
curl http://bower.heroku.com/packages/jquery
  {"name":"jquery","url":"git://github.com/jquery/jquery.git"}
```
## Unregister package
```bash
curl http://bower.heroku.com/packages/jquery -v -X DELETE
```


## License

Copyright 2012 Twitter, Inc.

Licensed under the MIT License
