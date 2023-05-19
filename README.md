# InstagramApp

## Frameworks and Language used:
* Spring
* Spring boot
* My-Sql
* Java
## Data Flow
## Controller
### Admin

toggleBlueTick
### Comment

* addComment


### Post

* addPost
* getAllPosts
* getLikesForPost
* updateUser
* followUser
* 
### User

* signUp
* signIn
* signOut
* 
## Service
### Admin

toggleBlueTick

### Comment

addComment
### Follower

saveFollower
### Following

saveFollowing

## Repository
### Admin

IAdminmentRepo

### Comment

ICommentRepo

### Follower

IFollowRepo

### Following

IFollowingRepo

### Like

ILikeRepo

### Post

IPostRepo

### Token

ITokenRepo

### User

IUserRepo

## Model
### Admin

* adminId
* firstName
* lastName
* email
## AuthenticationToken

* tokenId
* token
* tokenCreationDate
### InstagramComment

* commentId
* commentBody
* post
* user
### InstagramFollower

* followerTableId
* user
* follower
### InstagramFollowing

* followingTableId
* user
* following
### Post

* postId
* createdDate
* postDate
* postCaption
* location
* user
### PostLike

* likeId
* post
* user
### User

* userId
* firstName
* lastName
* instagramName
* instagramBio
* password
* dOB
* email
* phoneNumber
* isBlueTick

## dto
### SignInInput

* patientEmail
* patientPassword
### SignInOutput

* status
* token
### SignUpOutput

* status
* message


## Project Summary

* This API is a Spring Boot project that is about Instagram Clone. In this project request is sent from the client on HTTP in JSON body or from path variable and stored in object then response is sent back from the server by JSON format to the client.
