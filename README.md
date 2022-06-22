# so_long

We had to create a 2D game. It uses the MLX library and PNG file for images.  
The goal is to collect all the coins in the game and then take the exit.  
The numbers of movments is displayed in he terminal.
  
⚠️ If all the collectibles aren't collected you can't take the exit.  
⚠️ The program work on mac and it's not portable.  
⚠️ The map taken for the game need to be in `.ber` format.
  
The game is only playable with a keyboard.  

Keys :  
  - `w` : Move up.
  - `a`: Move left.
  - `s` : Move down.
  - `d` : Move right.
  - `ESC` : Shut down the window.
  -  <img width="23" alt="Screen Shot 2022-06-15 at 11 30 48 AM" src="https://user-images.githubusercontent.com/107465256/173794761-8513cff2-1e15-417b-96cc-ca32552097af.png"> : Shut down the window.

Map config :
  - The map is surronded by wall : `1`.
  - The map contains only one exit : `E`.
  - The map contains only one player : `P`.  
   &emsp;➡️ If there are several player only one is kept.
  - Yhe map contains at least 1 collectible : `C`.

### Examples :  

Raw map :  
  
<img width="447" alt="Screen Shot 2022-06-15 at 11 45 57 AM" src="https://user-images.githubusercontent.com/107465256/173797992-be85b6ad-01ff-4740-9573-af2f645817c5.png">

Launched game : 
  
<img width="1084" alt="Screen Shot 2022-06-15 at 11 43 04 AM" src="https://user-images.githubusercontent.com/107465256/173797441-a548eb0f-c4a2-4ac3-b6c7-24d7ae5e6078.png">
    
    
Grade :

<img width="192" alt="Screen Shot 2022-06-14 at 2 40 21 PM" src="https://user-images.githubusercontent.com/107465256/174995497-76814c10-b1ff-4574-b1e9-f1a56dbf3d1c.png">
