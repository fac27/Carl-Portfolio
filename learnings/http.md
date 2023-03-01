## 1. Write code that executes asynchronously

![](/Assets/Async-ss.png)

We have used asynchronous programming to fetch data from multiple API's and sort it. One example was the asynchronous call on the Police data api.

## 2. Use callbacks to access values that aren’t available synchronously

![](/Assets/Callback-ss.png)

Callbacks were used heavily, the example above shows the use of callbacks to print data onto the page.

## 3. Use promises to access values that aren’t available synchronously

As seen in the screenshots in #1 and #2, we used async/await which returned promises after awaiting the response.

## 4. Use the fetch method to make HTTP requests and receive responses

![](/Assets/Fetch-ss.png)

Fetch was used for each api call in the project, the above example shows how it was used to make a http request to the Teleport api.

## 5. Configure the options argument of the fetch method to make GET and POST requests

The project only used get requests so there wasn't a need to configure the options argument to make post requests.

## 7. Use the filter array method to create a new array with certain values removed

![](/Assets/Filter-ss.png)

Filter was used to 'filter out' the non matching results from the data fetched from the Teleport api based on what the user searched for.

## 8. Access DOM nodes using a variety of selectors

![](/Assets/Selectors-ss.png)

The generate scores function shows how we used "getElementById" and "querySelector".

## 9. Add and remove DOM nodes to change the content on the page

![](/Assets/Nodes-ss.png)

Examples of Dom nodes being added to the page in the screenshot above. This example shows how the police data was rendered onto the page, by creating div's and appending elements.

## 10. Toggle the classes applied to DOM nodes to change their CSS properties

![](/Assets/Nodes-ss.png)

The example in #9 also shows how css classes were also added to dom nodes.

## 11. Use consistent layout and spacing

![](/Assets/Spacing-ss.png)

Consistent spacing was applied to the entire page with css "letter-spacing".

## 13. Debug client side JS in our web browser

## 14. Use console.log() to help us debug our code

![](/Assets/Console1-ss.png)
![](/Assets/Console2-ss.png)

Console.log() was very helpfull when sorting the response data from the Police data api. As shown in the screenshot above, data was logged to the console at various points in the sorting algorythm, this gave an actual visual representation of what each function/method did to the data.
