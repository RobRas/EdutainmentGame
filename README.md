Please claim things that you're working on!

CONCEPT OVERVIEW:
--------
- "battle arena": opponent, player, math question in the middle, text box to answer question, time limit bar
- grade = score, as you correctly answer your opponents grade goes down until they have a 0
- in battles, player can choose what type of math they are solving in a menu at bottom (+, -, *, /)
--- the game gives them time to prepare when they change math type (3, 2, 1...)
- overworld... player movement, beating back of class kids to front of class (smarter)
-- kids at desks are the ones that will fight you
- random characters in overworld with dialogue on edges of class 
- start with 50/100 health (F), each fight levels you up one grade and gives you more health
- missing an easy question hurts less than missing a difficult one, but difficult correct answers do more damage
- final boss is teacher: teacher chooses what type of math you must do (you go into this fight with an A)

TASKS:
------
----Misc:
- "Are you a boy or a girl?" different sprite based on response - Nancy

----Overworld:
- move dialogue boxes to bottom?
- block player from walking on the front wall
- change battlemate to classmate after the fight ("aw, I lost")
- fix math difficulty - Nancy
- stop sprite repeats
- You win! Screen once you get your grade to 100% after professor fight
- Optional: Fix character animation clipping

ASSETS:
-------
We are doing an 8-bit style!
- Music for overworld
- Fight sounds
- load screen - Nancy

COMPLETE:
---------
- State machine menus - Al, DONE
- 8 bit bitmap font - Cherie, DONE
- collision detection! -Al, DONE
- generate math questions - Nancy, DONE
- Display dialogue in box at bottom of screen -Al, DONE 
	(Dialogue is diplayed below the person the player is talking to)
- overworld students - Cherie, DONE
- implement student sprites - Nancy, DONE
- main character walking sprites - Nancy, DONE
- classroom objects: desks... - Cherie, DONE
- size up students better - Nancy, DONE
- initiate a fight: walk up to student, press enter. Some dialogue, then start questions -Al, DONE
- player movement -Al, DONE (change to WASD later?)
- capture player input in text box, -Al, DONE
- player pushes enter to submit answer, -Al, DONE
- display math questions one at a time -Al, DONE
- test to see if the player was correct - Al, DONE
- player health increases once fight is won -Bobby, DONE
- Graphic to show who you can fight currently (thought bubble, or '!') -Bobby, DONE
- Cannot fight people again *if you win* - Al, DONE
- Fixed dialogue boxes - Bobby, DONE
- display 5 math questions per student - Al, DONE
- thought bubble - Nancy, DONE
- player health goes down if incorrect answer input, -Al, DONE
- classroom background - Cherie, DONE

DESERTED TASKS:
---------------
- arena background
- FAIL or PASS for end of fight
- optional: animations for the 'fights' (eg. happy/sad player sprite when questions answered)
- optional: more detailed sprites in fights
- Optional: save and load files?
- allow the player to choose what type of math they are solving with a click menu at any time
-- Default to addition
- Optional: time limit on answering math questions, player loses health if time runs out
- Optional: time limit is a bar on the screen
- Optional: "What is your name?" store and use in dialogue
