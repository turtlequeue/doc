Docs
======

Source of the documentation for https://turtlequeue.com/doc/latest/overview.html

Run locally
--------------

How to run locally:

```
nodemon --watch modules --ext adoc,yml --exec "docker run -v `pwd`:/antora --rm -t antora/antora --stacktrace site.yml"
```

Also see https://docs.antora.org/antora/2.0/run-antora/#local-site-preview
