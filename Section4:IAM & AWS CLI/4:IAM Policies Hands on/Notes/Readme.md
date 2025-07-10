# IAM: POLICIES HANDS ON

## First of all lets go in the ADMIN group.

## As you can see the user muskan is part of the admin group and has the ADMNISTRATOR ACCESS permission to AWS.

[![Slide 1](../Slides/Slide1.png)](../Slides/Slide1.png)

## That means if i go into the user MUSKAN to go into my IAM Console

## Now i will go into the NORMAL ACCOUNT , go into admin and remove the User MUSKAN from that admin group

[![Slide 2](../Slides/Slide2.png)](../Slides/Slide2.png)

## As you can see above we see access denied

## STEPS TO ADD PERMISSION POLICIES

### Go to ADD PERMISIIONS

### ATTATCH POLICIES DIRECTLY

[![Slide 3](../Slides/Slide3.png)](../Slides/Slide3.png)

### Click IAMREADONLYACCESS and then NEXT

[![Slide 4](../Slides/Slide4.png)](../Slides/Slide4.png)

### Lets try to create a group on the right side

### As you can see we see ACCESS DENIED , as the USER only has IAMREADONLYACCESS it is not able to create a user

### To allow to create user on the right hand side i need to give IAMFULLACCCESS

[![Slide 5](../Slides/Slide5.png)](../Slides/Slide5.png)

### Lets create a group called DEVELOPERS on the left hand side

### Go to Groups => Add User To the Groups

[![Slide 6](../Slides/Slide6.png)](../Slides/Slide6.png)

### Click on Create Group

### Create user group

### Add any policy like Alexaforbusiness

[![Slide 7](../Slides/Slide7.png)](../Slides/Slide7.png)
[![Slide 8](../Slides/Slide8.png)](../Slides/Slide8.png)
[![Slide 9](../Slides/Slide9.png)](../Slides/Slide9.png)

group name => developers is created

now if you go to muskan user you can see the policies and different groups its attached to

[![Slide 10](../Slides/Slide10.png)](../Slides/Slide10.png)
[![Slide 11](../Slides/Slide11.png)](../Slides/Slide11.png)

# Now lets look at policies in Detail

[![Slide 12](../Slides/Slide12.png)](../Slides/Slide12.png)

# Lets go at PERMISIIONS DEFINED IN THIS POLICY

lets check

## Summary

[![Slide 13](../Slides/Slide13.png)](../Slides/Slide13.png)
allow all services of AWS
and then

## Json

[![Slide 14](../Slides/Slide14.png)](../Slides/Slide14.png)

# Allow any action on any resource

# Lets check another policy

# IAMREADONLYACCESS

[![Slide 15](../Slides/Slide15.png)](../Slides/Slide15.png)

## When i click on IAM i can see the api calls that have been allowed

[![Slide 16](../Slides/Slide16.png)](../Slides/Slide16.png)

## lets click on json and check the policy json

[![Slide 17](../Slides/Slide17.png)](../Slides/Slide17.png)
Effect => Allow

and then we list down api calls that have been allowed

Get*
List*

Resource\*

# You can also create your own policy

[![Slide 18](../Slides/Slide18.png)](../Slides/Slide18.png)

# Either you can use a JSON OR A VISUAL EDITOR to create your own policy

[![Slide 19](../Slides/Slide19.png)](../Slides/Slide19.png)
[![Slide 20](../Slides/Slide20.png)](../Slides/Slide20.png)

# Search and select IAM

[![Slide 21](../Slides/Slide21.png)](../Slides/Slide21.png)

# and what action we need to authorize, lets search LISTUSER AND GETUSER and authorize the same

[![Slide 22](../Slides/Slide22.png)](../Slides/Slide22.png)
[![Slide 23](../Slides/Slide23.png)](../Slides/Slide23.png)

# lets add name to the policy

[![Slide 24](../Slides/Slide24.png)](../Slides/Slide24.png)
[![Slide 25](../Slides/Slide25.png)](../Slides/Slide25.png)
[![Slide 26](../Slides/Slide26.png)](../Slides/Slide26.png)

# lets delete the developers group because we dont need it

[![Slide 27](../Slides/Slide27.png)](../Slides/Slide27.png)
