# Game
Text Adventure Game. Learnt object-oriented programming.

Welcome to our brilliant game.
The instructions are as follows:
To go to the garden enter the door and there are two gardens the_garden and smol_garden
To get to the smol_garden enter the tiny door.
To go through a door use (go (the tiny door))


The trees each have a different fruit- elderly has a ripe fruit, young tree has an unripe fruit and the mysterious tree has a toxic poisonous fruit while the other tree has a non-toxic poisonous fruit.

You can use the (find-fruit) procedure that takes in a tree as an input and allows you to ‘pick’ the fruit from the tree. After this you are able to use the (take) function to take the fruit from the tree after picking it. For example (find-fruit (the elderly-tree)) and then 
(take (within (the elderly-tree) fruit))
You cant take multiple fruits from the same tree

For taking a poison fruit you would have to do (take (within (the mysterious-tree) poison-fruit)) 

There is also an (eat-fruit) procedure where it takes the fruit or poison-fruit as an input.

There is also a bench where you can sit down and get up by using (sit) and (get-up) procedures with the bench as an input.

There is also a flower where you can use the (smell) procedure to find out what scent each flower has. (Smell) takes in the flower as an input.

The rabbit can be fed and petted.
To feed the rabbit a fruit, you would have to have the fruit in your inventory first then use 
(feed-rabbit) procedure with the rabbit and fruit as inputs in this order.


To feed the rabbit the poison fruit its the same but it is (feed-poison-fruit)
With the rabbit and poison fruit as inputs.

To pet the rabbit just use procedure (pet-rabbit) and rabbit as its input. You can’t pet the rabbit more than once.
