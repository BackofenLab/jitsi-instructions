Video conferencing with Jitsi
=============================

Requirements
------------

On a desktop computer/notebook:

- one of the following browsers: Chrome, Chromium, or Firefox

On Android:

- the Jitsi Meet App (available through the Playstore and through F-Droid)


Setting up a meeting room
-------------------------

1. Choose a jitsi server

   https://meet.jit.si/ is the flagship public server of the project running
   the latest code.
   
   https://jitsi.riot.im/ is a good alternative if the first server is
   down or overloaded, or if you are looking for Riot/Matrix integration
   (though that seems rather immature still).
   
   Alternatively, you can host your own server. Jitsi is FOSS and can be
   obtained from https://jitsi.org/.
   
2. Initiate a new meeting room

   On the home page of your chosen server, enter a name for your new meeting
   room, and the room will be created.
   
   Alternatively, just access https://<server-address>/<name-of-a-new-room>,
   and the room will get created, too.
   
   If a room name is already in use, at that time, you will be taken to that
   room instead so if you see other people hanging round in what you expected
   to be a new room, just leave it again and try another name.
   
3. Configuring your meeting

   - Grant Jitsi access to your microphone and/or camera if your browser asks
     you to.
   
   - Click on the *i* icon in the lower-right corner to display room
     information.
     
     Secure the room with a password if you want to, and copy the room
     information to send it around via email to participants (the password, if
     you set one, needs to be shared separately).
     
   - Some more settings are available if you click on the three dots icon, then
     Settings.
     
     In particular, you can set a display name under Profile.
     

Join a meeting
--------------

Your invitation to a meeting should contain the following:

- Room address (consisting of server address and room name)

  If the room is password-protected, the moderator of the room should share
  the password with you separately.
  
- A PIN number for joining via dial-in (Note: dial-in is not available on all
  jitsi servers, e.g., https://meet.jit.si has that feature, but
  https://jitsi.riot.im/ does not support it yet.)

  The invitation may also contain a US phone number for dial-in.
  There are phone numbers available for different countries - ask your room
  moderator for a number in your country.

You can use the link directly in your web browser or in the Jitsi Meet App to
join the meeting.

For dial-in, dial the phone number given to you, then the PIN terminated by a
*#*.

Follow some of the configuration instructions listed in the Setting up a
meeting room section, like granting access to mic/camera and setting a display
name.
