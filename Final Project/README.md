
## **Rating Recorded Fitness Activities According to Data Collected by a Smartwatch**

*This project is for the partial fulfillment of the requirements of EE 629 - Internet of Things*

As someone who uses smartwatches in their daily life and wants to get physically fit, I record a lot of my fitness activities using Garmin Vivoactive HR. As a fitness watch launched in February 2016, it is not as capable of giving important insights like a brief comparison with past activities. I decided to analyze the data collected by my watch and see how well I've performed over some time.

### Connection with IoT

Smartwatches and IoT are directly related. The watches have sensors that record data like heart rate, average pace, steps taken per day, and more. All of this data is stored in the watch provider's server. This data can be easily exported by logging into your account. As mentioned before, the watch used is relatively old, so I just used the data collected during the activities for analysis.

### Methodology

The basic outline followed by the project is:

  - Data Cleaning (to remove the unwanted or null columns in the CSV file).
  - Splitting the recorded activities into the type of activities (walking and running in this case).
  - Establishing rating criteria.
  - Analysing walking activities.
  - Analysing running activities.

### Data Visualization

#### Walking Data

1) Calories Burned per Minute versus Pace

![Calories burned per minute versus pace](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/cal_v_pace_walk.png)

2) Calories Burned per Minute versus Moving Time (duration of the activity)

![Calories burned per minute versus Moving Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/cal_v_min_walk.png)

3) Pace versus Moving Time (duration of the activity)

![Pace versus Moving Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/pace_v_min_walk.png)

4) Ratings of all the Walking Activities Over Time

![Ratings of all Walking Activities Over Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/walk_ratings.png)


#### Running Data

1) Calories Burned per Minute versus Pace

![Calories burned per minute versus pace](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/cal_v_pace_run.png)

2) Calories Burned per Minute versus Moving Time (duration of the activity)

![Calories burned per minute versus Moving Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/cal_v_min_run.png)

3) Pace versus Moving Time (duration of the activity)

![Pace versus Moving Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/pace_v_min_run.png)

4) Average Stride Length versus Pace

![Stride Length versus Pace](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/stride_v_pace.png)

5) Running Cadence versus Pace

![Cadence versus Pace](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/cadence_v_pace.png)


6) Ratings of all the Running Activities Over Time

![Ratings of all Running Activities Over Time](https://github.com/ragwantsadrag/raghav-daga-iot/blob/main/Final%20Project/run_ratings.png)


### Rating Criteria

#### For Walking Activities

2 points each to Calorie Burn Rate and Moving Time, and 1 point to Average Pace.

#### For Running Activities

1.5 points each to Cadence and Average Pace, and 1 point each to Stride Length and Moving Time.

#### Changes to Rating Criteria

The rating criteria was too harsh as the "best" activity got a maximum of 3.65 out of 5 points. So, the ratings were then scaled by giving the best activity for a category 5 and scaling the rest of the activities in that category accordingly.



*Still updating. Thank you for your patience!*
