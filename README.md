# Javascript Challenge

Included in this repository is a blank HTML template containing the list of items stored in the *info* variable. This is a sample data that you might get when you are requesting data from a REST API endpoint.

Using the provided HTML file, please create a mobile web prototype following the wireframe (wireframe.png). 

### Regarding the Wireframe:
Please note that this is just a "wireframe" and we would expect you to apply some usable designs. 
You are free to create your own design or apply existing design/frameworks (Bootstrap, Foundation, and Material UI)

## Requirements:
* HTML5 and CSS3 required.
* Items should be dynamically added when the page loads.
* Please use Javascript only. We can reconsider jQuery... no other frameworks (ReactJS, AngularJS, Vue.js, etc...)


## Please answer the following questions:
* Please explain how did you come up with the solution. We would like to see your train of thought.
*  * *First  wrote my javascript code in ES5 format to look more simpler and lesser codes (lesser codes == lesser bugs). I planned also to add Babel Polyfill to support old browser but however I just commented it out since I though it would not be necessary since new browsers support ES5 now and for faster loading as well.*
*   *  *I'm a fan of **functional programming** and **ReactJS** so you'll might notice that I created some independent function like filter, forEach and formatYear; and some reusable component such as Category and Item. Then I start to format the API response into 2 dimensional object that would looks like:*
	```
    {
    	"c001": {
          "categoryName":"Phones",
          "products": {...}
         }
    }
    ```
* * *After formatting API response, I loop it with reusable component then push it into the `.container`.*
* Please explain any design decisions made (why you chose the design/framework, etc.)
* * *In design, I just made it looks plain and simple. I would like to use material design if I just have some more time. I just inspired by the design of google play because I dont want users to scroll very long just to see the next catergory (just imagine hundreds of items listed).*
* Please indicate tools that you used for coming up with your solution.
* * *hmmmm... html, css, javascript?*
* Choose one: Star Wars or Star Trek? Why?
* * ***STAR WARS!!!** coz i'm a jedi. May the force be with you.*
