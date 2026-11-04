# Introduction

I’m currently in the process of understanding if it would make sense to do an energy renovation of my apartment. However, the process is quite complex as it involves multiple options. Do I have to involve the entire building in the process? Or should I focus on interventions that I can do alone? Is it better to install only photovoltaic panels, or is it better to combine them with electric storage? Would the panels produce enough energy to make a significant contribution to my expenses and CO2 footprint? How complicated is the permitting and installation process?

I imagine that these questions are the same for a lot of Belgians, especially those living in a city such as Brussels where living in co-owned buildings or renting is very frequent. For this reason, I thought it could be helpful to document the process, which can be easily replicated by other people in the same situation.

Also, my research at [SWIFFT](https://www.swifft.be/) focuses on modeling energy systems to plan the energy transition, and I thought it would be interesting to discuss some of the challenges associated with the energy transition through the lens of home renovations.

As a disclaimer, I'm not an expert in home renovation in Brussels or a qualified electrician, so take this considerations with a grain of salt.

## Brief technological recap

Before diving into the techno-economical analysis, I will give a brief overview of the main technologies that can be installed on a residential level. These are often called Distributed Energy Resources (DERs), because they are geographically spread in the urban environment instead of being localized, as traditional energy systems. This [page](https://environnement.brussels/citoyen/agir-pour-lenvironnement/renover-et-construire/quest-ce-que-lenergie-verte) provides a nice overview by Brussels Environment of residential green technologies that can be considered in Brussels. In the rest of this blog, I will focus mainly on two types of technologies: solar panels and battery storage.

Solar panels are devices that convert solar electromagnetic emission into electric current. They are also called photovoltaic (PV) panels to distinguish them from solar thermal panels, which convert sunlight into heat. I will focus on PV panels so I will use the term solar panels and PV panels interchangeably.
Solar panels produce electricity in the form of direct current, at a relatively low voltage (12 to 48 V). However, the current that we conventionally use in our homes is alternated current at a much higher voltage of 240 V. This means that to couple solar panels with the residential electric circuit we need to convert the direct, low voltage current into alternated, high voltage current through the use of an inverter.

In this [page](https://environnement.brussels/blog-citoyen/dossiers/les-panneaux-solaires-en-10-questions), you can find a nice article by Brussels Environment explaining residential solar panels in ten questions.

Nowadays, PV systems are also coupled with electric storage in the form of batteries. As traditional cellphone batteries, electric storage converts the electric energy into chemical energy, which is released when needed. Electric storage is particularly useful in combination with PV panels because it allows to spread the consumption of renewable energy throughout the day.

In terms of measurements, the power produced by the solar panels is defined as the amount of sunlight converted into electricity every second, measured in Watts (W). The producers of the solar panels list its peak power, which is the electrical power generated when sunlight perpendicular to the solar panel hits it with an irradiance of 1000 W/m2. This reference irradiance mimics the average amount of sunlight hitting the Earth.

The electrical energy produced by a solar panel is obtained by summing the electrical power across a specific time interval. For example, a panel generating 1000 W for an hour will have generated a 1000 Watt hour (Wh) or 1 kWh. Thus, the W is a measure of power (energy per unit of time) while the kWh is a measure of energy. To give an example, my hairdryer has a power of 2000 W, meaning that if I run it continuously for half an hour I will have consumed 1 kWh of electrical energy.  

Batteries store electrical energy, and their capacity is also generally listed in kWh. When they release their energy, they will do that with a specific power output that is measured in W. To give an analogy, the capacity of a water reservoir is measured in liters, while the flow is measured in liters per second. The capacity is analogous to the energy while the flow is analogous to the power.

The energy meter connected to our home's electrical panel measures the amount of energy consumed in kWh. Traditional analogical meters cannot be read remotely. Every so often the amount of energy consumed must be reported to the electricity provider to calculate the amount of money that needs to be balanced. Recently, Sibelga, Brussels distribution system operator, has started replacing the old meters with new [smart meters](https://www.sibelga.be/en/connections-meters/smart-meters) that can be read remotely and track the energy consumption every 15 minutes.

Smart meters are a technological requirement to go from the conventional energy system to a new energy system in which individuals can be at the same time producers and consumers (prosumers) of electricity. Without smart meters, it would be impossible, for example, to coordinate the sharing of electricity produced by rooftop solar across different apartments or  buildings.

Smart meters also represent a huge opportunity from a research point of view, because of the quantity of data that can be gathered and analyzed on the consumption patterns. This data can be employed to develop more efficient methods for energy allocation, for the coordination of different energy resources needed to cover the energy requirements, or for the prediction of different scenarios of energy procurements. As always with data collection, they also pose quite an important concern from a privacy point of view, and robust safeguides have to be put in place to avoid exposing sensitive information.
  
## The authorities

The electrical grid is an extremely complex system that is vital to sustain modern society (arguably one of humanity’s most complex achievements). Understandably, it features multiple layers of control and coordination to ensure its correct operation. On the European level, [ENTSO-E](https://www.entsoe.eu/) is the association that coordinates the national Transmission System Operators (TSOs) to ensure the security of the cross-border electricity flow and the integration of renewable energy.

In Belgium, the national TSO is [Elia](https://www.elia.be/), which manages the high-voltage transmission lines linking the production to the consumption, and responsible for the energy dispatching to ensure that production meets consumption at every second.

Before the electrical energy reaches private consumers, the voltage needs to be lowered to medium and low voltage levels (such as the 240 V we have in our homes). This is done through the distribution network, operated by the Distribution System Operators (DSO). In the Bruxelles region, [Sibelga](https://www.sibelga.be/en) represents the DSO in charge of ensuring the distribution of electrical energy to the individual homes.

[Synergrid](https://www.synergrid.be/nl/) is the sector association of the Belgian TSO and DSO, which act as spokesperson towards the Belgian and European policymakers. As such, it translates high level decisions into technical standards to ensure grid safety and reliability.

[BRUGEL](https://brugel.brussels/) represents the authority that oversees the electricity market in the Brussels capital region. It also regulates the incentives to photovoltaic generation through the issuing of green certificates.

Finally, the regional administration is also involved in shaping the energy system. [Brussels Environment](https://environnement.brussels/) is the public administration agency that oversees the energy and environmental policy of the capital region.
