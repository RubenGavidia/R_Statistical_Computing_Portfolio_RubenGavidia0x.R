# R_Statistical_Computing_Portfolio_RubenGavidia0x.R
```
> x = matrix(1:9, ncol=3)
> x
     [,1] [,2] [,3]
[1,]    1    4    7
[2,]    2    5    8
[3,]    3    6    9
> t=t(x)
> t
     [,1] [,2] [,3]
[1,]    1    2    3
[2,]    4    5    6
[3,]    7    8    9
> det(x)
[1] 0
> det(t)
[1] 6.661338e-16
> all.equal(det(x),det(t))
[1] TRUE

> at=cbind(c(9,8,7),c(6,5,4),c(3,2,1))
> at
     [,1] [,2] [,3]
[1,]    9    6    3
[2,]    8    5    2
[3,]    7    4    1
> det(at)
[1] 0
```

---------------------------
Learning R Richard Cotton
---------------------------
rubengavidia#6305

rgavidia13@gmail.com

