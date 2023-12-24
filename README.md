
## Machine Learning Model for prediction of algal growth, using maritime observatory  

### Author: Dalit Roth Rosenberg  

**Introduction**
The marine microalgae are primary producers responsible for almost 50% of the Earth's oxygen and form the foundation of the marine food web. Understanding microalgae growth is crucial for comprehending global cycles and the interactions among marine organisms. However, other aspects, such as algal blooms, are also under intense investigation. Harmful algal blooms (HABs) are identified by the rapid accumulation and increased concentration of the microalgal population. These blooms, usually resulting from an excess of nutrients, significantly impact the environment. They can lead to a dramatic depletion of oxygen, reduced light penetration, and the release of harmful toxins affecting various trophic levels.

HABs pose a significant threat to coastal areas and are often associated with large-scale marine mortality events. Consequently, extensive studies on HABs are being conducted by the National Centers for Coastal Ocean Science. Scientists utilize various technologies to predict the probable formation of HABs, their locations, and their potential impacts.

Although the East Mediterranean Levant is highly oligotrophic (low in nutrients) and experiences fewer massive blooms, rapid algal growth does occur. Hence, understanding the biotic and abiotic factors triggering this extreme growth becomes valuable.

Our objective is to develop a model capable of predicting microalgae growth in the marine environment 24 hours in advance. Additionally, we aim for this model to explicitly explain essential factors (geophysical and environmental) influencing algal growth leading to blooming.

A proxy for algal levels is Chlorophyll A (chlA). ChlA, the primary pigment in all photosynthetic organisms, can be routinely monitored using sensors or remote sensing (satellite). These measurements indirectly indicate chlA concentration (ug/L). For our model, we'll utilize chlA data obtained by the Texas A&M - Haifa Eastern Mediterranean Marine Observatory (THEMO1) sensor, positioned at the edge of the continental shelf at approximately 125m depth (33.04°N, 034.95°E). THEMO1 generates data samples every 30 minutes from 32 to 40 sensors simultaneously.

A comprehensive description is provided in the BIDs Project protocol.  
The project codes are provided in the ipynb files. 
