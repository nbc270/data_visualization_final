Here is my (Nathan Caplan, nbc270) final project for the data visualization course I took this summer. I rendered my viz' in jupyter notebook using folium (leaflet backend) and plotly. In the end my notebook can be seen [here](https://nbviewer.jupyter.org/github/nbc270/data_visualization_final/blob/master/data_viz_final_project_images.ipynb) in case the notebook doesn't render in Github. My visualizations can be found on this [website](https://nbc270.github.io/data_visualization_final/).The buttons for the first viz do not show the fast backward, backward, forward, or fast forward buttons but they work in the order described from top to bottom. Also feel free to clone this repo and run the notebook for thre best way to see all visualizations. 

<a name="Challenge_2"></a>
Task 2
<iframe width="450" height="600" src='challenge_2.html'></iframe>
In this first visualization, we see a changing heatmap over a 24 hour period for missed pickups. This means each dot seen on the map a single ride where the driver did not end up picking up the intended rider. In order view such a dataset over space and time, it felt appropriate to do a heatmap over a street map of nyc (spatial) along with a time slider (time). The time slider allows one to view a continuous run and look at discreet hours. As seen, there are few missed rides in the early morning hours (2-6). During mid day, there are plenty of missed rides in mid town, particularly around Grand Central, Port Authority, Penn Station, and Times Square. As then slider moves into evening hours the clusters begin to shift south and around 10 PM Oct.5 -1 AM Oct.6th we see more missed pickups in West Village, East Village, Meeat Packing, and NoHo. These are all big going out regions. The slider buttons rendered poorly with iframe but follow in reverse to begining, reverse once, pause, forward once, and fast forward in top to bottom order.

<a name="Challenge_4"></a>
Task 4
<iframe width="800" height="600" src='challenge_4.html'></iframe>
In this second visualization, we have an interactive bar plot detailing number of violation rides given during a 24 hour period per each hour. As seen above, there are few violators during the early hours of Saturday. However, by 7 AM they begin an increase that doesnt peak until 1 PM, where is slightly decreases as the day goes on. What is incredibly noticable is the dramatic change between 1 AM on Saturday and 12 AM on Sunday. Though, both being "going out" hours, there's a stark difference between early Saturday and Sunday hours. This figure only shows aspects regarding time.

<a name="Challenge_8"></a>
Task 8
<iframe width="450" height="600" src='challenge_8.html'></iframe>
In the third visualization above we see line plot over a street map (spatial) indidcating the route of Vehicle ID 269. This vehcile was chosen as it's route was fairly easy to understand and allowed for a heatmap to be applied to indidcate change in location over time (time). Blue indicates earlier in the day and red indidcates later in the day. Therefor This driver started in Inwood and ended in Fidi. Quite a trip!
