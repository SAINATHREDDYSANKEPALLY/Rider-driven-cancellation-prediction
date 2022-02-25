
# Rider driven cancellation Prediction using ML
 The  business of Shawdofax company  includes delivering food orders from clients such as Swiggy and Zomato to customers. The typical order flow goes something like this:
A client creates the order in their system

The order gets allocated to a rider,
The rider accepts the order,
The rider goes to the pickup location,
The rider picks up the order,
The rider goes to the delivery location and delivers the order,
The rider also has the option to get the order cancelled before delivery by calling the client’s call centre. The task is to to predict this kind of cancellation before it happens so that they can try and reassign the order to another rider before it gets cancelled.



![Logo](https://global-uploads.webflow.com/5f4b7e375695f50f9f0ffbb5/6208e800cfa704af82aac3fd_Shadowfax.png)

## Acknowledgements

 - [Consulting and Analytics club, IIT Guwahati](http://iitg.ac.in/sa/caciitg/)
 

##  Data set information

order_id : unique id for each order,

order_time: time of the creation of order by the client,

order_date : date of the order,

allot_time: time of allocation of order to the rider,

accept_time: time of acceptance of the order by the rider (if available),

pickup_time: time of pickup of the order (if available),

delivered_time: time of delivery of the order (if available),

cancelled_time: time of cancellation of order (if the order was cancelled),

cancelled: whether the order was cancelled,

rider_id: unique id for each rider,

first_mile_distance: road distance from rider’s location to the pickup location,

last_mile_distance: road distance from pickup location to the delivery location,

allotted_orders: total number of orders allotted to the rider in the 30 days before (not including) order_date,

delivered_orders: total number of orders delivered by the rider in the 30 days before (not including) order_date,

undelivered_orders: total number of orders allotted to but not delivered by the rider (i.e. cancelled) in the 30 days before (not including) order_date,

lifetime_order_count: total number of orders delivered by the rider at any time before order_date,

reassigned_order: whether the order was reassigned to this rider,

reassignment_method: if the order was reassigned, whether the reassignment was done manually (by the ops team) or automatically,

reassignment_reason: a more detailed reason for the reassignment,

session_time: total time the rider had been online on order_date before order_time,


## Roadmap

- Additional browser support

- Add more integrations

