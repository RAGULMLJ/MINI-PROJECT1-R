# MINI-PROJECT1-R

# Create Pie from the Data
numbers<- c(53, 5, 4, 2, 1, 1, 1, 1, 4)
labels <- c(53, 5, 4, 2, 1, 1, 1, 1, 4)

# Plot the chart with title and rainbow
# color pallet.
pie(numbers, labels, main ="Passengers from Different Country in Flight Crash",
			col = rainbow(length(numbers)))
			legend("topright", c("Nepalese", "Indians", "Russians", "Koreans","Ireland" ,"Australia", "Argenina", "France", "Crew"),
					cex = 0.5, fill = rainbow(length(numbers)))
