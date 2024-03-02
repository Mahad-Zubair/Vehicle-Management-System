# Vehicle-Management-System
This database will keep track of all the damage, repairs, maintenance, and parts that have been replaced since production. This will help the owners determine the health of the mechanical components of the vehicle


There are six relationships in our logical schema which have been displayed in the ERD as well. The Relationships are as follows: 
•	Owner – OWNS – Vehicle(s): Owner has a one-to-many relation with vehicle with a mandatory participation of the two attributes. 
•	Workshop – PROVIDES – Services: Workshop has a one-to-many relation with Services and a mandatory participation of the two attributes. 
•	Vehicle – HAS – Registration Details: Vehicle has a one-to-one relation with Registration Details and a mandatory participation of the two attributes. 
•	Vehicle – UNDERGOES – Service: Vehicle has a one-to-many relation with Services and an optional participation of the two attributes. 
•	Vehicle – HAS – Parts: Vehicle has a one-to-many relation with Parts and mandatory participation of the two attributes.
•	Service – REPLACES – Parts: Service has a one-to-many relation with Parts and optional participation of replaced parts.


Owners of vehicles can avoid unforeseen car problems by maintaining their vehicles regularly. Early detection of vehicle concerns is crucial to preventing them from developing into serious difficulties. Vehicle technicians will examine crucial parts of the vehicle and fix problems to make sure they are in good condition and won't break down suddenly. Car Owners will be aware of all the history of repairs and service that vehicle has gone through and hence the technicians can diagnose the future issues more efficiently. At the time of selling or purchasing used cars, it will benefit customers to view the history of the changes the car has gone through, helping them take wiser decisions.
