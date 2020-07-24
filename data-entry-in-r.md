---
description: How to enter data in R
---

# Data entry in R

To enter one value to a variable 

`	x=5`

To enter one vector, use  ‘c’ \( small\) function

`	x=c(2,5,6,7,8,9)`

To enter an AP with a difference, d use the function ‘seq’

`	x=seq(5,100,5)`

`seq(first term, last term, d)`

 output  is

 `5,10,15,..., 100`

To enter AP with common difference 1

`	x=c(3:10)`

The output is 

`3,4,5,..., 10`

To enter a matrix using the function ‘matrix’

`A=matrix(c(1,2,3,4,5,6),nrow=2,ncol=3,byrow=T,dimnames=list(c(“R1”,”R2”),c(“C1”,”C2”,”C3”)))`

nrow  -&gt; the number of rows	

ncol -&gt;	 the number of columns

byrow=T  row-wise entry of date, byrow=F or bycol=T for column-wise entry of data

dimnames -&gt;specifies the dimension names of the matrix

The output  is:

       `C1	C2	C3`

`R1	1	2	3`

`R2	4	5	6`

     



