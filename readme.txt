==================
QUICK REFERENCE :
==================
	Item pickup : hold down the Action Key (+action) and walk over the item.

	Reloading : Once out of ammo, try to fire the weapon again.
                To reload before you are out of ammo, use the command "reload"
		For non-clip using guns, it will auto-reload additional shells/bullets.
		To stop this, hit fire/fire or hold down the Action Key.

	Opening Doors : Walk up to door and hit the Action Key (+action)

        Walking : Hold down the Action Key (+action) to walk (less noise)

	Bandaging : Free your hands and the hold still for a moment.
		Once it has begone to bandage, you are free to move again.
		Note that you do not have UNLIMITED bandages. 
		To get more, search a body.

        Corpse Searching : Walk up to the body and hit the Action Key (+action)
		A menu will come up showing what items are on that body. 
		Use [ and ] keys to go through items and ENTER/BACKSPACE to take an item.

	Climbing Up : jump and then hit the Action Key, while near the edge of something.
		Hitting multiple times sometimes helps...

	Ledge Grabbing : hit the Action Key while near the edge of something to try and grab it. 
		Must be off the ground of course.
		To climb up after grabbing a ledge, press forward or hit jump.
		To let go, hit crouch.
		You can still move side to side while hanging on, 
		but can't fire or select weapon etc.

	Max items : There is no individual max on ammo etc!
		Ammo, bandages and knives all use the same space, so be careful what you carry.
		eg. Why have 14 shells when you have an MP5?

	Two Weapons : This version only supports dual weapons
		Dual = Use the gun twice

	Jump Kick : similar to AQ2's jump kick. Jump into an enemy and auto-kick their gun away

	Kicking : hit the Action Key while facing an enemy to kick them

	Healing Team mates : hit the Action Key while facing a team mate to use bandages on them
		Only works if you're hands a free and you both must remain still.

	Grabbing : with your hands free, hit "+attack2" while you're facing the front of an
		enemy. If they arn't firing, you'll grab their weapon and kick them.

	Neck Snap : with your hands free, hit "+attack2" while you're facing the back of an
		enemy. Will only work if they are not already in combat and haven't seen you.
		Instant and a pretty silent kill...

	Back Stab : while using a knife in slash mode, hit "+attack" while you're facing the 
		back of an enemy. Will only work if they are not already in combat and haven't 
		seen you. Instant and a pretty silent kill...

	Arm wounds : If you shoot someone in the arm, and cause enough damage, they will 
		drop their gun. Arm wounds will also stop you using twin guns...

	Leg wounds : Slow you down, reduce your jump.

	Head shots : Will you kill you most of the time. If not, then you get concussed.

	Radio : usage 'radio <soundfile>'
		The 'soundfile' should be located in your 'sound/player/<gender>',
		'gender' being male or female, chosen by the normal quake2 command, gender.
	

==================
BASIC COMMANDS :
==================
	+action - The ACTION KEY (default : KP_INS)
		Used for picking things up, searching bodies, climbing etc. 
		USE THIS TO OPEN DOORS!

	+attack2 - handles a second weapon and/or mode (default : MOUSE2)

	drop_weapon - drop your current weapon or weapons
		Will also bring out a weapon if you arn't currently holding one
		Allows you to bandage quickly. (default : KP_END)

        reload - reload your gun(s) before they run out of ammo.
		
	hands - same as "drop_weapon", except this tries to put your guns away first.

        NOTE : You still need the normal inventory keys
                for dropping ammo/armor etc...


==================
SMART AUDIO :
==================
        Smart audio is a semi-auto radio communication system. Everytime
        something happens to you or near you, Smart Audio chooses what
        message you would send to other players.
                For instand : your buddie just bought it.
                        SA chooses 'Team mate down' as your message.

        To make it more useful, once a request/reply has been sent, anyone
        receiving it will get an on-screen indicator of your relative
        position (when you sent the message).

        SA COMMANDS :
                reply - report your situation to your team mates.
                        (Taking fire, hurt, just saw a team mate die etc)

                request - ask for team update, assistance or say 'yes' to
                        someone else's request for help.
