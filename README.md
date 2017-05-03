# hello koa

[![Build Status](https://travis-ci.org/joehecn/hellokoa.svg?branch=master)](https://travis-ci.org/joehecn/hellokoa)
[![codecov](https://codecov.io/gh/joehecn/hellokoa/branch/master/graph/badge.svg)](https://codecov.io/gh/joehecn/hellokoa)
[![Code Climate](https://codeclimate.com/github/joehecn/hellokoa/badges/gpa.svg)](https://codeclimate.com/github/joehecn/hellokoa)
[![Dependency Status](https://gemnasium.com/badges/github.com/joehecn/hellokoa.svg)](https://gemnasium.com/github.com/joehecn/hellokoa)

## develop

``` bash
make lt // lint
make tt // test
npm start // 启动开发服务器, nodemon watching 文件变化
```

## build

``` bash
npm run pub // build
npm run dist // 启动本地服务
```

## docker

``` bash
docker build -t joe/hellokoa:1.0.0 .
docker run -d -p 7001:7001 --name hellokoa joe/hellokoa:1.0.0
```
