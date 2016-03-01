#User Resource:
  - Author:  Richard Kellermeyer
  - Description: User resource specification.
  - Version: 1.0
##Attributes:
  - id (PK)
  - First Name
  - Last Name
  - Alias (Username)
  - Email
  - Address1
  - Address2
  - City
  - State
  - Zipcode
  - password
##Relationships
  - Groups (XTable GroupsUsers -> group_id, user_id)
  - Journal Entries (FK)
  - Notes (FK)
  - Profile (XTable ProfilesUsers -> profile_id, user_id)
  - Projects (FK)
  - Users (XTable UserConnections -> a_id, b_id)
