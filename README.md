# Night-Time-Lights
This repository contains code developed by Somdeep Kundu, PGD NHDRM 2022-23, Indian Institute of Remote Sensing, Dehradun, to visualize developmental changes using Night Time Light (NTL) data.



Colour is indeed a captivating aspect of our perception, allowing us to interpret the world around us and find beauty, joy, and valuable information. When it comes to nighttime imagery, the VIIRS sensor stands out from most other optical satellites, capturing the radiance of lights during the dark hours. In this context, I would like to introduce a fascinating project that utilizes Night Time Light (NTL) data from VIIRS to visualize developmental changes over time. This dataset allows for a comprehensive assessment of changes in light intensity over time, offering valuable insights into developmental trends and urban growth.

To begin with, the code loads three distinct nighttime image datasets from different years: 2014-15, 2017-18, and 2021-22. These images correspond to different time periods and will be used to visualize the changes in light over the years. The VIIRS sensor captures the average radiance of lights during these specific time frames.

![image](https://github.com/zomm0095/Night-Time-Lights/assets/62704009/1b99351e-47e6-4856-863d-624229eb750c)

To create a visually informative representation of the data, a unique color scheme is employed. Specifically, a color progression is defined from red to blue. In this progression, red signifies older developments, while blue denotes newer ones. By using this color spectrum, the visualization aims to highlight temporal trends in urbanization and infrastructural changes.

The code then proceeds to select and process the nighttime images for each year, computing the median radiance for each period. This step is crucial to reduce any potential noise or outliers in the data, ensuring a clearer representation of urban areas' light intensity. With the median radiance values obtained for the years 2014-15, 2017-18, and 2021-22, the code generates an RGB composite image. The RGB composite combines the three images into a single representation by assigning each image to a specific color band: red for 2014-15, green for 2017-18, and blue for 2021-22. This composition effectively presents the developmental changes over time in a visually intuitive manner.

![image](https://github.com/zomm0095/Night-Time-Lights/assets/62704009/c538b7ea-1f2e-48dc-adaf-310b31309fbc)

The final visualization, known as the 'RGB composite image', is then added to the map display. The image showcases the areas illuminated in different colors, with red representing places that were brightly lit during 2014-15, green representing those during 2017-18, and blue representing those during 2021-22.

However, some areas may appear white in the RGB composite. These regions are of particular interest as they exhibit consistent and continuous illumination throughout the entire temporal dataset. In other words, these areas have remained lit up over all three years, indicating stable development or ongoing activities.

![image](https://github.com/zomm0095/Night-Time-Lights/assets/62704009/a2f7fad5-40d6-4990-b686-c4594aa8f56f)

On the other hand, the presence of blue lights in the composite image signifies new developments. These are areas that experienced increased illumination between April 2021 to April 2022, highlighting rapid urban expansion and infrastructural growth in those regions.

in the end, the VIIRS Night Time Light data and the RGB composite visualization provide a powerful tool to monitor and analyze developmental changes over time. The code developed by me, Somdeep Kundu offers an insightful and visually compelling perspective on the evolution of urban landscapes, demonstrating how the mixture of colors can indeed grant us a unique perception of beauty, joy, and valuable information embedded in the changing urban fabric.

This code is free to use, change and reporoduce.. if you like it please star it, ot will act like encouragement, and fell free to ask me any questions.. My mail id somdeepkundu@gmail.com
happy learning.. 🌍🛰️❤️



![image](https://github.com/zomm0095/Night-Time-Lights/assets/62704009/91fa52a5-ced1-44fc-b9b2-436bc2f3ed9d)

