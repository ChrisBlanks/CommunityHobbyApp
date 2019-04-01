# CommunityHobbyApp
**Chief Developers:** *Chris B*, *KJ D*

**A web application for connecting people who share similar hobbies.**

## Details/Features (3/29 Meeting)

- Storage of message history on remote server
- Public & private groups
- Public groups are created by developers & can be requested
- Groups will be deleted after a certain amount of inactivity
- Threshold set on storage for message history
- Username, hobbies, etc. will be collected at account creation
- Groups will be only accessible for people in a certain area (gps coordinate will be used)

## Specifications (4/1 Meeting)
- **2** Months of inactivity until private groups get deleted
  - Notification sent to user as warning
- Private groups have a cache that is stored on **their** respective devices
  - All history is stored on respective devices
- Public Groups managed by **Developers**
- Admin or private groups is **Creator** of the group
  - Can be transferred between users
  - Can kick people out of Groups
  - Developers are super users
- **Personal/User** information stored
  - Username, Password, Email Address
  - Hobbies Interest
  - Current City
  - Mac Address
  - ?Profile Picture?
- **Award System** implementation
  - Trophies for days active and membership
  - Trophies for users ad groups
- _Login Page_
  - Username and Password
  - Account recovery info sent to Email
- _Landing Page_
  - Your Groups, Public Groups, Potential/Recommended groups
  - A link to configure account info
  - Search bar for finding public groups
- _Creation of group / group Page_
  - Name of groups
  - Typical meeting place
  - Description of group
  - admin username
  - Number of people in group
