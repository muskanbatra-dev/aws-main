# STEPS TO CREATE IAM USERS

## In the search bar of the console search IAM, and go to the iam service dashboard

[![Slide 1](../Slides/Slide1.png)](../Slides/Slide1.png)

## Upon arriving on the IAM DASHBOARD, we have some security recommendations that we can for now not care about

[![Slide 2](../Slides/Slide2.png)](../Slides/Slide2.png)

## On the left hand side of the IAM DASHBOARD we go to users

So this dashboard is where we are going to create our users
[![Slide 3](../Slides/Slide3.png)](../Slides/Slide3.png)

## IAM is a global service, therefore there is no region to be selected

## When you create a user in IAM it will be global, it will be available everywhere, and therefore no region needs to be selected.

## but some other consoles that we see over here will be region specific.

[![Slide 4](../Slides/Slide4.png)](../Slides/Slide4.png)

# Why do we create Users?

## Well we create users beacuse right now we are using what is called the root User, which is not the best practise

## Click on create user button

[![Slide 5](../Slides/Slide5.png)](../Slides/Slide5.png)

## Add a username

[![Slide 6](../Slides/Slide6.png)](../Slides/Slide6.png)

## click the checkbox for Provide user access to AWS mangement console

[![Slide 7](../Slides/Slide7.png)](../Slides/Slide7.png)

## click the radiobutton for I want to create an IAM User

[![Slide 8](../Slides/Slide8.png)](../Slides/Slide8.png)

## click the autogenerated password and , and user must create a new password at next sign-in

[![Slide 9](../Slides/Slide9.png)](../Slides/Slide9.png)

## Next we have to add permissions to this User or get started with groups.

[![Slide 10](../Slides/Slide10.png)](../Slides/Slide10.png)

## Now we create a group , the group name is going to be admin and policy name is going to be admnistrator access

[![Slide 11](../Slides/Slide11.png)](../Slides/Slide11.png)
[![Slide 12](../Slides/Slide12.png)](../Slides/Slide12.png)

## Now that this is done,we can add the user into the admin group, now click on next

[![Slide 13](../Slides/Slide13.png)](../Slides/Slide13.png)

## Now we have tags as well

## Tags are everywhere in aws they are optional, but they allow you to give metadata to many of your resources

[![Slide 14](../Slides/Slide14.png)](../Slides/Slide14.png)

## Now we can email signin instructions or download csv file, so we can login with this user later

## But first lets return to the user list and have a look at everything

## click on create user

[![Slide 15](../Slides/Slide15.png)](../Slides/Slide15.png)

[![Slide 16](../Slides/Slide16.png)](../Slides/Slide16.png)

## lets return to the user list

[![Slide 17](../Slides/Slide17.png)](../Slides/Slide17.png)

## if we go to permisiions

[![Slide 18](../Slides/Slide18.png)](../Slides/Slide18.png)

## It has been attached via the group admin

[![Slide 19](../Slides/Slide19.png)](../Slides/Slide19.png)

## Muskan inherited permission of the group admin it is in, and this is why we put users in group

# now we want to sign in with our user muskan

## AWS user has an

### account id

### sign-in Url

[![Slide 20](../Slides/Slide20.png)](../Slides/Slide20.png)

## You can customize this Sign-in URL very easily by creating an account alias

click on create under Account Alias
[![Slide 21](../Slides/Slide21.png)](../Slides/Slide21.png)

[![Slide 22](../Slides/Slide22.png)](../Slides/Slide22.png)

[![Slide 23](../Slides/Slide23.png)](../Slides/Slide23.png)

[![Slide 24](../Slides/Slide24.png)](../Slides/Slide24.png)

## Now paste this sign-in url in a private window on safari web browser

## On the left side we have the IAM USER on the right side we have Normal AWS User[text](<../../../Section5: EC2 FUNDAMENTALS/2: EC2 Basics copy 5>)

[![Slide 24](../Slides/Slide24.png)](../Slides/Slide24.png)
