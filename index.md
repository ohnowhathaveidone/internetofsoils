---
layout: default
---

# Welcome!

Welcome to the Internet of Soils project page!

This project aims to develop low cost sensor nodes for long-term monitoring of ~soil~ ~moisture~ whatever you need moitored in remote areas. We will provide an open source design that will allow you to build your own nodes and to modify them to your own needs. Our primary focus are soils in protection forests and trees in urban areas, but (as long as it's legal and you don't hurt anyone) you are free to stick a sensor wherever you like.

## Project history, status & roadmap

We deployed an alpha version of our sensor at a site in Zollikofen (CH-BE). [Here](http://86.119.41.87:3000/dashboard/snapshot/6U7bzUOIN1Sz8jtWq3N0pNmtaTdS7YJt) you can see a sample of the data we record.

In November 2023, we deployed eight sensors in a protection forest near Martigny (CH-VS). In May 2024, six out of them were still sending data, while one was hit by a falling branch soon after installation and another one seems to have run out of energy. Forests are not the most suitable area to harvest solar power - trees not only protect from natural hazards, but also from sunlight. To make things worse, our test site is situated on a steep slope facing north. On the upside, we get to test the guts out of our devices in properly suboptimal conditions. 

We currently redesign some of the peripherals for the next monitoring project! [The Mobile Urban Green (MUG)](https://www.bfh.ch/en/research/research-projects/2023-527-998-470/) aims to lay the groundwork to better understand the positive effects of trees in urban areas and the suitability of different tree species for the purpose. While some work is necessary to adapt our solution to other types of sensors, the ability to reuse the backbone of the project gave us a proper boost to get going fast. 

## Prototype deployment

Click [here](./protopics.html) to see our prototype deployment.

## Deployment in Martigny  

Some impressions of the test site are [here](./martigny.html). 

## System architecture

Click [here](./sysarch.html) to have a look at the architecture behind the sensor node its communication.

## How do I build a sensor myself?

![wherePlans](./assets/img/whereplans.png)
##### Fig. 1: Where plans for build?

We did originally plan to release our design and the accompanying code to the public. The MUG Project proved that the solution was well adaptable to situations outside of the initial use case, however, a number of changes to the sensor node design were still necessary. Simply publishing instructions on the soil moisture sensor nodes would probably not generalize well for other applications. We will therefore take some time later this year to produce and publish a flexible reference design that can be used as a basis for other projects. 

## Contact

Do you have a question or a comment? Do you want to build your own sensor nodes and don't know where to start? Feel free to contact us using the coordinates below!

|Who?          |Does what?                |Talk to us!|
|:-------------|:-------------------------|:------|
|[Christine Moos](https://linkedin.com/in/christine-moos-515585183) |Forest Science            |christine.moos@bfh.ch|
|[Estelle Noyer](https://noyerestelle.wordpress.com/) |Calibration, data analysis|estelle.noyer@bfh.ch|
|[Nikita Aigner](https://github.com/ohnowhathaveidone) |Confused Technology Officer |nikita.aigner@bfh.ch|
|[Lennart Becker](https://www.linkedin.com/in/lennart-becker-4425ba236/) |Chief Making Officer |lennart.becker@bfh.ch|

## Acknowledgements

We want to thank [Bern University of Applied Science](https://www.bfh.ch/en/) for financially supporting this project in 2023 within the [BFH Transversal](https://www.bfh.ch/de/aktuell/news/2022/bfh-foerdert-interdepartementale-forschung/) program.
