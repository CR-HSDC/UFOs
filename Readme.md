# UFO Sightings Analysis

### **Overview of the UFO Sightings Analysis**
The purpose of this project is to provide a filter menu system for a large dataset of UFO sightings. Data can be filtered by Date, City, State, Country and Shape.

Use of the filtering tool is explained in the "Results" section below.

The webapp is deployed at the following location: 
https://cr-hsdc.github.io/UFOs/

### **Results**

 * **Use of the Filtering System:**

 1) Upon loading of the webpage, the entire dataset is loaded (111 rows). Placeholder search terms are in place.
 
![Figure 1](https://github.com/CR-HSDC/UFOs/blob/main/resources/1_FullData.png)
**_Figure 1_:** Full Dataset displayed on loading
 
 2) Data is successively filtered as each criteria is applied. The worked example in proceding steps may be used to filter results to required criteria.
 
 3) Apply Date of 1/1/2010 (This filters results to 34 rows of data, not all shown)

![Figure 2](https://github.com/CR-HSDC/UFOs/blob/main/resources/2_ApplyDate.png)
**_Figure 2_:** Apply Date Filter

 
 4) Apply State of "ca" (This filters results to 16 rows of data, all shown)
 
![Figure 3](https://github.com/CR-HSDC/UFOs/blob/main/resources/3_ApplyState.png)
**_Figure 3_:** Apply State Filter
 
 5) Apply Country of "us" (This filters resulsts to 16 rows rows of data, all results from step 4 were located in US)
 
![Figure 4](https://github.com/CR-HSDC/UFOs/blob/main/resources/4_ApplyCountry.png)
**_Figure 4_:** Apply Country Filter

 6) Apply City of "la mesa" (This filters results to 2 rows, all shown)

![Figure 5](https://github.com/CR-HSDC/UFOs/blob/main/resources/5_ApplyCity.png)
**_Figure 5_:** Apply City Filter
 
 7) Apply Shape of "light" (This filters results to single row, all shown)

![Figure 6](https://github.com/CR-HSDC/UFOs/blob/main/resources/6_ApplyShape.png)
**_Figure 6_:** Apply Shape Filter

 

### **UFO Sighting Analysis Summary**



**Drawback of this design:**

A drawback of this current design is that the results cannot be filtered by the duration of the sighting. This is significant, as length of sightings time could be related to a sighting's veracity.

**Recommendations for future designs:**

  * Implementation of "Duration" filter; filtering by range of durations (e.g. > 5min, 5 to 10 min etc.) would alllow that specific subset to be reviewed.
  * Filtering on the comments section by a string search; sightings with specific criteria (e.g. comments mention hovering) to be reviewed. This filter would check for the exisitence of a specific string within the entire comment and return rows where comments contain that string.
	




