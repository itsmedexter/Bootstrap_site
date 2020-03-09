# First use of Bootstrap

Website done using Bootstrap. No seperate local css style sheet. All Bootstrap CSS.

## Getting Started

Open github links to view on browser or repository link for files. 

### Prerequisites

Any web browser can access or view link, repository. Use source-code editor to view html files.

### When hand hits the head

One thing that I should have payed attention to is the flow of div endings. One missing, boggled my mind and added several hours of cursing.

A big one was to zero padding and margins when needed. It was driving me mad seeing why is there extra space between my name and the bottom of the container. I asked Kerwin for a hint, it was the best. I used the Dev tools in the browser. I clicked on the area affected, it showed me padding and margin was there.

Second is keeping the code simple in portfolio.hmtl images. If you see the beginning to end in the  repository, you will see major changes in the container which holds the images.

--"col-sm-12 col-md-6" how much to split for each breaking point. Before, I just put one thinking it will do everything. Thats not the case.

--"img-fluid" forgot to do this, set fixed height and width and wondered why did it not work during breaking points.

--h4 class="bg-info text-white text-center py-1 px-0 mx-0 mb-2" I was putting this in different divs and making the boxes not jive together moving seperatly from each other. Finding I could just do this under the image. So the code with be the container with breaking points over the image and h4. 


## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

## Deployed Link

* [See Live Site](https://itsmedexter.github.io/Bootstrap_site/)


## Authors

Dexter Valencia 

- [Link to Portfolio Site](https://github.com/itsmedexter/Bootstrap_site)
- [Link to Github](https://github.com/itsmedexter)
- [Link to LinkedIn](https://www.linkedin.com/in/dextervalencia/)

## License

This project is licensed under the MIT License 

## Acknowledgments

* Jerome, TA, Bootstrap, Lynda.com for refrence, Google helped when I was super lost, and lots of trial and error.
