# TFL + Giphy API Project

![](https://media.giphy.com/media/4SAw7TBKJPX3y/giphy.gif)

Select the tube line you want to check the status of from a predefined list (so that we didn't need to worry about misspellings or other inputs).

Once you have selected your tube line, an API call is made to TfL to check on the status of the line. This would be fed back into the DOM to tell the user what the current status is.

Then using this status received from the TfL API, we make an API call to Giphy to search for a gif that captures the sentiment of tube line statuses like "Good service" or "Part suspended".

## Design

We designed our app with large fonts and plenty of negative space so that it had balance, and used multiples of 8 in our margins, padding, and other elements to keep things harmonious and pleasing to the eye.

We were originally going to have a white background and elements (such as the submit button and the logo) styled to 'TfL blue'. But with some extra time on our hands, we tied in the styling with our functionality. Now these elements, plus the background color, update according to the tube line the user selects.

Even though the design was balanced and comfortable on desktop and mobile as it was, we added a media query for mobile just to really hone in on that style and make sure it looked great on mobile phones.

## Gifs

At first the gifs we returned were from hard-coded search terms in an object, and then always returning the first gif we received from those search terms. However, with some further intense work, we were able to make a random gif return each time the submit button was pressed, rather than the same one over and over.
