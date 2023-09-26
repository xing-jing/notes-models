structure:
- earth
- atmosphere
- boundary between earth and atmosphere
	- this includes [[Soil|soil]]

surface processes
- fundamental causes, conceptually
	- kinetic energy, [[Potential energy|potential energy]]
	- heat (small scale motion) and topography (gravitational potential energy) drives mechanics (large scale motion)
- causes, actual
	- radiogenic heat and primordial heat
		- **heat sources**
			- radiogenic heat from **decay of radioactive isotopes** in **crust and mantle**
			- primordial heat left over from **planet's formation and accretion**
				- gravitational energy released upon segregation of metallic core from silicate mantle
		- result: mantle convection driven plate tectonics
		- other sources of heat in mantle: tidal friction from the Moon's pull on Earth[^1]
	- heat from **uneven solar heating**
		- result: atmospheric circulation (of water)
	- effect of heat - "the surface temperatures of Earth span the phase boundaries of H<sub>2</sub>O"
		- result: topography
			- from impact of ice (glaciers), water (rivers, precipitation), water vapour

>The Earth’s surface is the boundary between rock put in motion by deep geophysical processes and the atmosphere put in motion by uneven solar heating. Neither motion is steady. Earthquakes punctuate the motion of the rock. Storms punctuate the motion of the atmosphere.

---

plate tectonics and mantle convection
- mantle convection **drives** plate tectonics
- plate tectonics is the **expression** of mantle convection

>Mantle convection and plate tectonics are more than simply mechanically coupled. The plates are, in fact, an integral part of the mantle circulation: they are clearly formed at ridges and recirculate into the mantle through subduction zones. In essence, plate tectonics is the surface expression of mantle convection.[^4]

since there is a causal link, we consider primarily the cause i.e. the convective system

convective system (a Rayleigh-Benard system)
- parts of system
	- upper and lower boundaries with temperature difference
	- fluid between upper and lower boundaries
		- a **fluid parcel** <- subject of analysis, of whether convection occurs
- interaction between parts of system
	- upwards displacement (of **fluid parcel**): **buoyancy**
	- dampening (of upwards displacement): **viscosity** and **thermal conductivity**
	- refer to the Rayleigh number, but in general a large temperature difference and thermal expansion coefficient will result in thermal convection
- fundamental causes of interaction
	- **gravitational instability** (density difference, typically from temperature difference (thermal expansion coefficient != 1))
	- **gravitational instability** may become **convective instability** (if upwards displacement of fluid parcel is not sufficiently dampened by viscosity, if temperature difference is not sufficiently mitigated by thermal conduction)

this is described in the Rayleigh number[^2]
![[Pasted image 20230924172408.png]]
derivation:
- buoyancy force (gravitational acceleration x density difference between parcel and surroundings)
	- assume density difference is solely due to contrast between temperature and surroundings (density difference = density x thermal expansion coefficient x temperature difference between parcel and surroundings)
- viscosity force (scaling factor x acceleration)
- account for thermal conduction by setting temperature difference as function of time
- integrate from zero to infinity across dt to get how far the parcel can move in infinite time (distance traversed by parcel)
- set right side as distance traversed - left side is Rayleigh's number

> at ∆T > 0 (i.e., heating is from below and causes **gravitational instability**)
> R<sub>a</sub> still must exceed a certain value, called the critical Rayleigh number R<sub>ac</sub> for convection to occur
> for R<sub>a</sub> < R<sub>ac</sub> the layer is stable and transports heat by conduction
> for R<sub>a</sub> > R<sub>ac</sub> the layer will be convectively unstable and transport heat more rapidly via convection
> although R<sub>ac</sub> varies depending on the mechanical nature of the horizontal boundaries (whether rigid or a free surface) it is typically of order 1000

more on mantle convection - [ms3.dvi (yale.edu)](https://people.earth.yale.edu/sites/default/files/files/Bercovici/17_MantlConvection-ESEG2011-2_0.pdf)

convection, applied to mantle convection[^3]
- process/interaction view
	- convective currents **deform** and **chemically modify** the top and bottom boundary layers
		- hot upwelling mantle currents generate **surface uplifts** or induce **volcanic activity**
		- downwelling currents (due to sinking mantle material) pulls the surface down from below
- form/structure view (terms of various components)
	- the earth's **surface** is a **top cold thermal boundary layer**, and is subdivided into **tectonic plates**
		- **plates** have **plate boundaries** (convergent, divergent, transform)
			- **convergent boundaries** are **subduction zones**, and cooler, denser plates sink into the **mantle**
			- **divergent boundaries** are **mid-ocean ridges**, where **hot mantle material** undergo **partial melting** and **ascend** to drive **ridge volcanism** and form new **oceanic crust**
			- **transform boundaries** are not directly associated with upward/downward convective currents, and are likely due to non-linear rock **rheology** (the way a rock responds to stress through deformation or strain rate) to indirectly couple it to convective motion)

form/structure view
- tectonic plates: cold thermal boundary layer of the convective mantle system (conductively cooled surface layer)
	- composition: differentiated mantle (crust, depleted lithosphere) on top, undifferentiated mantle at bottom
- structure of tectonic plates themselves - consider its **rheology** (consider its response to stress, given that it's primarily subject to stress)
	- cause:
		- plates undergo **tensional**, **compressive**, **shear** stresses from the movement of tectonic plates
	- result:
		- two types of **crustal deformations**: **faults** and **folds**
		- faults
			- definition: break in rock formation + slip along it
			- more rigorous definition: faults are planes across which shear motion of the adjacent walls takes place when the frictional strength of the materials is exceeded; the resulting earthquakes are major hazards for humans on the earth's surface
			- types: **normal**, **reverse**, **transform** faults
		- folds
			- definition: layers of rock deformed (curved, bent) by plastic (ductile) deformation (typically by compressional forces)
			- types: **anticlines**, **synclines**
		- crustal deformations (faults, folds) give rise to: **earthquakes**, **mountain ranges**

earthquake
- when stress overcomes **friction**, movement of slip along faults produces **seismic waves** that propagates through **earth's layers**
- rupture, elastic rebound, aftershocks
- earthquake characterization: location, magnitude (amount of energy released), intensity (destructive effects of ground shaking)

>These motions crinkle the margins of the plates, generating belts of mountains, and drive volcanism that dots the topography with volcanoes where plates descend.

>A further clue regarding the physics of toroidal-poloidal coupling was provided by O’Connell, Gable & Hager (1991) who demonstrated with Monte Carlo methods that the present day plate motions minimize the toroidal kinetic energy. However, the physical mechanism by which the interaction of flow and rheology creates distinct plates with strike-slip margins is not well understood. Olson & Bercovici (1991), using simple statistical arguments, hypothesized that the present state of toroidal-poloidal near equipartitioning occurs because plastic or pseudo-plastic rheology causes the plates (and the underlying convection cell, if one is present) to be decoupled from each other to the extent that the plates drift nearly independently of one another.

>The celestial mechanics of our planet’s motion, which includes interactions with other planets in the solar system, leads to variations in the Earth’s orbit, which in turn drive variation in the delivery of energy to the Earth. In the last couple of million years, this has resulted in numerous major swings in the climate on the Earth, leading to the growth and demise of huge ice sheets on northern continents.

that is, climatic swings between **glacial** and **interglacial** periods

definitions
- convection: buoyancy-driven fluid flow
- rayleigh number: a dimensionless number associated with convection, that can also characterise the fluid's flow regime; it describes the behavior of fluids when the mass density of the fluid is non-uniform
- rheology: relationship between applied stress and resultant deformation

---

water cycle
- definition: circulation of meteoric water through the hydrosphere, atmosphere and upper parts of crust

drainage system
- definition: area of land drained by a river and its tributaries
- types:
	- surface drainage system
	- subsurface drainage system
- geographic area of drainage system is called a **drainage basin**, also called **watershed** in USA, **catchment** in UK

fundamental unit of landscape (quanta of geomorphic system): **drainage basin**
- hillslopes deliver **water** and **sediment** to streams at their base; streams form dendritic network breaking landscape into drainage basins - **streams bound hillslopes**

processes[^5]

![[Pasted image 20230924234954.png]]


definitions
- interception: temporary storage of water on the surface of plants/buildings before it reaches the surface
- infiltration: movement of water **into** soil
- throughflow: movement of water **through** soil
- groundwater flow: movement of water above impermeable rock (bedrock)

read in depth about the processes at https://www.nwrfc.noaa.gov/info/water_cycle/hydrology.html

the water cycle and plate tectonic processes combine to create the **rock cycle**

--- 

![[Screenshot 2023-09-26 at 12.32.41 PM.png]]

rock cycle
- form, structure view
	- rocks
		- igneous: formed from **crystallization** of cooling magma
		- sedimentary: formed from compaction and cementation of sediments, which are formed from erosion of rocks and deposition of sediment
			- clastic
			- 
		- metamorphic: formed from heat and pressure on existing rock - **solid-state recrystallization** occurs
- processes/interactions
	- weathering, transport, deposition

rock cycle, step by step
1. volcanoes, folding, faulting, uplift bring igneous and other rocks, water, and gases to the base of the atmosphere and hydrosphere.
2. once exposed to air and meteoric water, these rocks begin to decompose and disintegrate by the action of weathering.
3. gravity, wind, and water transport the weathering products to the oceans.
4. deposition occurs on the ocean floor.
5. burial of the loose sediments leads to compaction, cementation and recrystallization, and so the formation of sedimentary rocks. 
6. deep burial may convert sedimentary rocks into metamorphic rocks through heat and pressure.
7. if uplifted, intruded or extruded, and exposed at the land surface, the loose sediments, consolidated sediments, metamorphic rocks may join in the next round of the rock cycle.

compaction, definition
- continued compression of buried sediments reduces **pore-spaces** and removes excess water

cementation, definition
- chemical change whereby individual grains are cemented together as minerals are **precipitated** out of **saturated solution** that is percolating as a matrix between individual sediments
- note - also removal of water (saturation of solution precipitates minerals)

lithification
- either compaction, cementation or both

types of weathering
- chemical: depends on particle size (surface area exposed to chemical attack), permeability (rate at which water seeps into rock body - dictates internal surface area exposed to weathering)
- mechanical: freeze-thaw cycles, wet-dry cycles, heating and cooling cycles

types of transport
- sediment transport (essentially mechanical)
	- mass movement (a lot of sediment moving en masse)
	- fluid transport (sediment moving as individual grains dispersed in fluid)
- solutional transport (essentially chemical)
- fundamental causes: gravity (i.e. potential energy), fluid flow (i.e. energy-momentum relation)

> Wind carries sediment in much the same way as water does - along the 'bed' or in suspension. But, as air is far less dense a fluid than water, for the same flow velocity it carries sediment of smaller grain size.

deposition process
- when the transporting capacity of the fluid is insufficient to carry the solid sediment load
- or where the chemical environment leads to the precipitation of the solute load
- deposition of sediment occurs
- **sedimentary bodies** occur where deposition outpaces erosion, and where chemical precipitation exceeds solutional loss.

definitions
- rock cycle: the repeated creation and destruction of crustal materials - rocks and minerals
	- also: the processes undergone by the three main rock types as they form, move and transform from one type into another
- weathering: a process that disintegrates and **loosens** rock
	- also: the decay of rocks by biological, chemical, and mechanical agents with little or no transport
	- outcome: a **mantle** of rock waste. the weathered mantle may stay in place or move down **hillslopes**, down **rivers**, down **submarine slopes**.
- regolith: weathered rock (any degree of weathering)
- saprolite: weathered rock that is sufficiently broken down that it can be readily augured through or dug through, yet retains the original rock structure
	- retention of original rock structure implies:
		- rock has not undergone strain, and has likely undergone isovolumetric weathering (no change in volume)
		- saprolite has not been displaced or mobilized (i.e. material has not undergone strain)
- mass movement: bulk transfer of rock debris down slopes under influence of gravity
- erosion: sum of all destructive processes by which weathering products are picked up and carried by transporting media

> Weathering, transport and deposition are essential processes in the rock cycle. Volcanic action, folding, faulting and uplift may all impart potential energy to the toposphere, creating the 'raw relief' on which geomorphic agents act to fashion the marvellously multifarious array of landforms found on the earth's surface - the physical toposphere. Geomorphic (or exogenic) agents are wind, water, waves and ice, which act from outside or above the toposphere; these contrast with endogenic (tectonic and volcanic) agents, which act upon the toposphere from inside the planet.


---

misc. - wind and atmospheric circulation

wind: the motion of air
motion - when there is a net force
atmosphere - driven by variations in pressure
because the Earth is spinning, the Coriolis effect causes the apparent trajectory of the air mass as seen by an observer on the Earth to bend to the right in the northern hemisphere and to the left in the southern hemisphere

wind system
- major wind system
- specific winds set up by local but persistent pressure fields: monsoons, sea breezes, katabatic winds

Now we must come to grips with the fact that the fluid in motion is of low enough viscosity, is thin enough, and is moving fast enough, to be turbulent. A manifestation of turbulence is the instability of flows to disturbances, such that they evolve toward chaotic motion that includes many scales of eddies.

The forcing of the geomorphic system is therefore not well characterized by the mean flow of the atmosphere, the mean annual temperature, the mean annual precipitation, and the mean waves that might well be used to characterize the “climate” of a region. Rather, we must acknowledge the reality that these quantities are stochastic and can be only statistically described.

definitions
- weather: state of atmosphere at any given time at a specific place
- climate: weather over a long period of time at a place or over a region
	- i.e. statistical mean of weather
- atmosphere: (top-down view) thin, gaseous envelope over the earth. (bottom-up) N<sub>2</sub>, O<sub>2</sub>, H<sub>2</sub>O, CO<sub>2</sub>, and small quantities of other gases
- cloud: visible aggregate of tiny water droplets or ice crystals suspended in air
	- cloud formation: convection, topography, convergence of air, lifting along weather fronts

> Since this cloud is supported by an updraft, the bottom of the cloud is relatively flat compared to the top.


---


views, macro to micro level level
- earth layers: crust, mantle, core; lithosphere, etc...
- within earth layer: tectonic plate, plate boundary, faults, folds
- within tectonic plate: rock - igneous, metamorphic, sedimentary
- within rock: minerals - feldspars (aluminium silicates w/ potassium, sodium or calcium), clay minerals (complex aluminosilicates), ferromagnesian minerals (iron magnesium, calcium silicates)

---

We live on a blue, white, brown, and green, nearly spherical, spinning, canted planet, 150 million kilometers from a medium-sized 4.5-billion-year-old star (Figure 1.0). One moon adorns the sky and tugs the ocean of its parent planet into a giant moving permanent wave. The moon was born early of a massive collision. That event set the planet spinning on an axis tilted with respect to the plane of the ecliptic, yielding daily and seasonal variations in radiation reaching the surface. The Earth is cooling down. Heat moved efficiently toward the surface by convection of the mantle is more slowly conducted through the outermost, coolest layer, which behaves as a solid on geological timescales, and which is broken into a small number of tectonic plates. The descent of old, cold, thickened plates from the surface also drives a creeping circulation of the mantle, at speeds of several cm per year, and establishes the relative motions of the plates. These motions crinkle the margins of the plates, generating belts of mountains, and drive volcanism that dots the topography with volcanoes where plates descend. But this topography is subject to attack. That the Earth is both blue and white reflects the fact that water can be found in all three phases at the surface of the planet – blue liquid water, white water vapor (clouds), and ice. This unique aspect of Earth is allowed by being the right distance from the Sun, having an atmosphere that contains gases capable of absorbing long-wavelength radiation, and being large enough to retain these gases. The atmosphere and ocean of the planet are in motion as well; unlike the mantle, motion of fluids of the hydrosphere and atmosphere is turbulent, at speeds up to many meters per second, driven by both the uneven solar heating of the planet and its spin. Water evaporated from lakes and oceans, and transpired by land plants, is transported by storms spawned within the atmosphere, and then precipitates as either rain or snow. It is the motion of these substances, rain immediately and snow more slowly, where it accumulates sufficiently to become a glacier, moving down slopes ultimately generated by crustal processes, that leads to the dissection and sculpting of the land surface. None of these phenomena are steady on geologic timescales. Wind, water, and ice erode, transport and deposit sediment in discrete episodes of activity. Movement of continents on the surface of the planet slowly changes the circulation of atmosphere and oceans. The celestial mechanics of our planet’s motion, which includes interactions with other planets in the solar system, leads to variations in the Earth’s orbit, which in turn drive variation in the delivery of energy to the Earth. In the last couple of million years, this has resulted in numerous major swings in the climate on the Earth, leading to the growth and demise of huge ice sheets on northern continents. These set the climatic context within which human civilization has arisen and have greatly influenced the landscapes with which we interact.


[^1]: [Mantle Convection and Plate Tectonics (article) | Khan Academy](https://www.khanacademy.org/partner-content/amnh/earthquakes-and-volcanoes/plate-tectonics/a/mantle-convection-and-plate-tectonics)
[^2]: [Ocean 540: Convective Heat Transfer (washington.edu)](http://www2.ocean.washington.edu/oc540/lec02-8/)
[^3]: [Mantle Convection in Terrestrial Planets | Oxford Research Encyclopedia of Planetary Science](https://oxfordre.com/planetaryscience/display/10.1093/acrefore/9780190647926.001.0001/acrefore-9780190647926-e-109)
[^4]: [A Simple Model of Plate Generation from Mantle Flow (yale.edu)](https://people.earth.yale.edu/sites/default/files/files/Bercovici/86_nnewt-GJI93.pdf)
[^5]: [The drainage basin system - The drainage basin - CCEA - GCSE Geography Revision - CCEA - BBC Bitesize](https://www.bbc.co.uk/bitesize/guides/zxvw4qt/revision/2)