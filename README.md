# SERIES-DE-TIEMPO
x <-1:25  #despues de escribir cada cosa darle control r y enter, al termino de la funcion, y me va dar resultados
x 
mean(x)
ls()  #muestra cuantos objetos tenemos
y <-2:19
ls()
x2 <-c(2,5,8)  #la flechita es un vector de asignación
x3 <-c(1.3,5.9,7.4)
y1<-seq(8,80,4) #secuencia del 8 al 80 en intervalos de 4
y1
y2<-seq(6,120,5)
y2
length (y1)  #muestra la longitud del vector
length (y2)
mean(x)  #es la media del vector
media<-sum(x)/length(x)  #length es nuestra "n"----es la creación de una función
?sum
rm(x) #para borrar un objeto
ls ()
rm(list=ls())  #borrar todo
ls()
nse<-c("alto","medio","bajo")   #nse nivel socioeconomico
ls()
tds<-c("A","B","O+","O-")
################VECTORES CON DISTRIBUCIONDE PROBABILIDAD
x<-rnorm(100)   #para que nos de valores aleatorios en decimales
x
plot(x)  #simulacion grafica
b<-1:100    #para que nos de valores aleatorios enteros
b
plot(b,x)
y=x+rnorm(100,mean=50,sd=0.5)
cor(x,y)

mean(y)
var(y)
sd(y)
################operdores relacionales#############
#<,>,<=,>=,==,!=
8==7.99999999999999999999999999999999999999  
x<-17
x==17
x<=19
# "&"  "|"  =  "y"  "o"
a<-1:100
a[a<b & a<3]


_______________________________________
install.packages("readxl")
library(readxl)
rates <- read_excel ("C:")
