### Primer Programa en R
3 * 2
100:130
seq(100,130.1)
1000:1020
seq(1,100,5)
5 -
4
die <- 1:6
die * 2
die - 1
ls()
my-number <- 999
my_number <- 999
ls()
die + 1:2
die 1:2
die + 1:4
die + 1:3
a <- c(1,2,3)
del(a)
rm(a)
dir * a
a <- c(1,2,3)
dir * a
die * a
die %o% die
b <- die %o% die
t(b)
det(b)
x <- c(10.4, 5.6, 3.1, 6.4, 21.7)
y <- c(x,0,x)
length(x)
length(y)
b <- 2*x + y +1
y <- c(x,x)
b <- 2*x + y +1
b
length(b)
log (x)
exp(y)
sqrt(x)
sin(x)
cos(x)
range(y)
mean(x)
var(x)
rep(x1, times=5)
rep(x, times=5)
rep(4, times=5)
rep(x,each=5)
t
s
s <- c(1:3,NA)
s
is.na(s)
s <- c(1:3,NA, 0/0)
s
is.na(s)
is.nan(s)
labs = c("X", "Y")
labs
labs <- paste(labs, 1:10, sep="")
labs
s
y1 <- x[!is.na(x)]
y1 <- x[!is.na(s)]
y1
x
x[1]
x[2]
x[FALSE]
x[TRUE]
x[1] , x[5]
x[1]
x[5]
c(x[1],x[5])
s
s <- c(s,0)
s
s[7] <- -1
s
s[9] <- -1
s
s[10] <- 1
(x+1)[(!is.na(s)) & x>0] -> z
z
x
s
z[-(4:7)]
z
c(z[1],z[-5])
fruit <- 1:4
fruit
names(fruit) <- c("orange", "banana", "apple", "peach")
fruit[1]
fruit[13]
fruit[3]
fruit["banana"]
fruit[2]
if (!is.na(s))
s1 <- s
if(!is.na(s))
s1 <- s
s1
s
if (is.na(s))
s2 <- s
s2
!is.na(s)
is.na(s)
for(x in s1)
print(x)
x
help(split)
?split
xc
xc <- split(s, ind)
x <- array(1:20, dim=c(4,5))
x
x[[1,3]]
x[1][3]
x[[1]]
x[[3]]
x[[,3]]
x[[0,3]]
x[[6]]
x
x[[4,5]]
x[4,5]
x[4,4]
x[3,3]
x[3]
c(x[1,3], x[2,2], x[3,1])
i
i <- array(c(1:3,3:1), dim=(2,3))
i <- array(c(1:3,3:1), dim=(3,2))
i <- array(c(1:3,3:1), dim=c(3,2))
i
x
x[i]
x[i] <- 0
x
for(j in x[j])
print(x[j])
for(j in x[j])
x[j]
j
for(j in x)
x[j]
for(j in x){
x[j];
print(j)
}
wheel
wheel <- c("DD", "7", "BBB", "BB", "C", "0")
wheel
combos
combos <- expand.grid(wheel, wheel, wheel, stringsAsFactors = FALSE)
combos
wheel <- c("DD", "7", "BBB", "BB", "B","C", "0")
wheel
combos <- expand.grid(wheel, wheel, wheel, stringsAsFactors = FALSE)
length(combos)
combos
combos$Var1
combos$Var2
combos$Var3
n <- 1
for(j in combos){
if (j == "BBB")
combos[n] <- "BBC"
n <- n+1
}
combos[1]
combos[[1]]
combos[[1,1]]
?replace
replace(combos,"BBB","BBC")
combos
replace(combos$Var1,"BBB","BBC")
combos
tail(combos)
replace(combos,combos="BBB","BBC")
combos1 <- as.matrix(combos)
replace(combos1,combos1="BBB","BBC")
combos[combos=="BBB"] <- "BBC"
combos
combos[combos=="BBC"] <- "BBB"
combos1
combos1[combos1=="BBB"] <- "BBC"
combos1
Lst
Lst <- list(name="Fred", wife="Mary", no.children=3, child.ages=c(4,7,9))
Lst
Lst$name
Lst$no.children
Lst[[1]]
Lst[1]
Lst[3]
Lst[[3]]
Lst2 <- list(1:3)
Lst2 <- list(casos=1:3, name="prueba", apellido="tulan")
Lst
Lst2
Lst3 <- c(Lst,Lst1)
Lst3 <- c(Lst,Lst2)
Lst3
getwd
getwd()
Titanic
titanic3
titanic3 <- read.table("titanic3.csv")
titanic3 <- read.csv("titanic3.csv")
summary(titanic3)
str(titanic3)
class(titanic3)
typeof(titanic3)
Lst2
cbind(Lst2,combos$Var1)
Lst2
Lst4 <- c(titanic3$pclass,titanic3$survived)
cbind(Lst4,titanic3$sex)
titanic3$sex
Lst4 <- cbind(Lst4,titanic3$sex)
Lst4
summary(Lst4)
Lst4 <- c(titanic3$pclass,titanic3$survived)
summary(Lst4)
summary(titanic3)
titanic3[titanic3$pclass == 1, 12:14]
titanic3[titanic3$pclass == 1, titanic3$survived, titanic3$home.dest]
titanic3[titanic3$pclass == 1, c(titanic3$survived, titanic3$home.dest)]
titanic3[titanic3$pclass == 1, c(2,14)]
titanic3[titanic3$pclass == 1 & titanic3$survived == 1, c(1,2,14)]
titanic3[titanic3$pclass == 1 & titanic3$survived == 1, 14]
titanic3[titanic3$pclass == 1 & titanic3$survived == 1, c(1,2,14)]
fruit
toupper(titanic3$home.dest)
titanic3$home.dest
substr("Hola Como estas", Hola, estas)
substr("Hola Como estas", "Hola", "estas")
?substr
substr("Hola Como estas", 6, 10)
substr("Hola Como estas", 1, 4)
?nchar
nchar("Hola Como estas")
s3
s3 <- c(1,2,20)
as.Date(s3)
?as.Date
s3 <- c("01/2/20", "02/15/20", "12/12/1999")
s3
s4 <- as.Date(s3, "%m/%d/%Y")
s4
s3 <- c("01/2/2020", "02/15/2020", "12/12/1999")
s4 <- as.Date(s3, "%m/%d/%Y")
s4
