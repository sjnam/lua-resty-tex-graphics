mpresty
=======
A version of MathJax, adapted to tex graphics such as metapost, graphviz or tikz
- A web application for TeX graphics that works in all browsers.
- No more setup for readers. It just works.

Installation
------------
- Prerequisites
  
  - [TeX Live](https://www.tug.org/texlive/), An easy way to get up and running with the TeX document production system
  - [OpenResty](http://openresty.org/en/), A full-fledged web platform that integrates the standard Nginx core, LuaJIT
  - [lua-resty-signal](https://github.com/openresty/lua-resty-signal), Lua library for killing or sending signals to UNIX processes
  - [lua-resty-shell](https://github.com/openresty/lua-resty-shell), Lua module for nonblocking system shell command executions
  - [lua-resty-requests](https://github.com/tokers/lua-resty-requests), Yet Another HTTP library for OpenResty - For human beings!
  - [lua-gumbo](https://craigbarnes.gitlab.io/lua-gumbo/), A HTML5 parser and DOM library for Lua

- Webapps

```bash
$ git clone https://github.com/sjnam/mpResty.git ./www
$ cd ~/www
$ mkdir -p html/images logs
$ ./openrestyctl start
```

Examples
--------
- Sample page,  http://localhost:8080/demo/sunflower.html
- Preview page, http://localhost:8080/preview.html

Copyright (C) 2018-2019 Soojin Nam
