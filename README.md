Jack
====

A script to download and control jackrabbit with support for project-specific extensions

Installation
------------

```
$ git clone git://github.com/rndstr/jackrabbit-jack.git /path/to/somewhere/
$ cd $YOUR_PROJECT
$ ln -fs /path/to/somewhere/jack jack
$ ./jack start
```

Usage
-----

See output of `./jack usage`


Settings
--------

Copy `jack.conf.sample` to `jack.conf` and adjust it.


Project Extensions
------------------

To support project-specific actions you can create custom actions or extend
existing actions. Take a look at `jack.sample` for more info.

Don't forget to add it to the `extensions` list in `jack.conf`
