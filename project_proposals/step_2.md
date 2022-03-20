# Project Proposal #

## Step Two of your first capstone is all about fleshing out your project idea. ##

For this step, please write a proposal based on the project idea you agreed on with your mentor. 

This proposal should be a 1-2 page document that answers the following questions: 

1. What goal will your website be designed to achieve?

    The website will allow you to track a package that was shipped using UPS

2. What kind of users will visit your site? In other words, what is the demographic of your users?

    The users that will use my app will be looking for an easy way to track a package and have that traking number saved so that they can check on it again

3. What data do you plan on using? You may have not picked your actual API yet, which is fine, just outline
   what kind of data you would like it to contain.

    I plan on using a username, password and tracking number

4.  In brief, outline your approach to creating your project (knowing that you may not know everything in         advance and that these details might change later). Answer questions like the ones below, but feel free       to add more information:

      a. What does your database schema look like? 

            User table
            
                username: id
                password
                first name
                lastname
                email

            Tracking Number table

                id
                tracking number
                user id
      
      b.  What kinds of issues might you run into with your API?

            Figuring out how to connect to the api
            How to use the data that is returned  
      
      c.  Is there any sensitive information you need to secure?

            User information
      
      d. What functionality will your app include?

            It will allow the user to store their tracking number and easily return to the site to check on the packages status
      
      e.  What will the user flow look like?

            Login/Register
            Enter a tracking number
            Receive tracking information
            Be able to enter another tracking number
            the tracking numbers will be kept in a list on their user page
            They will be able to click on those links to track the package
            Once they are finished with the tracking number they will have the option to delete it
            Log out
      
      f. What features make your site more than CRUD? Do you have any stretch goals?

            Being able to return to the site and click on a tracking number to receive updated tracking information