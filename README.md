# Personal Dataset Project on Philadelphia Murals 
Personal dataset project for Math-144-01: Foundations of Data Science
# Motivation 
Philadelphia is known as the "Mural Capital of the World." Growing up there, passing by a mural was an aspect of everyday life. Ultimately, I grew appreciative of how they beautified my neighborhood and walk to school. They also became a core driver of my educational experiences. In my senior year of high school, I wrote a research paper on murals in Philadelphia and painted my own in a childcare center. These experiences led me to focus my personal dataset project on murals in Philadelphia. I wanted to explore whether the data I collected and my analysis supported how impactful and prominient I believed murals to be in Philadelphia. In specific, I hoped to figure out what areas of Philadelphai were most densely populated with murals and whether they had any common or overarching themes. 
# Data Process 
I sourced my data by searching "murals" in "Philadelphia" on ![Google Maps](https://www.google.com/maps/search/murals+in+philadelphia/@39.9836562,-75.2319604,13z/data=!3m1!4b1?entry=ttu&g_ep=EgoyMDI1MTEzMC4wIKXMDSoASAFQAw%3D%3D). I manually entered the information into Excel. I choice to only use murals that included the artist's name, address, zipcode, and title. After exporting the data as a .csv file into R, I added two additional column. One wa the number of words in each title, which was used in my analysis later on. The other was the categories that I believed each mural title could be idenified as. 


# Visualization 
![Number of Murals by Zipcode and Artist](https://github.com/lsmollen/Livia-Personal-Dataset-Project/blob/main/000046.png) 

This bar chart shows the number of murals in each Philadelphia zipcode and how they are distributed among different artists. While most zipcodes have only one mural represented, 19107 has several. The area's high concentration of murals suggests that it may be a hotspot for public art in the city. However, the range of zipcodes reveal that murals can be found across Philadelphia. The variety of colors also show that many artists contribute to public art in Philadelphia. In contrast to the zipcodes, no particular artist is creating more murals than another. This suggests that the public art scene attracts many artists and is a flourishing, collaborative sector. 

![Number of Murals by Zipcode and Artist](https://github.com/lsmollen/Livia-Personal-Dataset-Project/blob/main/000042.png) 

This bar chart visualizes the number of murals that were collaboratively made or independent works. Eight of the murals in my dataset were created by one artist, while two were collectively made. Like the above bar chart, this emphasizes that there are several artists contributing to the public arts scene in Philadelphia. The two murals made by multiple artists reveal that murals foster teamwork and require hands-on hardwork. 

![Number of Murals by Zipcode and Artist](https://github.com/lsmollen/Livia-Personal-Dataset-Project/blob/main/000069.png)  

This bar chart shows the categories I placed the mural titles under. Three of the murals was not classified under any of the four categories, and were identified as "Other." Two of mural shared a title that related to nature: "Water Gives Life" and "Tree of Knowledge." While there were other categories, only one mural title belonged to each of them. 

# Analysis 
![Number of Words in Mural Title](https://github.com/lsmollen/Livia-Personal-Dataset-Project/blob/main/00002a.png) 
![Number of Words in Mural Title](https://github.com/lsmollen/Livia-Personal-Dataset-Project/blob/main/.png) 

For my analytical technique, I choose to conduct simple EDA. I created a boxplot and calculated the summary statistics of the number of words in each mural tile in my dataset. The boxplot and summary statistics revealed that the shortest title had only one word (“Legendary”), and the longest had five ("A Love Letter for You"). On average, the titles in my dataset contained around three words. I wanted to explore how much meaning could be derived from the titles and how this might impact a viewers' interpretation of the murals. By analyzing the number of words in each title, it was revealed how concise mural titles typically are, leaving viewers to imagine and interpret the artwork independently. 
