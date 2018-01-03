# Football 5-a-side Random Team Picker Project
This is the technical project set on our penultimate day at the Coding Fellowship to make for January 7th

## tecnologies used
react, redux, jsx, css, sass, gulp, css animations, git



## The brief

The exercise is to create a tool which randomly picks 5-a-side football teams from a list of 10 names.
It's up to you how you implement this, with JavaScript, PHP, as a web page, or as an app.

### Advanced features might include:

    1. support for n-a-side, where a list of any length can be split into two teams
    2. support for balancing of the teams, where some measure of each player's strength is used to allocate teams fairly


### Some suggestions

I would suggest you look to demonstrate clear thinking and good quality code.

If your tool requires a particular environment to run (e.g. Node or PHP) 
then this should be documented, or provided (e.g. Vagrantfile). 

In short: I shouldn't struggle to get it working on my local machine.


## Wireframes:

![Demo](https://user-images.githubusercontent.com/26763021/34521518-f97e4088-f085-11e7-937b-10b21d12942a.png)
![Demo](https://user-images.githubusercontent.com/26763021/34521517-f962918a-f085-11e7-9778-cb628c70ce69.png)


# My initial notes

I would like to create the app with options for n-a-side teams, also for randomly picking team names, and creating top-trump style skills of players so that they can be balanced against eachother.

Need to do some research into what apps are out there and what elements it would need.

Initial names of the app could be: FTBLL-TM-Pckr, The beautiful game team picker (sub header), need to look up words that are synonymous with Football!

The MVP is randomly picking a 5-a-sdie football team from a list of 10 names, so initially I need:

1. to have an input where the user can enter 10 names, (should the names default to 10 initially or be empty? 
    -should this be single line? or have 10 spaces or 10 inputs? or a large text box that fits 10 names?

2. It should have a button that has 'Generate Team' or 'Pick your team' on it, which when pressed will places the 10 names into 5 a side teams.

### Additional Notes on Saturday 23rd after 1st draft of Wireframe (see pdf attached) initial set up and first changes:
1. have set up SASS on my project
2. Also have set up a background and the logo and favicon - this has allowed me to help with the formatting
3. Adding an input and thinking about the best way the user interface could work.
4. Will now do some more research into other apps to get some more ideas.

### Sunday 24th Notes:
1. Have managed to get the input to add names to an initial list below.
2. Need to write some logic that disables the add button after 10 names are entered.
3. Would like to have some visual boxes, maybe dotted lines in the space in the middle for the start of the page, so that it's obvious there whould be players names entered. (Will make a new wireframe draft 2).
4. Need to figure out where to put randomise button.
5. I have to make sure that the text entered does meet text requirements, should be no longer than 50 characters, and must be letters, not numbers or spaces or empty.

### Tuesday 26th Dec Notes:
I got a bit stuck with adding in Redux, and after lots of back and forth and looking over older work and tutorials with React and Redux, I kind of want to go back to the drawing board, both in terms of layout and in terms of approach. I will remake a 2nd draft of the wireframe first thing tomorrow (it's 23:14) and re-structure the app in the morning too! I want to make it more horizontal so everything can fit within the fold, also have 10 inputs, so that it's clear immediately that the app needs to take 10 names.

### Monday 1st Jan Notes:
Since Boxing Day, I went over a lot of other React and separate stuff, I started again a couple of times after going back over Redux and React tutorials and workshops. I decided to go back to simplyfying the idea. I've now got to a stage where the user can enter names, the names get outputted to the left of the screen, these names come with an Edit and a Delete button. Then when 10 names have been entered the Reset and Generate buttons appear. Reset takes everything but the header and the input away from the screen, and Generate button generates two teams, these will then be shuffled when the user represses the generate button.

Things TODO:
1. Try and get a balancing skills section in, with stars, or points
2. Add some more styling to the scoreboard area
3. Refactor a lot of the code
4. Move the MapDispatchToProps and ..State to their own pages
5. Try to put the functionality for the randomising into a smaller function from lodash - called shuffle

### Checklist
1. Check accessibility and responsiveness when the project is nearing the end.
2. Testing with friends, family and unit testing
3. Write up how to run it on another machine
4. Send supporting documentation


## Styling
There could be a background of a birds-eye view of a football pitch - so green grass with white stripes...can this be done with CSS? Ideas: https://codepen.io/eyecandy91/pen/dXLjNG  https://codepen.io/oloman/pen/ynJcl  https://codepen.io/paulnoble/pen/PwOxOY. With CSS I can easily do stripes like this: https://thumb1.shutterstock.com/display_pic_with_logo/3910382/568052803/stock-vector-football-pitch-icon-on-white-background-football-pitch-sign-symbol-568052803.jpg.

Football type fonts: https://www.designboom.com/wp-content/uploads/2014/07/dutch_home.gif

possible Google font: https://fonts.google.com/specimen/Bungee+Inline  https://fonts.google.com/specimen/Anton  

