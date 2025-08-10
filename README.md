# **WHAT DID IT DO**
It adds support for motion NBT to the world, which makes your mini-game maps easier to make.

# **HOW TO USE IT**
Add tag to what entity that you want to move.

here are all the available tags:

-"mot" : Throws entities in the direction of your gaze

-"random_mot","random_mot_mid","random_mot_big" :Throws entities in the direction of your gaze, but adds randomness

-"one_random_mot" : Add randomly but it doesn't work when applied to multiple entities

-"random_exp" : throws entities to a random direction, if you do this to multiple entities at once, then it will look like an explosion!

-"trace": Throw entities to the nearest player

-"away": Throw entities away from the nearest player

Here's an example of throwing a snowball:

/summon snowball ~ ~ ~ {Tags:["random_mot"]}
