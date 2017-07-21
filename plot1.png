data<-read.table("household_power_consumption.txt",header=TRUE,sep=";",stringsAsFactors=FALSE,dec=".")
data1<-data[data$Date%in%c("01/02/2007","02/02/2007"),]
png("Plot1.png",width=480,height=480)
hist(as.numeric(data1),col="red",xlab="Global Active Power(kilowatts),ylab="frequency",main="Global Active Power")
dev.off()
