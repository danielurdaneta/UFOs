# UFOs

The purpose of this project was to create a web application that provides UFO data so that the user can conduct their own research. This web application has different functions, at the top of the page there is a navigation bar that the user can click to refresh the page, there is also a short article that exposes the question that humans have been asking for thousands of years "Are we alone in the universe?", at the bottom of the page there is a table with data on UFO sightings and filters that you can use to narrow your search.

We made this using JavaScript, Html and CSS.


## Results 

Our web page without filters looks like this:

![ing](https://user-images.githubusercontent.com/81272629/124393773-a893f600-dcc1-11eb-8870-7ec93ed6b98e.png)

As we can see, there is input boxes with examples, thus the user knows the format the data must have. The user can put data in all filters, some of them or none of them and the table will be filtered accordingly.

In the following example we filtered the table with state = "tx" and city = "tomball" to see all the registered UFOs sightings in this texan city

![ing](https://user-images.githubusercontent.com/81272629/124394157-c19da680-dcc3-11eb-8cf0-ab2cec52bb4a.png)

## Summary

One drawback of this web application is that the filters are case and format sensitive, and while the user has examples of how the input should be written, it can be too subtle to notice. More dynamic filters would lead to a better user experience.

When the page has the table with all the data, it becomes very long, for this reason another improvement would be to change the design of the table so that it shrinks and we could scroll within the table.

On the other hand, we could also add another filter to filter by sighting duration, to do that we would have to standarized the duration column. This would be helpful for all users that want search for patterns based on this criteria
