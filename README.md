# The-DAPDP-Instances
The Drone-Assisted Pickup and Delivery Problem Instances

The following instances are originally presented in the paper The drone-assisted pickup and delivery problem: An adaptive large neighborhood search metaheuristic, written by Timothy Mulumba, Waleed Najy, and Ali Diabat, and published in Computers & Operations Research.

The data correspond to 92 instances corresponding to different scenarios for the Drone-Assisted Pickup and Delivery Problem. Each instance is named x.y.z, where x is the number of customers in the scenario, y is the dimension of the grid, and z is the generic name of the scenario. 
The first line of each instance file indicates the number of requests/ customers in the specific instance. The second line is the header for the characteristics of each request/ customer. These characteristics are Pickup Coordinate X, Pickup Coordinate Y, Dropoff Coordinate X, Dropoff Coordinate Y and Demand. The rows that follow contain the respective numeric values for each request.

We include an extra file, Parameters, which provides information about the value of the parameters in the main configuration of the problem. These parameters are:

•	TruckSpeed: Truck speed (miles per hour).

•	DroneSpeed: Truck speed (miles per hour).

•	TruckCapacityWithDrones: Truck load capacity with drone (kg).

•	TruckCapacityWithoutDrones: Truck load capacity without drone (kg)

•	DroneCapacity: Drone load capacity (kg).

•	ServiceTimeTruck: Truck service duration at each node (minutes).

•	ServiceTimeDrone: Drone service duration at each node (minutes).

•	Endurance: Flight endurance of UAV (minutes).

•	MaximumRouteDuration: Maximum duration time of the routes (hours).

•	LaunchTime: Time needed to load UAV before launch (minutes).

•	RecoveryTime: Time needed to recover UAV upon rendezvous (minutes).

•	CostFactor: Parameter for computing the cost in $ for a truck for traversing an arc (i,j), given the fuel price ($/liter), consumption rate (liter/km) and miles converter (km/miles).

•	DroneFactor: Corresponding parameter for computing the cost for a drone for traversing arc (i,j) with respect to the truck cost.
