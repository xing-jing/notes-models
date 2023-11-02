this note describes:
- the two main functions of roads, and how to categorize roads according to how they fulfil the functions
- road elements
- pavement structure and function
- traffic flow types and characteristics - this is is relevant against road function

###### Road
- thoroughfare for conveyance of traffic, usually with an improved surface for use by vehicles and pedestrians
###### Roadway
- part of a road intended for vehicles

**Access** and **mobility**, two opposing functions of roadways[^8]
> Roadways serve two primary travel needs: access to/egress from specific locations and travel mobility. While these two functions lie at opposite ends of the continuum of roadway function, most roads provide some combination of each.
> - **Roadway mobility function**: Provides few opportunities for entry and exit and therefore low travel friction from vehicle access/egress
> - **Roadway accessibility function**: Provides many opportunities for entry and exit, which creates potentially higher friction from vehicle access/egress

Hence a general **functional classification** of roads would be:
![[Pasted image 20231102175020.png]]
Singapore' implementation[^9]
- expressway - optimization of **long distance mobility**
- major arterial - traffic from one **region** to another **region**
- minor arterial - **distributes traffic** within major **residential and industrial areas**
- primary access - provides **access to developments**; through traffic is **discouraged**
- local access - **direct access** to buildings and other developments, should connect only with primary access

road elements
- road markings and signage
- lanes
	- increased lane width decrease number of accidents when traffic volumes are high
	- increased number of lanes usually decrease the number of accidents
- pavement
	- surface condition - presence/absence of potholes can inform about vehicle load/climatic conditions
![[Pasted image 20231102170756.png]]

> [!comments]
> LTA documents (Standard Design of Road Elements) actually uses US terminology

modeling pavement
- components:
	- layers of pavement (wearing course, base course, subbase, subgrade (soil))
	- grains vs slab
- interactions:
	- wheel causing **wheel load stresses** onto pavement (mediated by **loading time**, **temperature**)
	- pavement **distributing** or **transmitting** wheel load stresses to lower layers, subgrade

pavement
- structure consisting of superimposed layers of processed materials above the natural **soil subgrade**
- whose **primary function** is to **distribute** the **applied vehicle loads** to the **subgrade**

>The ultimate aim is to ensure that the transmitted stresses due to wheel load are sufficiently reduced, so that they will not exceed the bearing capacity of the subgrade

types of pavement[^6][^7]
- flexible pavement
	- stress distribution characteristics:
		- transmits wheel load stresses to lower layers through **grain-to-grain** transfer
		- depends on **aggregate interlock**, **particle friction** and **cohesion** for stability
	- major failure modes:
		- fatigue cracking, rutting, thermal cracking
			- may be difficult to simulate due to difficulty of characterizing pavement materials under **repeated** and **moving loads**; asphalt concrete material (typically wearing course) is **viscoelastic** and **viscoplastic** i.e. strongly **loading time** and **temperature** dependent
- rigid pavement
	- stress distribution characteristics
		- transmits wheel load stresses to wider area below via **slab action**
			- slab action: **load carrying capacity** is mainly due to the **rigidity** and **high modulus of elasticity** of the **slab**[^5]
		- simulated via **finite element analysis**

modeling traffic flow
- condition - **interrupted**/**uninterrupted** flow
- components of system: **vehicle**, **roadway** - **point** on roadway vs **length** of roadway

##### types of traffic flow[^1]
- uninterrupted flow
	- flow regulated by **vehicle-vehicle interactions** and **vehicle-roadway interactions**
	- primarily on freeways[^4]
- interrupted flow
	- flow regulated by external means e.g. traffic signal, and only vehicle-vehicle and vehicle-roadway interactions secondarily

##### traffic flow parameters[^2]

traffic **volume**
- number of **vehicles** that pass a given **point** on the **roadway** in a specified period of time (unit: num_vehicles)

traffic **flow**
- rate at which **vehicles** pass a given **point** on the roadway (**unit**: num_vehicles/hr)

> Actual traffic data is often much noisier than idealized models suggest. However, what we tend to see is that as density rises, speed is unchanged to a point (capacity) and then begins to drop if it is affected by downstream traffic (queue spillbacks).[^3]

density
- number of **vehicles** present on a given **length** of **roadway** (unit: num_vehicles/km)

under **uninterrupted flow** conditions:
flow (vehicles/hr) = speed (km/hr) x density (vehicles/km)

cases of low flow: high speed, low density; low speed, high density (traffic jam, **congestion**)

>[!comments]
>Note that transport focused on roads assumed **vehicular traffic** - as opposed to rail, or pedestrian traffic. Optimization that is road-focused tends to represent the **traffic** or **mobility** perspective, not the **accessibility** perspective.


[^1]: https://www.webpages.uidaho.edu/niatt_labmanual/chapters/trafficflowtheory/theoryandconcepts/TypesOfTrafficFlow.htm
[^2]: https://www.webpages.uidaho.edu/niatt_labmanual/chapters/trafficflowtheory/theoryandconcepts/TrafficFlowParameters.htm#:~:text=Volume%20is%20simply%20the%20number,at%20the%2015%2Dminute%20volume.
[^3]: https://eng.libretexts.org/Bookshelves/Civil_Engineering/Fundamentals_of_Transportation/05%3A_Traffic/5.02%3A_Traffic_Flow
[^4]: http://www.ce.memphis.edu/4162/L1_Traffic_Flow_Parameters.pdf
[^5]: https://www.civil.iitb.ac.in/~vmtom/nptel/411_lnTse/web/web.html#:~:text=As%20the%20name%20implies%2C%20rigid,the%20slab%20(slab%20action).
[^6]: https://www.e3s-conferences.org/articles/e3sconf/pdf/2018/20/e3sconf_infraeko2018_00082.pdf
[^7]: https://www.studocu.com/sg/document/national-university-of-singapore/civil-engineering-transport-engineering/ce3132-02-pavement-materials-and-design/19109976
[^8]: https://www.fhwa.dot.gov/planning/processes/statewide/related/highway_functional_classifications/fcauab.pdf
[^9]: https://www.lta.gov.sg/content/dam/ltagov/industry_innovations/industry_matters/development_construction_resources/road_line_plan/pdf/Road_line_Plan_Explanatory_notes_final.pdf