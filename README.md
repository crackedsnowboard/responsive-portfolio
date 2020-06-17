# Responsive Portfolio
This project was oriented around creating web pages according to a specific formating and design request. I primarily utilized Bootstrap to create elements and applied classes to adjust the formating. The website was composed of three pages:

1. About Me page
2. Portfolio page
3. Contact page

## Responsive pages
The key consideration was to make the website dynamically responsive to different view ports. Each page required to adapt at the following breakpoints:

* 980px
* 768px
* 640px

## Additional Procedural Steps - What We Did
* Insert semantic HTML elements into the code
* Provide alt attributes for image elements
* Verified all links were functioning

### Key bootstrap components utlized
I primarily used the following boot strap elements to complete this project

1. Navbar - Consistent across all three sites
2. Cards - for the About Me page and the Portflio page
3. Forms - for the Contact page

#### Bootstrap grid  
Below is an exaple of how I used the row and columns to layout the cards on the Portfolio page.

```
<div class="row">
        <div class="col-sm-6">
            <div class="card mb-5">
                <img src="./Assets/portfolio1-guess.jpeg" class="card-image" style="width: 100%" alt="Red background with white lettered words written as Guess Who">
                    <div class="card-img-overlay d-flex  align-items-end">
                        <h5 class="d-flex flex.fill bg-info text-white py-1 px-2 text-center">Word Guess</h5>
                    </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div class="card">
                <img src="./Assets/portfolio2-rpg.jpg" class="card-image" style="width:100%"
                                        alt="Board game with multiple player pieces displayed on top">
                    <div class="d-flex flex-column justify-content-end">
                        <h5 class="text-over-img bg-info text-white py-3 my-0 px-0 text-center">RPG Game</h5>
                    </div>
            </div>
        </div>
    </div>
```
##### Useful links
[Bootstrap Starter Kit](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
[Bootstrap Components](https://getbootstrap.com/docs/4.5/components/alerts/)

#### Author Links
[LinkedIn](linkedin.com/in/joel-mathen/)
[GitHub](https://github.com/crackedsnowboard)
