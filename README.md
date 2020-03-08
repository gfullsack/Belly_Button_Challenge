# Plot.ly Homework - Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria_by_filterforgedotcom.jpg)

In this Boot Camp Assignment, I builty an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

I used Plotly.js to build interactive charts for your dashboard.

* Created a PIE chart that uses data from the samples route (`/samples/<sample>`) to display the top 10 samples.

  * Used `sample_values` as the values for the PIE chart.

  * Used `otu_ids` as the labels for the pie chart.

  * Used `otu_labels` as the hovertext for the chart.

  ![PIE Chart](Images/pie_chart.png)

* Created a Bubble Chart that uses data from the samples route (`/samples/<sample>`) to display each sample.

  * Used `otu_ids` for the x values.

  * Used `sample_values` for the y values.

  * Used `sample_values` for the marker size.

  * Used `otu_ids` for the marker colors.

  * Used `otu_labels` for the text values.

  ![Bubble Chart](Images/bubble_chart.png)

* Displayed the sample metadata from the route `/metadata/<sample>`, with each key/value pair from the meta data JSON object on the page. 

* Updated all of the plots any time that a new sample is selected.

## Advanced Challenge Assignment

* Adapted the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the Weekly Washing Frequency obtained from the `/metadata/<sample>`route.

* Modified the gauge code to account for values ranging from 0 - 9.

![Weekly Washing Frequency Gauge](Images/gauge.png)

- - -

## Flask API

Used Flask API starter code to serve the data needed for your plots.

- - -
