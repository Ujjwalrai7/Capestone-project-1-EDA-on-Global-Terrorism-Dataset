# Capestone-project-1-EDA-on-Global-Terrorism-Dataset                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           Introduction                                                                                                                                                            Exploratory Data Analysis (EDA) is a process of examining and analyzing data to summarize its main characteristics and uncover patterns, trends, and insights. In the context of global terrorism, EDA can provide valuable insights into the nature and patterns of terrorist attacks worldwide, helping us understand the evolving threat of terrorism and informing policy decisions aimed at preventing and mitigating its impact. Global Terrorism Database (GTD) is one of the most comprehensive and widely used datasets on terrorism. It contains information on terrorist attacks worldwide from 1970 to 2017, including the date, location, type, and severity of the attack, as well as information on the perpetrators and victims involved. The dataset also contains information on the weapons and tactics used in the attack, the targets of the attack, and the group or ideology behind the attack.Given the vast amount of data contained in the GTD, EDA is an essential step in understanding the data and extracting meaningful insights. By visualizing the data, exploring patterns and trends, and identifying relationships between variables, we can gain a better understanding of the nature and patterns of global terrorism. In summary, EDA on the GTD is a critical step in analyzing and understanding the data, providing valuable insights into the evolving threat of terrorism and informing policy decisions aimed at preventing and mitigating its impact.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   Problem Statement                                                                                                                                                        The problem statement for conducting EDA on the Global Terrorism Database (GTD) can be framed as follows                                                               Specifically, the analysis aims to answer questions such as:                                                                                                                     
What are the overall trends in terrorist activity over time?                                                                                                            
Which regions of the world are most affected by terrorist attacks, and what are the characteristics of these attacks?
What types of weapons and tactics are commonly used in terrorist attacks, and how have these changed over time?
What are the demographic characteristics of the perpetrators of terrorist attacks?
Can we identify patterns in the data that may be useful for predicting and preventing future terrorist attacks?The goal of this analysis is to provide policymakers, security agencies, and the general public with a better understanding of the nature and patterns of global terrorism, as well as insights that can inform policy decisions aimed at preventing and mitigating the impact of terrorist attacks.                                                                                                                                                                                                                                                                                                                                                                                                                                            Introduction to Dataset                                                                                                                                                  The global terrorism dataset contains 181000 rows and 135 labels the major columns contains the information such as eventid, year, month, day, country, city province/state, region, of attacks held all over the world. It also contains columns such as killed and wounded personalities in a particular attack.                                                                                                                                                                                                                                                                                                                                                                    Data Manipulations                                                                                                                                                      I have just replaced the null values of the killed and the wounded columns with 0 and also introduced a new column called casualties which is the sum of killed and the wounded people of any attack. Also I have tried to extract some of the insights such as which year had the most no of attacks which country has faced the most no of attacks which region and the city is the hotspot for terrorsist attacks etc. Let's try to undertand the insights of the analysis through graphs and visualisation.                                                                                                                                                                              Few Graphs for Data Visualisation                                                                                                                                      I have used matplotlib, seaborn & plotly libraries to draw the various charts such as line chart, pie chart, bar graph, Histogram, correlation Heatmap & Pair plot etc.  ![newplot](https://user-images.githubusercontent.com/125723652/219847937-33174a99-7630-4d61-8183-801ab419b32e.png)                                                                                                                                                                                                                              The above chart represents the trends of no. of. attacks by any terrorist groups all over the globe.                                                                    the insights that can be generated from the above chart is that** Taliban** is responsible for most of the attacks across the globe which is followed by ISIL & SL groups respectively.                                                                                                                                                                                                                                                                                                                            ![newplot (1)](https://user-images.githubusercontent.com/125723652/219848243-f24ac1f7-be49-48d2-8d0e-91aabb998063.png)                                                  The above Bar chart extracts the information on analysis of attacks on yearly basis.                                                                                    The insights that can be generated from the above chart are that there an increase of terrorist attacks since the year 2005 and the year 2014 has faced the most no of attacks till 2017.                                                                                                                                                                                                                                                                                                                              ![newplot (2)](https://user-images.githubusercontent.com/125723652/219848392-ce269902-ad51-4c54-b0f9-33c9c5a6579d.png)                                                  The above graph gives the insights of most attacked provinces in India                                                                                                  The insights from this chart are Jammu and Kashmir is the most targeted province of India followed by Assam, Manipur,Punjab Jharkhand etc.                                                                                                                                                                                                                                                                                                                                                                              Conclusion                                                                                                                                                                                                                                                                                                                                      The conclusion from the data analysis can be stated as The frequency of terrorist attacks has varied over time: The EDA shows that there have been an increase in the terrorist attacks after 2005 . This can provide insights into the evolution of terrorism and the effectiveness of counter-terrorism measures. Certain types of targets and attack methods are more common: The EDA reveals that certain types of targets (e.g. Private Citizens & Property, military personnel, police officials ) and attack methods (e.g. bombings, armed assaults, hostage taking) are more commonly used by terrorists. Terrorism can have a significant impact on human life and infrastructure: The EDA show that terrorist attacks have resulted in numerous deaths of 411868 people and injuries to 523869 people, as well as damage to infrastructure and economic activity. The EDA also depicts the information about the most effected contries such as Iraq, pakistan, Afghanistan which have faced the most no. of. terrorist attacks.
