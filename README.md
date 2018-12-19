 #                         -- PUZZLE -- 

 A warden has a challenge for his 100 prisoners. Once per day, he will
 choose one of them at random and bring them to a room with nothing but 
 a light bulb. The prisoner may change the state of the light bulb. 
 Nothing about this room can be seen from the outside; a prisoner must be
 in the room to see the state of the light bulb. Once the prisoners are
 100% sure that every single one of them has been in the room, he will set
 them free. If they are wrong, he will execute all of them.

 The warden gives the prisoners an hour to work on a plan together, but then
 they will never see each other again until the trials are over. The ONLY
 means of communication the prisoners will have with each other is the
 state of the light bulb in the room. There is no trickery going on with
 this puzzle, there is no way around it. The light is the only form
 of communication. What is the strategy the prisoners come up with?

 #                         -- SOLUTION --

 The prisoners choose from among themselves a "reporter". If any of the
 other prisoners go into the room and the light is off, AND they have never
 turned on the light before, they turn it on. Otherwise, they do nothing.
 If the reporter walks into the room and sees that the light is on, he turns
 it off and increments his count. If he sees that the light is off, he does
 nothing (this indicates that no new prisoner has been in the room since his
 last visit). Once his count increases to 99 (plus one for himself), he can 
 be sure that everyone has been in the room.

 So, how long does this take?
