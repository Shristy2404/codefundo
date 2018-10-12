# codefundo
Repository for Microsoft Codefundo '18

#Idea 
Rescue operation during the time of disaster is a challenging task of utmost importance. However, unfortunately, little attention is paid to make it economically efficient and less error prone. It is often random and things are decided at the spur of the moment, the information is not conveyed properly and as a result, the whole process becomes highly inefficient. Rehabilitation camps during a calamity are subject to vulnerability too. For example, a relief camp set up during a flood might not be safe for a long time and this can result in a logistic nightmare. Apart from the vulnerability of the relief camp, there are numerous other factors that must be kept in mind while setting up a relief camp. Efficacy of the relief project and efficient allocation of resources are critical in adverse situations like these. 

We aim at identifying best suited probable points for setting up a relief camp. Our model would be capable of forecasting the viability of a given geographic coordinate. Further, it would help suggest best suited coordinates for setting up relief camps. The parameters considered while estimating these geographic points would be:

1. Distance from the affected region.
2. Probability of the relief camp getting affected by the calamity.
	2.1 Elevation from sea level.
	2.2 Distance from water body.
3. Ease of rescue.
4. Ease of transportation for food supply.
5. Cellular network strength.
6. Amenities and human settlements in vicinity.

The aforementioned parameters will be given appropriate weights to make an estimation of their suitability for setting up relief camp. The parameters may have other nested factors too. 

Using this model, a database for disaster prone areas based on previous years' data can be made (which will be stored in Azure.) 
For each area, there will be multiple indexes. For example, say for an area A, during floods,
Index 1 areas can be used for relief camps if the flood is predicted to be relatively less ravaging
Index 2 areas can be used in more grave situations and so on.
If such information is used and followed in times of disaster,

1. Rescue operations by military can be much more efficient
2. Amenities like food, medication etc. can be supplied in a better manner 
3. Citizens will be generally more aware about what to do in time of a disaster and thus better equipped to deal with it

We will attempt to update viability scores in real-time. We intend to use GIS tools for implementing this model. 
This is our basic idea and we plan on improving the idea for greater advantages once we actually start implementing it. 