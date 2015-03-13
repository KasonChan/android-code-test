## Android Code Test for ZipfWorks Engineering Candidates##

### Introduction ###

[ZipfWorks](http://www.zipfworks.com/) is currently seeking a talented Android engineer
to join our growing team. More information about our company and the position are available
at our [Stack Overflow careers page](http://careers.stackoverflow.com/jobs/81017/android-engineer-zipfworks)

This repository contains the necessary instructions for completing the code test. The
test involves building an that covers some of the basic use cases for
BluePromoCode and makes use of our RESTful API endpoints.

### Requirements ###

Your mission is to write an app with the following screens:

![](design/coupons.png) ![](design/login.png)

Use the [design](design) folder for guidance, we would like you to focus on how the app works

1. Coupons
  - Show coupons from our REST API
  - Resource: `http://api.bluepromocode.com/v2/promotions`
  - Method: `GET`

2. Login
  - Login using our REST API
  - Resource: `http://api.bluepromocode.com/v2/users/login`
  - Method: `POST`
  - JSON Encoded Parameters: `email`, `password`
  - We have a test account you can use: email: `a@a.com`, password: `12345678`

3. Bonus: Signup
  - Signup using our REST API
  - Resource: `http://api.bluepromocode.com/v2/users/register`
  - Method: `POST`
  - JSON Encoded Parameters: `fullName`, `email`, `password`

4. Bonus: Personalized Coupons
  - Show personalized coupons from our REST API (requires authentication)
  - Resource: `http://api.bluepromocode.com/v2/users/self/promotions/suggestions`
  - Method: `GET`

### Developing ###

1. Fork this repository to your Github account
2. Implement the above requirements - we'd like to see several commits to
   get an idea of how you went about developing the app
3. You may use Eclipse, Android Studio, or the IDE/editor of your
   choice; you're also welcome to use any 3rd party libraries -
   although we may ask you how you might implement the same functionality
   without the use of said libraries
4. If you have any questions, don't hesitate to contact us at any time
   at android@zipfworks.com

### Submitting Your Code ###

1. Include in this README (or a separate markdown file) any steps needed
   for us to compile and run your code
2. Send the link for your repository to android@zipfworks.com
3. After we receive your submission, we'll schedule a follow-up
   interview to go over your project

