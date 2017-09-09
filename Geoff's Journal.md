# COMP6001-17B-SWIFT
### Geoff's Personal Journal for Team Swift

## My Role:
I have been assigned the role of creating the functionality for the timesheet edit. I made sure to be helpful in the wireframe design, by asking critical questions, providing reasoned answers and strongly contributing to the visible design of the edit page. Based off our design, I will now need to create the edit page in the app as per the spec.

## The Journal:  

#### Questions raised:  
* (1) How are we getting to the edit page?
* (2) What is the best way to display the edit page?
	* Can the same page be used to edit the item and add a new item, with the model changing depending on the state?
	
	
#### Reasoned answers:
* (1) My suggestion was that the user could edit the page from a) some dialogue popup with extra/additional info, or b) from directly tapping on the item slot.
* (2) The concern I had was that unecessary coding for two pages could be avoided by recycling one view and passing it an empty model (for creating items) or the populated model (for editing). Certain controls would be changed at page-load, such as the 'save' button text for example, based off the state of the bound model.  


#### Personal Research Done:  
1. Leveraging iOS' native 'edit' style controls for the items. Able to find several tutorials online and from the Swift book, but I have linked Apple's offical documentation for the group's reference below:  
[iOS Natively Edit](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/ImplementEditAndDeleteBehavior.html "iOS' Native Edit and Delete Example")  

![alt text](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Art/IEDB_sim_deletebehavior_2x.png "Native iOS Edit and Delete Example")