<h1> cardinaalit </h1>  
cardinality Counter for large .data files, uses MapReduce method to count unique visitors on our company's app. This is later used to support our AdXchange system and better monetizes Ad Displays to maximize efficiency and value. 
Basically, it counts unique visitors for a given file (hourly) and that data lets us determine which hours of the day are the most popular. Then, we can better "auction" those hours with our companies AdXchange system by showing that our data supports that those hours are when the net-traffic is highest.
Reads in large text files, counts unique lines, prints a total count of unique lines.   
Tested with .data file of 5GB formatted as below.  
a1293013NJEw|12DKSDNwieWQ|\N|\N|\N|  
jasoid12312J|12903i1023iD|\N|\N|\N|  
etc.   
Final Result: 
unique visitors to site is 84646983

Edit 2: 
Final Result now prints number of each type of device. Ex. iphone6 6, android 5, etc.

