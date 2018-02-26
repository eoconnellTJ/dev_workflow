### Dynamic Yield

#### Setup a test environment

* Build out a test environment to begin testing Dynamic Yield actions
* Preference of the user, a simple Node app hosted on [Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up) will do just fine
* on DY - create a new site for testing on the top left it'll show current site connected, click `Add site`
* Paste the heroku/site url i nthe `Website URL` field


#### JS Exercise

* Spend some time practicing building out a mock page entirely within javascript. Codepen is recommended for this exercise but is the developers choice. 
* Add this to your html and the rest should be done in javascript: 
```
<header id="banner"></header>
<div id="main"></div>
```
* The end result should look as:
![Top Part of Solution](/assets/js_exercise_top.png)
![Bottom Part of Solution](/assets/js_exercise_bottom.png)

#### Injecting DY

* Once the test environment is properly set up, now it's time to get familair with DY
* Start by adding a ```hero image``` to your site via `Dynamic Content`

###### Dynamic Content
* Dynamic Content is an ideal solution when wanting to make sure that each visitor to the site is exposed to the most relevant creative for him or her, or when you are unsure which creative would lead to the best performance on site and increased engagement – Homepage hero banners are a perfect example for using Dynamic Content
* Set **2 different variations** so each time you arrive on the page or refresh there may be a differrent image showing. This is a great benefit for using DY will determine in real-time which variation is the best performing per your defined objective, and which should be displayed to each visitor on the site

###### Custom Actions

* Custom Actions enable highly dynamic and interactive experiences – brand new elements can be introduced to the page, any element on the page can be changed, moved, swapped with other elements or completely manipulated
* Create at least **2 Custom Actions** some ideas of what to create:
  * Injecting new div elements to page
  * Changing the color patterns and style
  * Adding a button that triggers another event
  * Inserting text inside of an element 

#### Checklist

* Complete JS Exercise
* Live site
* Hero-image (2 variations)
* 2+ Custom Actions