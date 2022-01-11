# Instructions for homework due Jan. 13, 2022

  ** Here are the instructions for this assignment **

  _ Please read the whole thing and once you think you are finished, read the whole thing again. _

  ## Steps
  1. Make up a Dwarf structure with Name, favorite song, favorite color all of type string.  And an attribute for weight (an integer of some kind). And two bool attributes for wears glasses and has a beard.
  2. Make an array called dwarfs of size 7.
  3. Write an initialize function called init_dwarf that takes a Dwarf reference parameter and string params of name, song, color, int weight and two bools for glasses and beard.
  4. Call the init_dwarf function with the correct parameters for each of the 7 dwarfs.
  5. Write an operator<< function for Dwarf (see example below for Song and adapt that)
  6. Write a for loop to iterate over the dwarfs structure and print each of them out.
  7. Ensure your program compiles, add your name and date and submit your program.


  For help on declaring an array see: [Array Geek](https://www.geeksforgeeks.org/arrays-in-c-cpp/) or [Array c++] (https://www.cplusplus.com/doc/tutorial/arrays/)

  For help on for loops you may want to look at:  
  [w3 for] (https://www.w3schools.com/cpp/cpp_for_loop.asp) or 
 [Geek loops] (https://www.geeksforgeeks.org/loops-in-c-and-cpp/)


  See also the program we did in class for top 10 songs

  Here is the operator<< function we did in class for a Song
```c++  
// Note: both the ostream and song are passed by reference  
//       That is why they have the &
// Also note: the return type of the function is a reference
//            to an ostream, same thing as the first parameter
ostream& operator<< (ostream& os, const Song& song) {
    os << "Title:" <<song.title << " Singer:" << song.singer << 
    " Composer:" << song.composer;
    return os;
}
```

Seven Dwarfs (Snow White is MIA):  
  1. Doc  
  2. Grumpy  
  3. Happy  
  4. Sleepy  
  5. Bashful  
  6. Sneezy  
  7. Dopey  

Doc's favorite song is "Heigh-Ho, Heigh-Ho, It's Off to Work We Go"  
Grumpy's favorite song is "Let It Go"  
Happy's is "Walking on Sunshine"  
Sleepy's is "No Sleep Till Brooklyn"  
Bashful's is "Creep"  
Sneezy's is "Fever"  
Dopey's is "Dazed and Confused"  

Colors:
Doc likes orange.  
Grumpy likes red.  
Happy likes yellow  
Sleepy also likes green.  
Bashful likes blue.  
Sneezy likes brown.  
Dopey likes light green.  

Weight:
Doc     wights 51 lbs
Grumpy  wights 42
Happy   wights 71
Sleepy  wights 50
Bashful wights 62
Sneezy  wights 46
Dopey   wights 40

Sneezy doesn't have a beard, the others do.
The only one that wears glasses is Doc

Their origional names 
Doc     Blick
Grumpy  Glick
Happy   Flick
Sleepy  Snick
Bashful Plick
Sneezy  Whick
Dopey   Quee


  Include an image by placing it in the `assets` folder.

  For example, here is the Replit logo:

  ![alt text](assets/logo.png)
  
  