# IAM: USERS & GROUPS

## IAM = Identity and Access Management, It is a Global Service beacuse in IAM, we are going to create our users and assign them to group.

## Root Account: created by default , shouldn't be used or shared.

## Users are people within your organization, and can be grouped.

## Groups can only contain users , not other groups.

[![Slide 1](../Slides/Slide1.png)](../Slides/Slide1.png)

## Lets take an example:

## We have Alice ,Bob, charles, David, Edward and Fred.

[![Slide 2](../Slides/Slide2.png)](../Slides/Slide2.png)

## Alice Bob and Charles work together hence they are all developers.

[![Slide 3](../Slides/Slide3.png)](../Slides/Slide3.png)

## David and Edward are in the operations group.

[![Slide 4](../Slides/Slide4.png)](../Slides/Slide4.png)

## Users dont have to belong to group , and user can belong to multiple groups.

## For example: Fred here

[![Slide 5](../Slides/Slide5.png)](../Slides/Slide5.png)

## If Charles and David work together, you can create another group of Group: Audit Team

[![Slide 6](../Slides/Slide6.png)](../Slides/Slide6.png)

## Why do we create users and why do we create groups?

### Because we want to allow them to use our AWS accounts, and to allow them to do so we have to give them permisiions.

### USERS OR GROUPS: can be assigned json documents called policies

[![Slide 7](../Slides/Slide7.png)](../Slides/Slide7.png)

### These policies define the permisiions of the users

### These policies define the permisiions of the users

### In AWS you apply the LEAST PRIVILEDGE PRINCIPLE: dont give more permisiion than a user needs
