# NYC_Citibike

# Overview
I used Tableau as a visulatization tool that helped me present my findings in an appealing way. I also used Pandas to change the 'tripduration' column from an integer to a datetime datatype. Then using the converted data type I created a set of visulatizations to: 
  Show the length of time that bikes are checked out for all riders and genders
  Show the number of bike trips for all riders and genders for each hour of each day of the week
  Show the number of bike trips for each type of user and gender for each day of the week.
  
# results
First, using pandas in jupyter notebook, I was able to convert the data type so that I could create visualizations to present my findings. The first visualization that I needed to create was the Checkout Times for Users: https://public.tableau.com/app/profile/karis2520/viz/CheckoutTimesforUsers_16322840775530/CheckoutTimesforUsers?publish=yes

![Checkout Times for Users](https://user-images.githubusercontent.com/85076259/134289501-e2f43af9-4850-4ffa-88db-f5a7a6cd6106.png)

Then I was prompted to create the Checkout times by Gender: 

![Checkout Times by Gender](https://user-images.githubusercontent.com/85076259/134289706-a1ef21ff-2079-4da2-8e73-d51059d54282.PNG)

I also created a heatmap that shows Trips by Weekday per Hour: 

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/85076259/134289826-ec5e9c59-dda3-4cee-9469-335a90489639.png)

To visualize further data I created Trips by Gender and Weekday per Hour: 

<img width="1006" alt="Weekday trips by gender per hour" src="https://user-images.githubusercontent.com/85076259/134290034-632d850c-0fa9-4c4b-b3f6-6b461d1be499.png">

And Lastly, a heatmap that shows the number of bike trips for each type of user and gender for each day of the week: 

<img width="1147" alt="User Weekday trips by gender" src="https://user-images.githubusercontent.com/85076259/134290164-9154a02d-6a86-4de7-8471-42faf5ab9c39.png">

# Summary
I found that the largest group of users were males and the data shows that the number of rides are higher during rush hours of business days which indicates that riders could be riding to and from work and home. I also noticed that Non subscription users of all genders prefer to ride during the weekends and during daylight which indicates a preference for leisure riding. 

A visualization on user's age would likely give more insight on if riders are going to and from work and home. Also, a visualization that shows the data relationship between age and travel duration would give more insight on if riders are leisurly riding or if they ride as a mode of transportation. Older ages are most likely riding for leisure but we can't tell. 
