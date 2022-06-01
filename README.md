# MusicPlayer
### This is the Music Player Repository for DSA course project 4th sem 2022

# Problem statement-
   A music player application to be implemented using various data structures. The application includes doubly linked list,stacks and hashing to hash the user password which is used for login/signup of the application.
   
1. This application starts with asking the user to sign up.If the user is authenticated then the user can directly login.
2. Then the user can create a playlist.
3. The following operations can be performed-
   - Add a song
   - Delete a song
   - Display an entered playlist
   - Total Songs
   - Search Song
   - Play Song
   - Create a new playlist
4. Creating playlist has been done using multiple heads
5. Then the user can log out from the appication and login again whenever they wish to do so.

# Intution behind signup/login
This has been implemented using hashing.Here the value is the user's phone number from which the key is being calculated with appropriate hash funtion.
 And the user's password is stored in the key. Collision is been handled by chaining.
## Hash function-
 Key=value % size of hash table<br/>
   where value is user's phone number
   


