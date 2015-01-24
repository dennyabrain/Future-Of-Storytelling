#Results for the Detective Story
# objects selected were 'Detective', 'Murderer', 'Knife'
# blocks/Settings selected were 'Mansion', 'Basement' ,'Bar'

assumptions made :
1) Order within each block does not affect the story itself. For instance (Detective, Murderer) or (Murderer, Detective) will mean the same thing
2) Allow only unique objects. For instance, user cannot put the same object (Murderer,Knife) on all the three blocks.

##Block Arrangement 1 ["Mansion", "Basement", "Bar"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


##Block Arrangement 2 ["Mansion", "Bar", "Basement"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


##Block Arrangement 3 ["Basement", "Mansion", "Bar"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


##Block Arrangement 4 ["Basement", "Bar", "Mansion"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


##Block Arrangement 5 ["Bar", "Mansion", "Basement"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


##Block Arrangement 6 ["Bar", "Basement", "Mansion"]

(Detective,Murderer) (Detective,Knife) (Murderer,Knife)

(Detective,Murderer) (Murderer,Knife) (Detective,Knife)

(Detective,Knife) (Detective,Murderer) (Murderer,Knife)

(Detective,Knife) (Murderer,Knife) (Detective,Murderer)

(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)


Limitation/Learning : 

When you look at a case like
(Murderer,Knife) (Detective,Murderer) (Detective,Knife)

(Murderer,Knife) (Detective,Knife) (Detective,Murderer)

As the user plays, how does the system know which story to play out when only the first block is set up. Do we ask the user to 
put all the objects and then begin the story? In that case it becomes non interactive after the first interaction.
