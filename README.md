******************************************************************************************************************************
******************************************************************************************************************************

# Deceptive Visualization- Gun Sucides in US 

###### Date: 17th Nov 2017                                                                                                     
###### Tableau Visual: 

******************************************************************************************************************************
******************************************************************************************************************************


### I.	Project statement: 

**Motivation:**
The motivation for this project came from my earlier project that I have done on Mass shootings in the states. My main driving source for taking up this challenging project was to see that what are the underlying causes of so many mass shootings in the states and to prove or discredit the theory that the media has been talking about that the lenient gun laws are the root cause of people with or without criminal history killing innocent citizens without any cause.In my  My deception project I have tried to do something different but related to Gun Laws. I plan to analyze data on suicides in the states using Gun and see where it leads me. After finishing up the Project I hope to achieve a clear understanding of why such heinous crimes took place and are suicide related to gun laws in any way.

**Objective:** 
Today, data is become a driving force to make decisions  affecting millions of people. Since this is a deceptive project, I will try to show what the data actually tells its viewer and how can it be manipulated to something completely different and misleading to convince people otherwise.  

**Data:**
The data I have found for this project is from Centers for Disease Control and Prevention data base by using their wisqars platform.  But before extracting the relevant data, following filters have  to be applied:

1. In report type go to Incidents of Violence and check the field All Violent Incident Counts and Percentages
2. Select suicide in intent or manner of injury based on the abstractor
3. Select Firearm in cause or mechanism of the injury
4. Select All years of report for the report generation 
5. Select Spreadsheet as the type of report and submit 

* Link of the data set: https://wisqars.cdc.gov:8443/nvdrs/nvdrsDisplay.jsp


**Project plan:**
This project will be based on exploration rather than confirmation.

1.	Select a topic of interest 
2.	Find credible and reproducible data source 
3.  Analyze the data to come up with a claim 
4.  Add additional data to come up with a counter-argument 
5.	Make several intermediate versions 
6.	Critque the intermediate versions to come up with a final version 
8.	Descibe the final version and scope of improvement 
9.	Make a short video explaining the visual 

******************************************************************************************************************************

### II. 	Development Process:  

#### 1) Data wrangling:
Data wrangling steps have been written in the python notebook. In order to show the deception I had to find population for every states for every year from google and incorporate that in the python notebook.
The web query used for the population was, just replacing the state and year in question:
https://www.google.com/search?rlz=1C5CHFA_enUS726US727&ei=e8QOWs_wO8uN0wLd2IfYAg&q=population+of+state+in++Year&oq=population+of+state+in++year&gs_l=psy-ab.3...724.2953.0.3336.0.0.0.0.0.0.0.0..0.0....0...1.1.64.psy-ab..0.0.0....0.ePY34O6oGUk


#### 2) Approach:

For doing this deceptive visualization I  went through many articles studying about the gun violence and in particular suicides cases where some form of guns were used.  

**Audience:**

**Claim:** 

**Qualifier:**
The qualifier for this data is take in such a way that every group is being represented. There are top gun restrictive states and then there are the least gun restrictive States for the deceptive project.

**Data:**
The data is collected from cdc which did a federal funded study in the 7 states which were New jersey, Massachusetts, Maryland,Alaska, Oregon, Virginia and South Carolina from 2003 to 2014.The data is highly credible and contamination free. 

**Warrant:**



**Backing:** 

******************************************************************************************************************************

### III.	 Analyzing Intermediate Versions of visualization:

**Visualization 1:** 
<img width="565" alt="screen shot 2017-11-17 at 2 02 26 am" src="https://user-images.githubusercontent.com/25557540/32941948-5e580f9e-cb3c-11e7-98a7-563646519a0c.png">

* Pros:
1) This visual shows ranking of states from High to low based on Gun Restriction Law in their states
2) The layman opinion that we can form from this visual going forward is the most restrictive states should have less number of suicides using guns  

* Cons: 
1) The visual is incomplete and just shows the ranking based on which we can form different opinions 
2) More data is needed to start showing the what I want to the people to see 

**Visualization 2:**
<img width="1056" alt="screen shot 2017-11-17 at 2 07 32 am" src="https://user-images.githubusercontent.com/25557540/32941955-5f024b76-cb3c-11e7-8464-10d8251dc2e3.png">

* Pros:
1) This visual is way better than my previous visual as it starts telling us a story 
2) This visual is representing number of total suicides every year from 2003 to 2014 
3) It also shows the distribution of avg. number of suicides to let the viewers form and idea in terms of which state  has more average suicide rate 

* Cons:
1) The claim and  the visual still have no relation whatsoever. 
2) Something more can be done to better represent the data and show the objective of the visual 

**Visualization 3:**
<img width="1057" alt="screen shot 2017-11-17 at 2 44 55 am" src="https://user-images.githubusercontent.com/25557540/32943629-909ca06e-cb41-11e7-8341-02bc49419cc6.png">

* Pros:
1) This visual is again an extension of the previous visual and it has a trend!!!
2) The best thing about this is that we can see how the rates have change over the year in suicide rates 
3) Also the trend line indicates what the future holds for that state in terms of Gun Suicide if the relevant people don’t take any steps 

* Cons:
1) Lot of colors and can be done more simply 
2) Viewer might form an idea that is bad choice for a deceptive project as how can data be manipulated here 

**Visualization 4:**
<img width="1056" alt="screen shot 2017-11-17 at 2 03 51 am" src="https://user-images.githubusercontent.com/25557540/32941951-5e8f1336-cb3c-11e7-9375-7bb1c1f2000d.png">

* Pros:
1) This visual takes the most restrictive state and tries to represent Gun Suicides in that states
2) The main purpose here was to let the viewers know the average  suicide numbers  in the Most restrictive state.
3) This should make the viewer think if this is  just the suicide data than how would the visual look like if every gun homicide is included 

* Cons:
1) No trace of deception development 

**Visualization 5:**
<img width="1052" alt="screen shot 2017-11-17 at 2 04 41 am" src="https://user-images.githubusercontent.com/25557540/32941952-5eb3719a-cb3c-11e7-9cae-95e013a0b30e.png">

* Pros:
1) This visual takes the least restrictive state and tries to represent Gun Suicides in that states
2) Now the viewers can notice that the Suicides by Gun is more in a state that has lenient laws when it comes to firearms

* Cons:
1) Now seeing this visual the viewers might assume that lenient states have more suicides compared to restrictive states  

**Visualization 6:**
<img width="767" alt="screen shot 2017-11-17 at 2 05 21 am" src="https://user-images.githubusercontent.com/25557540/32941954-5ee3de5c-cb3c-11e7-8155-cba5201c4acd.png">


* Pros:

* Cons:





******************************************************************************************************************************

### IV.	Final data visualization:

![dashboard 1 1](https://user-images.githubusercontent.com/25557540/32945974-757d55ea-cb4a-11e7-92f9-c20bf83b112a.png)

#### Discusiion: 

**Visual 1:**
* In the final visualization, we can see that there is no actual trend between the suicide by firearm and the gun restrictiveness of the state
* Alaska has the least suicide death because compared to others as it does a large population as the other states in the study 
* Virginia is kind of neutral in gun laws likes to describe itself neither pro-gun law nor a pro no gun law kind of state. So people are free to buy guns and  when their mental states is not at its best they tend to shoot themselves
* The Next two states South Carolina and Virginia are two most lenient and pro No Gun law state and as it is evident from the visual, lot of people are taking their lives when they get depressed
* Now we look at the top three Pro-Gun Law States, and as we can see that they are in the middle of the scatter plot differing by small numbers. 
* Massachusetts, the third highest gun restrictive state has very few gun suicides which can make for a case that yes the law is preventing people to buy guns and shoot themselves
* New Jersey, and Maryland the 2nd and 4th most restrictive gun law states have also low gun suicides compared to their counterparts, bolstering the above claim.
* So far the audience might feel that the pro no gun law states have fewer suicides by guns then pro No Gun Laws states. 

**Visual 2:**


******************************************************************************************************************************
### V. Future Enhancements:

* Include more data from other states to form a better case and more concrete evidence 
* Add data From different Gun Violence sources such as Gun homicides, Mass shootings, robbery 
* Add data for the type of guns that were most commonly being used to see which firearms are causing more harm to the society 
* Include mental data to understand the underlying cause for these suicides 

******************************************************************************************************************************
### VI. References:

* http://www.slate.com/blogs/the_slatest/2015/10/07/gun_control_laws_by_state_oregon_new_york_texas_california.html
* https://wisqars.cdc.gov:8443/nvdrs/nvdrsDisplay.jsp
* https://www.cdc.gov/nchs/pressroom/sosmap/suicide-mortality/suicide.htm
* https://www.bjs.gov/index.cfm?ty=pbdetail&iid=5804
* https://www.usnews.com/news/best-states/articles/2017-05-24/database-reveals-striking-differences-in-how-guns-are-regulated-from-state-to-state
* https://www.theguardian.com/news/datablog/2011/jan/10/gun-crime-us-state#data
* https://www.statcrunch.com/app/index.php?dataid=1880699
* https://www.cdc.gov/nchs/pressroom/states/california/california.htm
* https://www.kaggle.com/walgemei/eda-the-usa-mass-shootings
* https://www.adn.com/alaska-news/article/study-suggests-connection-between-alaska-suicide-rates-higher-latitudes/2013/11/23/

******************************************************************************************************************************
******************************************************************************************************************************



