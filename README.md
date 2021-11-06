# R_Statistical_Computing_Portfolio_RubenGavidia0x.R

Linkedin Assesment badge:

![image](https://user-images.githubusercontent.com/35381213/140604163-4eaa04de-a8a0-42f7-abfc-888b39a25f55.png)


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

Rcode of stackoverflow test
```
# empty list to start with
X <- list()
# we get a vector
v1 <- c(1, 2, 3, 4, 5)
# add it to the ragged array
X <- c(X, list(v1))
# get another couple of vectors and add them as well
v2 <- c(9, 8, 7, 6)
v3 <- c(2, 4, 6, 8)
X <- c(X, list(v2, v3))

# add some more elements to the first vector in 
# the vector directly
X[[1]] <- c(X[[1]], 4, 3, 2, 1)
```
---------------------------

---------------------------
rubengavidia#6305

rgavidia13@gmail.com

