## Scriven42's Modified RePhone Kit Create Source Code

-Added a keyboard to type new messages, not just send pre-written canned messages.
-Changed the "no sim" background to C_PINK, as a marker.
-Added a second home screen, and rearranged the icon layout. New layout is:
	Home:	Call, Settings, SMS
		Actions, ITTT, Home2
	Home2: Home, Sensors, GPS (label only, does nothing)
		  All Unused

---

If you want to install without compiling yourself, please try these steps:

1) Copy the "RePhone_Create_Source_Code/ARM/RePhone_Create_Source_Code_default.vxp" file to the "\MRE" subdirectory on your RePhone.
2) Edit the "autostart.txt" file to read:

			[autostart]
			App=C:\MRE\RePhone_Create_Source_Code_default.vxp
