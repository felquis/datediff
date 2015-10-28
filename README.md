datediff [![Build Status](https://travis-ci.org/dmfilipenko/datediff.svg?branch=master)](https://travis-ci.org/dmfilipenko/datediff)
========

Simple module to calculate difference between two date

Example
=====

```js
var to = new Date('2015-05-03T04:55:44.248Z'),
    from = new Date('2010-10-20T12:19:09.248Z'),
    diff;

diff = datediff(from, to);
console.log( diff )

```
---------

```js
{
	years: 4,
	months: 6,
	days: 13,
	hours: 2,
	minutes: 36,
	seconds: 35,
	weeks: 236
}
```
