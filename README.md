# UFOs

## Purpose

Through using HTML and Javascript, we want to display a webpage with a dynamic table that is able to filter the UFO data results based on the input put into the search criteria fields.  Along with the functionality to filter it by date, we want add the capacity to filter by city, state, country, and by the shape of the identified phenemenom.

## Results
One of the first things we did was implement the following code to add additional search fields.  

```
<p>Filter Search</p>
                <ul class="list-group bg-dark">
                    <li class="list-group-item bg-dark">
                        <label for="date">Enter Date</label>
                        <input type="text" placeholder="1/10/2010" id="datetime" />
                    </li>
                    <li class="list-group bg-dark">
                      <label for="city">Enter City</label>
                      <input type="text" placeholder="bonita" id="city" />
                     </li>
                     <li class="list-group bg-dark">
                       <label for="state">Enter State</label>
                       <input type="text" placeholder="ar" id="state" />
                     </li>
                     <li class="list-group bg-dark">
                      <label for="country">Enter Country</label>
                      <input type="text" placeholder="us" id="country" />
                    </li>
                    <li class="list-group bg-dark">
                      <label for="shape">Enter Shape</label>
                      <input type="text" placeholder="circle" id="shape" />
                    </li>
```

We added placeholder text so that the user would know what the format of the search paramaters would need to look like.

The search field looked like this on the webpage.

<img width="361" alt="Screen Shot 2022-01-03 at 4 40 53 PM" src="https://user-images.githubusercontent.com/87248687/147983936-2a77f7df-7349-44ba-a4fe-2455bd1dab19.png">


In order to perform a search, one can filter through the data by using at least one of the criteria fields.  The search must match the format displayed in the placeholder text or it will not return a result.  A example of a search would look like this:


<img width="1425" alt="Screen Shot 2022-01-03 at 4 53 07 PM" src="https://user-images.githubusercontent.com/87248687/147984502-94a06315-a047-4980-b994-94aa4f87e050.png">







## Summary

### Key Drawback

Overall, this web application is a pretty effective way to filter through this UFO data.  While it is effective, there are a few drawbacks.  One issue with the webpage is that the duration time in the data is not specified by a universal unit of time.  Therefore there isn't a way to filter the data by time alone. 



### Ways To Improve

Another drawback to the website is that the criteria for filtering is case sensitive.  This means that we would not get a result if we typed in NY Vs. ny as shown below.

<img width="1420" alt="Screen Shot 2022-01-03 at 5 27 55 PM" src="https://user-images.githubusercontent.com/87248687/147987209-00ef37d8-80d9-46de-b60a-50ac5124b544.png">

<img width="1418" alt="Screen Shot 2022-01-03 at 5 28 25 PM" src="https://user-images.githubusercontent.com/87248687/147987267-5ac3db1c-1ac4-4a10-807f-378a2eeb849c.png">

If we can find a way to make the search filtering "case-insensitive", then we can make great strides towards making it better.


Another thing that would help tremendously to make this better would be to add functionality to filter the data by either a specific month or a even a whole year.  This would allow users to see if a string of UFO sightings in a specific time frame may be interconnected.


