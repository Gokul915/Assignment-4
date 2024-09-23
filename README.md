# Assignment-4
Frequency <- c(0.6,0.3,0.4,0.4,0.2,0.6,0.3,0.4,0.9,0.2)
Bp < - c(103,87.32,42,59,109,78,205,135,176)
First <- c(1,1,1,1,0,0,0,0,NA,1)
second <- c(0,0,1,1,0,0,1,1,1,1)
finaldecision <- c(0,1,0,1,0,1,0,1,1,1)



par(mfrow +c(1,2))

# 1.Boxplot for Blood pressure
boxplot(BP,
           main =" Boxplot"
           ylab = "Blood pressure"
           col = "red" 
           border = "blue"

# 2. Histogram for blood pressure 
hist(Bp,
          main = "Histogram"
          xlab = "Blod pressure"
          ylab = "Frequrncy"
          col = "brown"
          border = "black"
          breaks =  5)

# reset layout to defult 
par(mfrow = c(1,1))
      
    

           
