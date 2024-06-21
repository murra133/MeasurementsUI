# MeasureModelConnect
### Project Description
The purpose of this project is to create an interface between the actively changing 3D model world and the slow construction world. The reason this is done is because every day project engineers spend countless hours in document control of hand written notes by field personnel. This process essentially waste time and makes documentation unreliable as it is prone to several avenues were human error can interfere with the accuracy of the data. We live in the 21st century and we have the tools readily available to automate most of the process. I will document the experiences as I videotape while this project is built. Code is private so will only be sharing demos.


### Video 1: Calculation of Shapes Available to Scrap Material

https://github.com/murra133/MeasurementsUI/assets/46013488/a2e58116-4bdf-49b0-9aa9-2a6774a99292

In the video, the user is selecting the different dimensions to be measured for the scrap wood (H|W|D). As the user measures, the phone receives the measurement and instantly distributes the measurement to the 3D model. The 3D model then uses Rhino Grasshopper (Visual Scripting) to plot and calculate the available shapes that can be cut from the scrap pieces. This is done in sync with the user taking measurements.


### Video 2: UI Walkthrough


https://github.com/murra133/MeasurementsUI/assets/46013488/a61e850c-2a21-40ca-aa23-63d1555fbdad


In the video one is able to see the current user interface. The user interface consists of a 3D model with a measurement list. Selecting a measurement will highlight the measurement in the 3D model and the list. Taking the measurement will update the value in both areas. One is able to seamlessly cycle between models and take measurements as needed.




