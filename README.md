# Subway-Station-Security-Check-Simulation

## Background
In Beijing, during peak hours, there are always long lines (in hundreds of meters) outside of security checks of subway stations. The subway is especially crowded in Fuxingmen Station, the interchange station of Line 1 and 2. Though Beijing now has 19 metro lines, line 1 and 2 still play crucial roles in transporting people in downtown areas. Long time of waiting in lines during peak hours results in huge inefficiency.


## Introduction
We want to understand and simulate the arrival times and screening times during peak hours, in order to bring insights and recommendations to Beijing Metro Center to reduce the crowdedness and amount of waiting time during peak hours. Based on our simulation of arrival and security check times of Fuxingmen Station, we could recommend the number of security guards needed, size and number of baggage check screening, as well as better security check process, in order to reduce the amount of waiting time during peak hours. As Fuxingmen Station being one of the most crowded subway stations in Beijing, our simulation could be applied to all other subway stations in Beijing.


## DataSet
We gathered our data based on our own observation and investigation of Fuxingmen Station during the peak hour of 5:30 pm to 6:30 pm.

Time:
● 5:30 pm - 6:30 pm (T=3600s)

Subway Station:
● 2 entrance (A and B) for Line 1.
● For every 3 minutes, there will be about 200 people exchange line from 2 to 1.
● There is only one security track scanner for bags per entrance.
● There are two security checkpoints for people per entrance, one for people carrying bags, one for people without bags.
● If a person carries bags, they will go through body check during their bag checking.

Arrival per entrance:
● 60 arrivals per minute.
● 40% of people have large bags that needs to go through the track scanner.

Security track:
● 20s for one bag go through the security track.
● 2s for one person to be checked at the security checkpoints.
● Maximumly 5 people can put down and get their bag at the same time on the track.

Subway Platforms:
● It takes 90s Security checkpoint to walk to the platform.
● On the platform, there are two subways coming from opposite directions every 3 minutes.
● Each subway train has 24 doors and 12 compartments.
● Each door has a maximum capacity of 30 people waiting in the line.



## Contributors
Contributors: Yingying Deng, Zheyuan Hu, Ruitong Xu, Yao Yi

UNIs: yd2547, zh2447, rx2187, yy3097
