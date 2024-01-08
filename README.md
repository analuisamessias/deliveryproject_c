# deliveryproject_c
This project simulates a restaurant delivery app.

Consider a city represented as a matrix, where the city includes both restaurants and streets. Streets are represented by coordinates (x, y), indicating whether the coordinate is paved (1) or not (0). If two adjacent coordinates are paved, then the segment between those coordinates is also paved. The file "streets.txt" provides information about paved and unpaved segments (x, y, paved). All restaurants are accessible through the streets, meaning there is always a possible path between a paved location and a restaurant. Furthermore, there is always only one possible path.

Restaurants can be either cheap or expensive, and each restaurant has a delivery person. The delivery person makes deliveries with a motorcycle, and the motorcycle's speed is specified. The file "restaurants.txt" contains this information (x, y, name, cost, speed). The unit of distance is called "zambs." The distance between two adjacent coordinates in the matrix corresponds to one "zambs." Motorcycle speeds are given in zambs/minute.

You should input (via keyboard) the coordinates of your house. Note that your house must be on a paved segment of the city.
