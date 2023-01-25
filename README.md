# The Drone-Assisted Vehicle Routing Problem with Robot Stations and Time Windows Instances

A repository with instances for the VRPD-RS-TW. These instances are built for a real case study on the small and large rings of the city of Amsterdam, the Netherlands. To build the instances, we randomly generated three different instance types of 5, 10, 15, 50, 75, and 100 customers size for each type. Customers were selected from the district Amsterdam Centrum for the small instance set, and from districts Amsterdam Centrum, Noord, Oost, West, and Zuid for the large instance set. Here, the depot is placed in the south-west outskirts of Amsterdam since that area is well-connected to multiple highways entering the city center, as well as the districts in the suburbs. Trucks distances and travel times are based on city-car road distances and speed, respectively. Robot distances and travel times are based on pedestrian distances and speed, respectively. Done distances are based on the Harvesine formula to compute the great-circle distances by considering a mean earth radius value r = 6371 kilometers. Drone travel times are based on drone speeds.

The VRPD with Robot Stations and Time Windows (VRPD-RS-TW) is a generalization of Vehicle Routing Problem with Time Windows (VRP-TW), where a fleet of trucks assisted each by a single drone should work in collaboration to serve customers with their corresponding parcels. In the VRPD-RS-TW trucks are allowed to visit robot stations that can dispatch autonomous robots to deliver parcels. In this regard, the VRPD-RS-TW is a transportation problem focused on last-mile delivery operations, where autonomous vehicles, such as drones and robots are involved in the delivery process and together should minimize logistic costs while meeting time windows constraints.

Comments within an instance's file start with /* and end with */ have to be ignored.

This repository contains the instances used for the paper "The Drone-Assisted VRP with Robot Stations and Time Windows". Campuzano Giovanni, Mes Martijn, & Lalla-Ruiz Eduardo. DOI:

You are kindly requested to cite this paper if these instances are relevant to your research.
