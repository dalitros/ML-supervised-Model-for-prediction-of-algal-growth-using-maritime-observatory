
## Machine Learning Model for prediction of algal growth, using maritime observatory  

### Author: Dalit Roth Rosenberg  

**Introduction**
The marine microalgae are the primary producers that responsible for almost 50% of the earth oxygen, and the base of the marine food web. While microalgae growth is important to understand global cycles and the interactions between marine organisms, other aspects such as algal bloom are also being highly investigated. Harmful algal blooms (HABs) identified by rapid accumulation and increased concentration of the microalgal population. Blooming which usually occur due to excess in nutrients, affect the environment and may cause a dramatic depletion of oxygen, reduction in light and excretion of harmful toxins that may affect the whole trophic levels.   
HABs specially threatened coastal areas and are often associated with large-scale marine mortality events. Thus, HABs are being extensively studied by the National Centers for Coastal Ocean Science and Scientists use a range of technologies to predict where and when HABs are likely to form and how they will affect the areas where they occur.
While the East Mediterranean Levant is highly oligotrophic (low in nutrient) and massive blooms are less frequent, rapid algal growth indeed occurs. Thereby, understanding the biotic and abiotic factors leading to this extreme growth may be valuable.    
Our goal is to build a model that can predict the growth of microalgae in the marine environment 24 hours in advanced. In addition, we hope that this model will explicitly explain some of the essential factors (geophysical and environmental) that influence algal growth leading to blooming.   

What is known to influence the outcome?  
-It is known that algae blooms are influenced by high nutrients availability with optimal temperature and light conditions. 
-Increased nutrient loading from human activities are linked to severity of blooming frequent. 
-HABs are a predictable seasonal occurrence resulting from coastal upwelling, a natural result of the movement of certain ocean currents.
-Phytoplankton growth varies seasonally. In high latitudes (East Mediterranean Sea), blooms peak in the spring and summer, when sunlight increases and the relentless mixing of the water by winter storms subsides.
-blooming may be genre-specific and be dominant during different time of the year.  
-Winds play a strong role in the distribution of phytoplankton because they drive currents that cause deep water, loaded with nutrients, to be pulled up to the surface. 

How do I define the outcome(s)?
A proxy for algal level is Chlorophyll A (chlA). ChlA is the main pigment in all photosynthetic organisms and can be monitored routinely by sensors or remote sensing (satellite). These measurements can be indirectly shown as chlA concentration (ug/L). For our model formation I will use the chlA measurements that were obtained by the Texas A&M - Haifa Eastern Mediterranean Marine Observatory (THEMO1) sensor (…), which is positioned at the edge of the continental shelf at ~125m depth (33.04°N, 034.95°E). THEMO1 produces data samples simultaneously from 32 40 sensors every 30 min.  

Generally, environmental models use signals such light, temperature and nutrients to predict the seasonality of algal bloom in a scale of months and seasons. However, THEMO1, which provides a high resolution of meteorological and geophysical data (e.g. temperature, humidity, turbidity, salinity, waves intensity, winds speed) 
