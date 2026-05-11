# PhindThePhighter

## Wheres Waldo? 
  Wheres Waldo is The 7th project as well as a fullstack project in The Odin Project Path this is to showcase testing routes and controllers and seamlessly connecting both backend and frontend

Live: https://phindthephighter.netlify.app/
<br>
Frontend repository: https://github.com/SeasonedSoup/PhindThePhighter_front
<br>
Backend repository: https://github.com/SeasonedSoup/PhindThePhighter_back

Tech Stack Used <br>
-React <br>
-Express <br>
-Prisma <br>
-Postgres <br>

## Overview 
  The project is about finding fixed specific characters inside a designated map, the way I went with solving this is putting a PhighterLocation table on postgres 
  containing the correct coordinates and validating it inside the server through comparison. Getting the client coordinates for the user during gameplay was the hardest as I had to find out how I would be able to display the hitbox 
  inside the map with specific browser. I found out the way to use it is using the getBoundClientRect method to get the maps coordinates as it returns normalized coordinates meaning width and height of the img does not affect coordinate 
  complications in the client. There is no implemented user login or sign up implementation in this project but added security to prevent hacked scores to surface. The security for the time taken is tracked in the server rather than client as well as utilizing 
  a jwt to ensure the client cant just make all characters found and be able to create a leaderboard score as they would need the jwt for the server to verify otherwise it would prevent them from submitting the form. 

  


