# P-Wind (Wind Energy Power Prediction) 🎐

P-Wind App helps in predicting the energy output of wind turbine based on weather conditions. Our app can forecast the energy produced and plots it beautifully in a time series for visualization.The user can see the estimated energy of current hour as well as of 72 hours in future.

## Getting Started

App Stays at

[**My P-Wind App**](https://immense-reef-43943.herokuapp.com/)

### Prerequisites

* Node-RED
* IBM Watson Studio
* Watson Machine Learning
* Open Weather API
* [Wind Turbine Scada Dataset 2018](https://www.kaggle.com/berkerisen/wind-turbine-scada-dataset)


### Installing

To get the application up and running follow the below steps:

* Import the flows into the NodeRed flow editor.
* Create a project inside Watson Studio service.
* Inside the project import the dataset and the notebooks.
* Copy the required service credentials of Watson Studio  and Machine Learning Services and update them into the NodeRed nodes.
* Deploy the NodeRed flow.

![alt text](https://i.ibb.co/sH6t26c/2-Current-Pred.png)

## Running the tests

On the landing page of the app(see above), you can click on refresh to fetch the current wind speed and directions and pass it onto the model to make predictions for those parameters. 

If we click on the sidebar to go to Power vs Wind group we'll see a time series like this:

![alt text](https://i.ibb.co/N6cRtHw/3-Current-Pred.png)

Here we fetch data(speed and direction) for next 4 days at an interval of 3-3 hours and plot it in the time series. 


To see the optimal power generation time simply click on REFRESH and it notifies us with the optimal time to produce power.

![alt text](https://i.ibb.co/YfJS0fv/4-Current-Pred.png)


## Deployment

To deploy this app we just need to link the Dashboard UI address.

## Built With

* [Node-RED](https://nodered.org/docs/) - Developing the dashboard
* HTML/CSS/JavaScript - Creating the webpage
* [IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - Used to create notebook
* [Open Weather API](https://openweathermap.org/api) - For fetching current wind speed and directions

## Authors

* **Jashmin Mishra** - [Jashmin](https://github.com/jashminmishra1 )
* **Gurudeep Singh** - [Gurudeep](https://github.com/gudii16 )
* **Aman Kumar** - [Aman](https://github.com/bullet-ant)

## Acknowledgment

IBM Hack Challenge 2020 Bootcamps:
* [Nodered](https://www.youtube.com/watch?v=WUB6gySRjQg)
* [Cloudant](https://www.youtube.com/watch?v=J9xtw0zjDLY&t=6203s)
* [Machine Learning](https://www.youtube.com/watch?v=Tv_5DHwlYdE)
* [Notebook Deploy and NodeRED Integration](https://www.youtube.com/watch?v=flQ2-FVxPng)

## License

This project is licensed under the MIT License
