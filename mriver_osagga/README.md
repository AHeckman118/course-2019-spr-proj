Team Members: Miranda Rivera and Omar Sagga
## Narrative Project 2
The purpose of this project is to find a more efficient way of carpooling with Uber during rush-hour in New York City. During rush-hour, from 7am-10am and 5pm-8pm, carpooling with others is cheap, but inefficient, for the pick up points provided by Uber are not optimal. In an attempt to relieve commuters from walking long distances to their ubers or experiencing detours that delay the ride, our project uses the K-means algorithm to find K number of desired pick up points optimal for all riders. By analyzing the coordinates of all the pickup points at rush-hour, our algorithm determines the exact location commuters should walk to, to avoid long pick up waits, enjoy an efficient commute to work and pay cheaper fares while riding with others on Uber. Our statistical analysis of the average distance from original pickup point to the optimal pick up point generated by K-means, helps us score the new pick up point. The bigger K is the better the score will be, that is the smaller the distance the commuter will have to walk. If K increases, the score will decrease, meaning a smaller distance from the desired pick up point to the mean pick up point. 


Data Set used: Uber Pickups in New York City (filtered and aggregated rush-hour timestamps to form full data set of pickup points).



## Narrative Project 1

In Boston, hundreds of 311 Requests are called in daily by residents demanding maintenance of their respective vicinities. When searching the 311 request dataset, we came up with a few interesting questions regarding Boston and the maintenance of its neighborhoods: Are the areas that are most vulnerable being maintenanced? How does economic status of residents influence the types of requests that are called in and the time it takes the workers to fulfill a request? Should Boston be addressing these vulnerable areas regardless of received requests or not, given those areas may have residents whom are incapable of calling in a request? Does education play a roll in determining whether residents stop and take the time to call in requests for the good of the community? 


For project 1 we will be producing 3 datasets:
Boston Ages by Neighborhood 
Boston Income by Neighborhood
Boston Education by Neighborhood
To create these data sets, we performed some projections/selections/aggregation to clean the datasets and extract the demographics we were interested in. 


Eventually, we will be combining these datasets with the `311 requests` datasets and perform some relational operations in order to study the types of requests and how they are influenced by the neighborhood demographics. Hopefully, after multiple transformations, we will be able to see a meaningful correlation that will answer our questions. 

