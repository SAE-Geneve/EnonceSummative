# 924-4FSC0PF001-Summative

1. Find the issues in the repository and make it work.
2. Factorize that monolitihc main into functions and classes
3. 3 hours

The program is a "Duck Shooting Game".
You can shoot ducks clicking the mouse

https://github.com/user-attachments/assets/8b0b584a-9b47-4f3d-a97b-faa7e442966a

**You have to make it work as described above**

## Task 1 : Find the issues in the repository and make it work.
There are 3 kinds of bugs :
* **syntax and linking issues :** the code does not compile. These issues can be complex mistakes, as they can be trivial typing errors. find them and make it compile.
* **runtime issues :** program compiles, run but crashes after a while
* **functional issues:** program compiles, run but does not do what it is expected, compare with description and video

### if you do not succeed to fix all required issues, you can download the following repository. As a consequence, your maximum note will be automatically truncated to 5. 
[Task2 Repository](https://classroom.github.com/a/1aXrzuiu)

## Task 2 : Factorize
* Create the following class : game, projectile, invader, starship and move the related code
  * ``Game`` class handle the core programing elements :
    * 1 method setup : setup SFML variable and others classes
    * 1 method loop : handle all the cyclic and repeated programming elements
    * every gameplay eelements (Score, timer, etc.)
    * input events (trigerring other classes)
  * ``Background`` class handle ALL programming elements required to display of the decoration background
    * curtain
    * top curtain
  * ``HUD`` class handle ALL programming elements required to display the informations to the player
    * Targets shot
    * Target missed
  * ``Target Manager`` class handle ALL programming elements relative to targets
    * vector of targets, and accessors
    * add a target
    * remove a target

## don't forget use all tools on your disposal, debug windows and tabs, breakpoints, or your own projects and lecture ressources.
## uses of Chat GPT, or student-to-student communication is strictly forbidden 
