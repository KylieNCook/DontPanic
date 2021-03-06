
# Requirements

_Group 06 – “[Don't Panic!]”\
Date and location: Feb 23, 2020\
Group Members: Chris Keefe, Mason Rodgers, Brandon Click, Drew Sansom_

## 1. Positioning
### 1.1 Problem statement

The problem of life's many pitfalls affects everyone when they least expect it; the impact of which can cost you financially or cause a huge setback.

### 1.2. Product Position Statement

For anyone Who wants to stay informed about what matters for them, DontPanic! Is a is a free, lightweight application That helps anyone safely navigate life’s many pitfalls in a way that matters to you. Unlike CodeRED, our product is simple to use and allows the user to customize their preferences however they like.

### 1.3. Value proposition

Don't Panic is a free, minimal app that lets any American stay informed about the pitfalls in your life in a way you care about.

## 2. Stakeholders

**Users**: Commuters, Parents, People in locations at risk of natural or human-caused disaster, and Property Owners.
**Competitors**: CodeRED, Disaster Alert.
**Detractors**: People very cautious of allowing an app to see their location.
**Developers**: Mason Rodgers, Chris Keefe, Richard Sansom, Brandon Click.

## 3. Functional requirements (features)

- Personalization/Preferences: Being able to customize the information we receive from the app.
- Ease of Use: Simple design that is use for everyone to use and understand
- Basic Traffic Info: Most people in cities don't have many concerns in their everyday life. So basic traffic info was important for those people

## 4. Non-functional requirements
- Availability
- Usability
- Reliability
- Response Time


## 5. MVP
- The feature we plan on implementing early on would be the simple GUI and customization preferences.
- When building the GUI we try to keep in mind that anyone can use this app, so we are trying to make it very simple and intuitive.
- During our interviews, the most requested feature was being able to filter out the info they receive. If they were going to get notifications for things they didn't care about, they didn't want the app. So to deal with this we are planning on having categories, or a “tag” system to help people choose what they want to see.

## 6. Use cases
### 6.1. Use case diagram
**![](https://lh3.googleusercontent.com/DtVIkK9lUIwGwatsRzYubi1V014HrzINyTUaj9m-yfEIGhGTpLZiAPJROAn-Qhe4mBDRqtPdl50NSSNrGBl1lDIQCtQgDoSDekTQhvJ3fYqvT36fL_CMe-1sI3HVxzE1Cdm_M_Xu)**


### 6.2. Use case descriptions

**Use Case**: Download App   
**Actor**: App User   
**Description**: A smartphone user will download the “DontPanic” app to sign up for the service   
**Preconditions**: They own a smartphone    
**Postconditions**: They have the app, have created an account.    
**Main Flow**:
1. The actor logs into the Google Play store and downloads “DontPanic”  
2. After installation, the user opens the app, and follows the steps to create an account  
**Alternative Flow**:
None.  This is the first step and must go according to plan for the service to work.   

**Use Case**: Receive Push Notifications   
**Actor**:  App User   
**Description**: The user will receive emergency notifications on their smartphone   
**Preconditions**: The user has downloaded the “DonPanic” app and created an account   
**Postconditions**: The user is now receiving basic non customized notifications   
**Main Flow**:
1. After downloading the app, the user gives their phone permissions to send the phone notifications.    
**Alternative Flow**:
1. The user does not give their phone permission to send them notifications.   
2. They must open their settings, go to the notifications settings page, and then allow the phone to give them notifications.  
3. If they do not follow step 2, then they will not be able to use the service.  Permission must be given to the phone.   

**Use Case**: Sign Up Online  
**Actor**: SMS User  
**Description**: Someone who wants to receive their notifications via SMS can sign up using the web app  
**Preconditions**: They own a phone.  
**Postconditions**: They have created an account.  
**Main Flow**:
1. Actor logs into the DontPanic Website and creates an account  
**Alternative Flow**:
None, this must be done to start the service  

**Use Case**: Receive SMS Notifications  
**Actor**: SMS User   
**Description**: The SMS User will start to receive SMS emergency notifications   
**Preconditions**: They have signed up for the service using the web app   
**Postconditions**: They will start to receive SMS apps  
**Main Flow**:
1. They start to receive emergency notification apps  
**Alternative Flow**:
1. They are not receiving apps, and must verify the information they entered in their account such as their phone number and ensure it is correct.  

**Use Case**: Customize Notification Type  
**Actor**: Service User  
**Description**: The user can select they types of emergency notifications they want to receive  
**Preconditions**: The user has either signed up via the “DontPanic” app or the web app  
**Postconditions**: The user is not only receiving notifications, but notifications of their choice.  
**Main Flow**:
1. The user logs into the application on their phone  
2. They open the setting that allows them to select and deselect the types of notifications they want to receive  
3. They go through the list and customize what notifications they want to receive.  
**Alternative Flow**:
1. The user logs into their account online via the web app.  
2. They open the setting that allows them to select and deselect the types of notifications they want to receive  
3. They go through the list and customize what notifications they want to receive.  
**Alternative Flow**:
1. The user does not change any settings regarding what kind of information they want to receive, and will continue to receive the default emergency notifications.  

**Use Case**: Stay Informed Of Emergencies  
**Actor**: Service User  
**Description**: The end result: the user receives notifications that help them stay informed of emergencies  
**Preconditions**: The user has either signed up for “DontPanic” via the web app to receive SMS notifications, used the “DontPanic” app to sign up, or both.  
**Postconditions**: The user will be receiving notifications that let them stay informed to emergencies.  
**Main Flow**:
1. The user receives push notifications, SMS notification, or both.  
2. They respond to the information as they desire  
**Alternative Flow**:
None.

# 7. User stories

**User story 1**:  “As a Smartphone owner, I want to download the DontPanic app so that I can stay informed.”
Priority: 1
Estimated Hours: 40

**User story 2**:  “As a user, I want to receive push notifications so that I am informed immediately of issues.”
Priority: 2
Estimated Hours: 8

**User story 3**:  “As A non-smartphone user, I want to be able to receive SMS notifications so that I can stay informed”
Priority: 7
Estimated Hours:

**User story 4**:  “As A non-smartphone user, I want to be able to sign up online so that I can stay informed.”
Priority: 6
Estimated Hours: 20

**User story 5**:  “As a user, I want to be able to customize my notifications so that I only get informed about things I care about.”
Priority: 3
Estimated Hours: 13

**User story 6**:  “As a user, I want to have a simple UI so that I can easily navigate the app”
Priority: 4
Estimated Hours: 13

**User story 7**:  “As a user, I want to choose how many times I am notified so that I do not get annoyed with the app.”
Priority: 5
Estimated Hours: 8

**User story 8**:  “As a user, I want to receive sources so that I can investigate issues further”
Priority: 8
Estimated Hours:  5

## 8. Trello
**![](https://lh3.googleusercontent.com/kwG0HuVmbXngqnOajZmB8ZhF35BTiNIQb4JsGYFGPn_aTiEg-5nzHJCBt9TzxJgIqHmjbIeuYKSm-W_XCq6JaG5vD78GnsfzYYCNDv11E5wdxZwl7ALdv1kzZpJmKojW7hjYnCWV)**
