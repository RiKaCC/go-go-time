# go-go-time

## Using go-go-time
you can use go-go-time to get before time in a easy way.

`TimeBefore(hour,minute,second)`
you can use TimeBefore() to get the time you want.

```golang
now := time.Now().Format("2006-01-02 15:04:05") //print 2018-02-12 11:19:47

hour_before := TimeBefore(1,0,0) //print 2018-02-12 10:19:47
min_before := TimeBefore(0,1,0)  //print 2018-02-12 11:18:47
sec_before := TimeBefore(0,0,1)  //print 2018-02-12 11:19:46

all := TimeBefore(1,1,10) //print 2018-02-12 10:18:37
```
