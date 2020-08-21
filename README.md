<p align="center">
  <img src="https://github.com/joshhunt1991/Chalk-and-Sawdust/blob/0905e52615c5eda77c9ab60f499e8765b582ccb6/assets/images/CNSPL.png" alt="Chalk and Sawdust Powerlifting gym logo"/>
</p>

# Description

*This is a fictitious company*

> Chalk and Sawdust Powerlifting Gym is training facility focusing on the principles of powerlifting to help people of all abilities and age ranges improve their strength and fitness.

> This is a limited membership family run gym aiming to give maximum benefit to the members by capping the members at 150 people.

# Deployment and Demo

Website has been deployed to [GitHub Pages](https://joshhunt1991.github.io/Chalk-and-Sawdust/).

# Wireframe

The wireframe was designed using [Balsamiq](https://balsamiq.com/wireframes/) and links to the final version can be found below:

- [Wireframe Final Version](https://github.com/joshhunt1991/Chalk-and-Sawdust/blob/9676f8f67e486354209e52c9dfc19f63f9d707cc/CHALK%20AND%20SAWDUST.bmpr)

# UX

I have opted to a simple and responsive design which is lightweight and has a loading time of less than 1 second.

- Home page: Contains a jumbotron, background image, and an automatic image slider which all resize accordingly depending on user's viewport size
- The big 3 page: Contains and introduction to the concept of powerlifting and 3 responsive videos with accompanying text 
- About page: Contains a paragraph explaining the gym ethos and 3 responsive images demonstrating the benefits of the gym.
- Contact page: Contains a responsive contact form and responsive embedded google map 
- Membership page: Contains opening times, information on membership packages and a button linking to a modal containing the membership form.

![Responsive image with many different monitors](images/responsive.png)

In order to improve user experience and website loading speed, I have compressed the images using [tinypng.com](https://tinypng.com/) and the reduction in image size has been 57%.

![tinypng image saving results](images/image_compressor.png)

# Visual Identity

- [Canva](https://www.logopony.com/) for the logo design and then the color scheme was extended from this to the rest of the site

# User Stories

Users:

- As a user, I'd like to get a feel for the atmosphere of the gym
- As a user, I'd like to contact the company with any questions I have
- As a user, I'd like to see what the facilities are
- As a user, I'd like to sign up for membership


# Testing

Website has been tested using [GTmetrix](https://gtmetrix.com/reports/fandressouza.github.io/7xHu6MBv) and [BrowserStack](), see results below:

![Website Speed Test Results](images/speed_test.png)

The points below can be improved with a bit more optimization:

- Serving scaled images (some images are being resized in CSS e.g. logo.png)
- Leveraging browser caching
- When I did this test, css/theme.css returned a 404 (Imispelled Theme.css)

# Scalability

Using a back-end programming language and database, I'd like to have a fully featured CMS which can be used by non-technical people to create, read, update and delete data easily.

Also, I'd like franchise owners to have a private section where they can find resources and talk directly to our customer service representatives.

# Technologies

- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)

# Media

I have used different resources for images and my logo, I'll list all below:

- [Canva](https://www.canva.com/) for the logo design
- [Pexels](https://www.pexels.com) for the textured red background image used across the site
- [Font Awesome](https://fontawesome.com/6?next=%2Fstart) for the downward arrow on the home page
- [Pixabay](https://pixabay.com/) for the rest of the images


# Thanks to

- Font awesome community for developing this great resource
- Bootstrap crew for developing and maintaining such great library
- jQuery developers for all the work and great documentation
- Canva for the great service
- Pixabay and Pexels for creating such convenient resources of free use images

# License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.

Copyright 2020 Joshua Connor Hunt.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.