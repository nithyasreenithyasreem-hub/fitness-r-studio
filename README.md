fitness <- data.frame(
  Day=1:12,
  Steps=c(3000,3500,4000,5000,6000,7000,8000,8500,9000,9500,10000,11000),
  calories=c(150,170,190,230,260,300,340,360,380,400,430,470)
)
plot(fitness$Steps,fitness$calories)
lines(fitness$day,fitness$step,type="l")
barplot(fitness$calories,col=c("skyblue"))
max(fitness$Steps)
hist(fitness$Steps,
