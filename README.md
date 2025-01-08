SUPSI 2024-25  
Data Visualization course, M-D3202E  
Teacher Giovanni Profeta


# Is Boston a safe place?
Authors: [Bernacchia Alessia](https://github.com/AlessiaBernacchia), [Pioda Tommaso](https://github.com/Thetommigun432), [Villani Giacomo](https://github.com/DownToTheGround)

[Is Boston a safe place?](https://github.com/AlessiaBernacchia/data-visualization-crime-project)


## Abstract
This project explores **the distribution and severity of crimes across Boston's various districts**, providing valuable insights for **residents and visitors**. By analyzing crime data collected over the past four years, we identify key patterns in criminal activity, including the most critical times and areas for safety.    
Our findings reveal that the most critical time for safety in Boston is around 5 PM, when crime rates peak. Districts such as Roxbury (B2), Dorchester (C11), and South End (D4) are identified as the most problematic, with higher concentrations of serious and medium-level crimes. In contrast, Charlestown (A15) emerges as a model of safety and stability, thanks to its active community, historical landmarks that enhance surveillance, and successful urban redevelopment efforts.    
Despite the higher crime rates in certain districts, all areas of Boston offer unique cultural and historical attractions that should not be overlooked. For those seeking a peaceful and secure environment, Charlestown stands out as an ideal destination, embodying a perfect blend of safety and charm.    
This project **underscores the importance of understanding crime patterns to navigate the city more safely and highlights the potential for positive change through community engagement and urban development**.

## Introduction
Our research focuses on the distribution of crimes in Boston, aiming to identify the safest areas and the best times to explore the city. 
While pinpointing precise answers to these questions is challenging, we concentrated on illustrating crime trends and their spatial and temporal distribution. 
This approach provides a clear overview of the areas and times to avoid.The main questions driving our research were aimed at understanding which parts of Boston are more prone to criminal activity. To achieve this, we analyzed a dataset containing information about crimes, including the type of crime, the day and time it occurred, and its geographic location.
This study is particularly valuable for residents of Boston, tourists, and individuals considering moving to the city. It serves as a practical guide to better understand the patterns of crime in Boston and make informed decisions about safety.

## Data sources
We used a dataset from Kaggle (URL: https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston) that includes data from the Boston Police Department over a four-year period. This dataset provides a detailed record of all the crimes the police handled in Boston, categorized by police district.

## Data pre-processing
For the Preporcessing part look the file cleaning_dataset.ipynb, there you will find all the modification we did to the dataset in order to clean it and shape it as we wanted.

## Data visualizations
Sed enim ut sem viverra aliquet eget sit. Iaculis at erat pellentesque adipiscing commodo. Et pharetra pharetra massa massa ultricies mi quis hendrerit dolor. At tempor commodo ullamcorper a lacus vestibulum sed arcu. Ipsum faucibus vitae aliquet nec ullamcorper sit. Tempus quam pellentesque nec nam aliquam sem et tortor. Turpis egestas sed tempus urna et pharetra pharetra massa. Ridiculus mus mauris vitae ultricies leo integer malesuada nunc vel.

### Linechart
This graph shows us the average trend in the number of crimes in Boston during the day. 
On the X-axis we have the hour of the day, while on the Y-axis we have the number of crimes committed in Boston.
This graph is the result of a daily average over the 4 years of data we had available. As you can tell, the most dangerous time of day is around 5:00 p.m., while the quietest time is during the night from 03:00 to 06:00 in the morning.

[<img src="assets/images/03.png" width="800" alt="Placeholder image">]()

### Maps
These maps illustrate how crimes are distributed across Boston, categorized by their level of severity. They provide a valuable visual representation of which police districts experience higher crime rates.The crimes are divided into three levels of severity:  
Low severity (UCR Part 03), Medium severity (UCR Part 02), High severity (UCR Part 01),
While the Boston Police Department typically classifies crimes only as UCR Part 01 and UCR Part 02, we introduced a third category (UCR Part 03) to include very low-level crimes, ensuring a more detailed representation of crime types.
In these maps, greater saturation indicates a higher number of crimes recorded in a particular district over the four years covered by our data. From this graph we see that the police districts with more crimes are the ones nearer the city center, while the farther have a lower crime rate. This could be the result of many possible indicators like the demographic distribution or others socioeconomic factors but we dont have the data to discuss this Hypotesis.

[<img src="assets/images/04.png" width="800" alt="Placeholder image">]()

### Bar Plot
The bar plot illustrates the number of crimes committed in each police district over a four-year period.
This visualization is particularly useful for understanding the total number of crimes recorded in Boston during these four years. From the data, it is evident that most of the crimes fall under the UCR Part 03 category, which represents low-severity offenses.
The police districs with the highest number of crimes are: Roxbury (B2), Dorchester (C11), and South End (D4), while the lowest one is Charlestown (A15). Is important to notice that the police districts with the higest number of crimes are the one nearer to the city center while the ones further away are the ones with a lower level of criminality. This could suggest us that the crime rate is moslty affected by the amount of people living in a certain area but we do not have the data to confirm this Hypotesis.

[<img src="assets/images/04.png" width="800" alt="Placeholder image">]()

## Key findings
Summarizing the insights from the data, we conclude that it is advisable to avoid police districts Roxbury (B2), Dorchester (C11), and South End (D4), particularly around 5:00 PM. Generally, areas farther from the city center tend to be safer. While the data might initially suggest that Boston is a dangerous city, a closer analysis reveals otherwise. 
Considering that crime peaks at about 5 crimes per hour (mostly not violent) in a city with over 650,000 residents, Boston is not as unsafe as it might seem.
It is neither the safest nor the most dangerous city in the world. 
We simply recommend exercising caution a bit in the afternoon, especially near the city center.

## Next steps
The possible next steps could be centered on the motivation over why those districts are the ones that have higher crime rates.
Before we Hypotised that this fact could be related with the demografic distribution of the city itself, but there are many other possible different reasons.
The research is not really focussed on "why some places are better than others" but more on which ones are safer with respect to the others.
Perhaps even asking directly the city of Boston, or others, if there are aspects they would prefer to have evaluated in order to draw conclusions to improve the safety of the city. The possibilities are many and very disparate from one another.
