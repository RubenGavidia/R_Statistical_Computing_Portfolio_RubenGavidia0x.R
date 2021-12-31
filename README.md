# R_Statistical_Computing_Portfolio_RubenGavidia0x.R

Linkedin Assesment badge:

![image](https://user-images.githubusercontent.com/35381213/140604163-4eaa04de-a8a0-42f7-abfc-888b39a25f55.png)

![city driving (mpg) - highway driving (mpg)](https://user-images.githubusercontent.com/35381213/147829777-71833fe1-a749-4911-8965-7961f00e5d32.png)

![3 date-personal savings rate](https://user-images.githubusercontent.com/35381213/147829674-5c3d6601-f37b-482f-b50e-54d5f2f9ff72.png)
![4 date-median duration of unemployment, in weeks,](https://user-images.githubusercontent.com/35381213/147829676-20232be0-77ce-4a16-8c6c-9d2c1d59c236.png)
![5 date-number of unemployed in thousands](https://user-images.githubusercontent.com/35381213/147829677-29ef34f8-6c95-4268-bc77-0878f6ed3a06.png)
![5_1 date-number of unemployed in thousands](https://user-images.githubusercontent.com/35381213/147829678-8f34769a-4e51-4839-8a02-9ffe982aa560.png)
![Fuel Economy dataset count type of cars by class](https://user-images.githubusercontent.com/35381213/147829679-dfa0788b-8f9a-402e-9108-0469f7a2923a.png)
![1 month of data collection - total population, in thousands](https://user-images.githubusercontent.com/35381213/147829681-778e1564-c537-4385-b9c0-bc2441f8931e.jpeg)
![2 date-personal consumption expenditures](https://user-images.githubusercontent.com/35381213/147829685-9586ebac-6bb3-4679-9162-e100de4d3193.jpeg)

Fuel economy data from 1999 to 2008 for 38 popular models of cars.
relationship between cilinders, highway miles per gallon (effiency) and engine displacement, in litres (engine size)

![image](https://user-images.githubusercontent.com/35381213/143671286-958b3595-0cfc-4e9e-9e1f-76ba7ffde240.png)

![image](https://user-images.githubusercontent.com/35381213/143671353-f1fe8301-65c7-4cbf-afa9-fe9a8ff1a146.png)

#type of transmission

![image](https://user-images.githubusercontent.com/35381213/143672999-a696b16c-ddb9-4a8d-95ce-031e2e398a42.png)

#the type of drive train, where f = front-wheel drive, r = rear wheel drive, 4 = 4wd

![image](https://user-images.githubusercontent.com/35381213/143672349-a57f13ba-ff4b-411a-bb05-135d8df92b93.png)

![image](https://user-images.githubusercontent.com/35381213/143672939-a3a9e0de-50c2-45fb-85fe-df5231aef994.png)


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

