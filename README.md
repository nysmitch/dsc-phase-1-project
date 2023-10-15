![header](https://github.com/nysmitch/dsc-phase-1-project/assets/147038854/55be3483-8e32-46b5-8ba1-182e37d621c0)
# Microsoft Movies
**Author:** Nyssa Mitchell
 
## Project Overview

This project is designed to help plan the future of Microsoft Movies. All of the big companies are creating original movie content and Microsft wants to too. They are contemplating creating their own Microsoft Movies platform. Descriptive analysis of current movie trends and the revenues they generate can help lead Microsoft in the right direction.


![video-stream](https://github.com/nysmitch/dsc-phase-1-project/assets/147038854/202a2d5e-8c2a-42d3-a624-4fb59a87d97e)


### Business Problem

I have been hired to analyse 3 sets of data detailing movies, their ratings and their average gross revenues in both the domestic and foreign markets. I am then to provide 3 conclusions and reccommendations to Microsoft and the future of their movie platform.

### The Data

To answer those 3 questions I have used 3 datasets from 2 of the most reputable movie information sources:
* Box Office Mojo (bom.movie_gross)
* IMDB (imdb.title.basics,imdb.title.ratings)

This data provide insights into viewer ratings, revenue generated, movie studios and timings of some of the top movies from the past 12 years. 

## Methods
To measure the success of a movie I used the two values, average rating and total value. I then posed 3 questions that I would analyse the data to answer:
* What genres of movies have proved to be most successful?
* Which movie studios have produced the most successful movies?
* Does the runtime of a movie correlate to its success?

### Results - Most Succesful Genre
I started by relating my genres to my two success areas and my conclusions were:
* Measuring Success by average rating proved ineffectual: 
      this showed a very even playing field with genres ranging in rating from 5 - 7.2 but there was no obvious correlations between the genre and the rating
* Measuring Success by Total Revenue showed a clear result

<img width="531" alt="genres_v_totalrevenue" src="https://github.com/nysmitch/dsc-phase-1-project/assets/147038854/62888558-dee6-452c-9a42-dd47f2061967">


From this bar graph we can clearly see the top 3 genres of movies with the highest median revenues are: Adventure, Animation and Sci-Fi

### Results - Most Succesful Studios
I again started by relating my genres to my two success areas and my conclusions were:
Measuring Success by average rating proved ineffectual; Once again the average ratings were very similar and there were a lot more studios than genres this time so I needed to find another method

<img width="553" alt="studio_v_revenue" src="https://github.com/nysmitch/dsc-phase-1-project/assets/147038854/886c710d-1e92-408b-80ea-e5291e09b912">

When analysing success of a studio against total revenue we were easily able to find the top 20 studios as seen in this bar graph. With the top 2 being HC and P/DW.

### Results - Does Runtime Matter?
For this final question I wanted to calculate the correlation coefficient between runtime and Revenue. This would tell us if the length of the movie impacts its success.  

The correlation factor of runtime to total revenue  =  0.14949065557391722
This is also represented in the scatter plot which seems to have no shape or pattern whatsoever.

<img width="476" alt="runtime_v_revenue" src="https://github.com/nysmitch/dsc-phase-1-project/assets/147038854/3408d7e2-b7de-413d-bb05-a2e3abf313c8">

Thus there is no correlation between the length of a movie and it’s success.

## Conclusions and Reccommendations
My 3 conclusions for the future of the Microsoft Movies project are:
* The top 3 genres of movies are Adventure, Animation and Sci-Fi.

    I would recommend creating original content in those genres to maximise revenue.
* The most successful movie studios are: HC and P/DW.

    I would recommend collaborating with them on future movie projects and emulating their success
* Runtime does not influence revenue. Scientists have told us our attention spans are getting shorter and shorter but thankfully this does NOT correlate to our enjoyment of movies.

    My recommendation would be to produce movie content of good quality instead of focusing on length.

## For More Information

See the full analysis in the Jupyter Notebook or review this presentation.
For additional info, contact Nyssa Mitchell at nysmitch@gmail.com




