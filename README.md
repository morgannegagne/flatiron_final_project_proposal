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

Comment
* text: string
* image_url: string

(Possible Additional Models)
*ListSave*
*List*
*UserList*



Project Proposal Guidelines
Domain
Models and schema
Relationships (has_many/belongs_to)
Draw IO
Hand-drawn
User Stories
Description of what a user should be able to do

Example:

 As a user, I will be able to login/logout
 As a user, I will be able to add and remove friends
 As a user, I will be able to create and delete posts
 As a user, I will be able to comment on and like posts
Wire-Frames
Basic illustration of pages
Fluid UI
Mock Flow
Moqups
Hand-drawn
Overview of component structure
Container/presentational components
Routes
Outside Resources
APIs
example JSON
Authorization with keys
Libraries/gems
Project Schedule
MVP features
Final version features
Stretch goals
Which features you plan on having done on which days
