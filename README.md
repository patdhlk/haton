# haton
influxdb line data gen

[![Build Status](https://travis-ci.org/patdhlk/haton.svg?branch=master)](https://travis-ci.org/patdhlk/haton)

### input

```
{
	"measurement":"setpoint",
	"host":"mfc_1",
	"region":"europe",
	"value":11.5,
	"timestamp":7290431990000000000
}
``` 

### output

```
setpoint,host=mfc_1,region=europe value=11.5 7290431990000000000
```


