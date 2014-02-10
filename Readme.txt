==================
WoW Machinima Tool
------------------

Run the app.

If asked use:
User: testclient
Password: 3D6D40013A462CFF

Current Version Have:
Full 2.4.3.8606 Support

======================
	Commands
======================
CAMZ [AMMOUNT]
	Changes the Z distance between the camera and you.
	Tip: Changing this to a negative value makes a "scope" effect

CAMFOV [AMMOUNT]
	Changes the camera's Field Of View

CAMROTZ [AMMOUNT]
	Changes the camera Z rotation

CAMROTY [AMMOUNT]
	Changes the Camera Altitude

CAMAUTOPANX [AMMOUNT]
	Camera Automatic Pan in X

CAMYAWX [AMMOUNT]
	Yaw the camera angle.
	(changes the default Zero)
CAMAUTOROTCY [AMMOUNT]
	Automatic Rotation Around Cam Center

CAMWALKROTTY [AMMOUNT]
	Walk Rotation Around Toon Center

CAMROTTY [AMMOUNT]
	Camera Rotation Around Toon Center

CAMROTZ [AMMOUNT]
	Camera Rotation around Z (debricated?)

CAMPANX [AMMOUNT]
	Camera Pan in X

SPECTATE
	Toggels Spectate Mode

SPECSPEED [AMMOUNT]
	Changes the Spectate Mode Speed

SPECZOOM [AMMOUNT]
	Changes the Spectate Mode zoom

ANIMATION [ANIMATION ID]
	Changes your chars animation
			ID	FUNC
		_report("0 - Normal Stand")
		_report("1 - Talk / Conversation")
		_report("2 - Bow")
		_report("3 - Wink")
		_report("4 - Succes")
		_report("5 - Talk / Conversation - Shout")
		_report("6 - Talk / Conversation - Nod")
		_report("7 - Drink at table")
		_report("10 - Dance")
		_report("11 - Laugh")
		_report("14 - Fuck You!")
		_report("15 - Roar")
		_report("16 - Kneel")
		_report("17 - Kiss")
		_report("18 - Cry")
		_report("19 - Chicken")
		_report("20 - Beg / ?")
		_report("21 - Clap")
		_report("22 - Shout Far")
		_report("23 - Flex")
		_report("24 - Shy")
		_report("25 - Point")
		_report("27 - Fight Ready")
		_report("28 - Chop Wood")
		_report("29 - Point")
		_report("33 - Fight Take Damage")
		_report("34 - Fight Take Damage2")
		_report("35 - Fight Fist hit")
		_report("36 - Fight 1H hit")
		_report("37 - Fight 2H hit")
		_report("38 - Fight 2H hit")
		_report("36 - Parry")
		_report("43 - Shield Block")
		_report("44 - Fight Ready fists")
		_report("45 - Fight Ready 1h")
		_report("48 - Archer Ready")
		_report("51 - Fight Fists Hit")
		_report("53 - Battle Roar")
		_report("54 - Fight 2H JumpHit")
		_report("60 - Kick")
		_report("61 - 1H Hit")
		_report("64 - Stunned")
		_report("66 - Salute")
		_report("69 - Create")
		_report("70 - wave")
		_report("71 - Succes")

	You might be able to find new animations
	Please report them to me so i can add them to the tool

INJECT
	Injects the WoWMachinima DLL into wow.exe to enable weather spawn
	(Do Only Use Command ONCE per session)
	(Restart wow to remove it, Eject command comming soon)

WEATHER [WeatherState] [weatherIntensity] 
	(Use command "INJECT" once before using this feature)
	Changes Weather to WeatherState with Weather Intensity
	Set to "Weather 0 0" for clear sky.

	WEATHER_STATE_FINE              = 0,
	WEATHER_STATE_LIGHT_RAIN        = 3,
	WEATHER_STATE_MEDIUM_RAIN       = 4,
	WEATHER_STATE_HEAVY_RAIN        = 5,
	WEATHER_STATE_LIGHT_SNOW        = 6,
	WEATHER_STATE_MEDIUM_SNOW       = 7,
	WEATHER_STATE_HEAVY_SNOW        = 8,
	WEATHER_STATE_LIGHT_SANDSTORM   = 22,
	WEATHER_STATE_MEDIUM_SANDSTORM  = 41,
	WEATHER_STATE_HEAVY_SANDSTORM   = 42
	WEATHER_STATE_THUNDERS          = 86,
	WEATHER_STATE_BLACKRAIN         = 90,

TIME [HH]:[MM]
	Changes the current time.
	Remember to use the right format (ex; Time 12:35)

TIMESPEED [AMMOUNT]
	Changes the speed of the time, setting it to 0 will stop the daycycle.

BLUR [AMMOUNT*]
	Enables the Blur shader by turning Drunk mode on.
	Will affect chat and movement.

CHARSCALE [AMMOUNT]
	Changes the Char scale

CHARROTSPEED [AMMOUNT]
	Changes the speed of your chars rotation

CHARREMOVE
	Stop's the Char texture rendering leaving only Equipment visible

DIE 
	Simulate Death

SHS [NAME]
	Save a hotspot with the desired name
	(only spectate mode)

HS [NAME]
	teleports to the hotspot instantly
	(only spedtate mode)
========================
	Known Bugs.
========================
The rotation sliders toggle movement when less than 2% to center
The rotation sliders + the rotation Control can at times lock itself in the UP/DOWN axis
The rotation sliders + the rotation Control will when first used do a offset jump.
