# Final Project Proposal

## Domain

**Models**

User
* username: string
* *password_digest*: string
* image: string (url)
* blurb: text

Friendship
* user_id: integer
* friend_id: integer
* pending: boolean
* accepted: boolean

Notification
* belongs_to :user
* unread: boolean

Place
* name: string
* google_uid: string
* description: string
* lat: float
* lng: float
* address: string

Save
* user_id: integer
* place_id: integer
* type: string
* source: string (user, url)

Comment
* text: string
* image_url: string

(Possible Additional Models)

*ListSave*

*List*

*UserList*

**Relationships**
[Draw.io Schematic](https://drive.google.com/file/d/1tSVIjp0rLEyjQdre3IazEHK-qwdI5eTX/view?usp=sharing)

# User Stories

**MVP**
* As a user, I will be able to add friends. 
* As a user, I will be able to save and recommend places with comments and photos.
* As a user, I will be able to view all of my saved or recommended places on a map.
* As a user, I will be able to see all the the saves and recommendations of my friends.

**Final Product**
* As a user, I will be able to login/logout with authentication.
* As a user, I can create lists and invite others to contribute to lists.
* As a user, I can view the website through a demo mode (without needing to login).

**Stretch Goals**
* As a user, I will be able to use a Google Chrome extension to save places to my profile with a link to the page where it was saved from. 

# Wire-Frames

# Overview of Component Structure

# Client-Side Routes
/:user_slug ?

/map

/friends

/lists

# Outside Resources
* Google Maps API (google-maps-react)
 * < GoogleMap />
 * < StandAloneSearchBox /> (access to Google Places)
* Filestack (image uploads)
* React Semantic UI 
* *AWS*
* *Authorization*

# Project Schedule

Tues 4/3 
* Finish project proposal

Wed 4/4 (**MVP Approval**)
* ActiveRecord relationships
* Database creation
* Server-Side Routes

Thur 4/5
* Finish up backend
* Full User CRUD
* Search and Save Google Maps places

Fri 4/6
* Display places on maps
* Add friends
* See friends maps

Weekend 4/7-4/8
* Image Upload
* Client-Side Routes

Mon 4/9
* Notifications
* Edit/delete saves

Tues 4/10
* Basic styling (layout/CSS grid)

Wed 4/11 (**MVP Demo Day**)
* Wiggle room to work out any bugs

Thurs 4/12
* Add User Lists
* Invite Friends to Lists

Fri 4/13
* Auth

Weekend 4/14-4/15
* Fun stuff (design logo, pick name)
* Explore Chrome Extension

Mon 4/16
* Chrome Extension

Tues 4/17
* Chrome Extension with Auth
* Styling

Wed 4/18
* Styling
* ReadMe
* Demo Mode

Thurs 4/19 (**Science Fair**)
* Deploy!
