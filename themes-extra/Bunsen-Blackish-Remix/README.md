Bunsen-Blackish-Remix

by hhh (hsumen@bunsenlabs.org)

A gtk theme based on Greybird, designed to be compatible 
with libgtk-3.0 (3.22.*)

Made for BunsenLabs Linux Helium. Includes an Openbox theme
and themes for Xfce4-notifyd in both stretch and jessie.

Designed to be compatible with Debian stretch.

Only tested on stretch with a limited number of applications.

https://github.com/shimmerproject/Greybird
https://www.bunsenlabs.org/

Light text on a dark background will not work with some programs, for
example input fields in Iceweasel/Firefox.

In order to fix this, navigate to

  ~/.mozilla/firefox/${your_profile_folder}

and create the folder and file chrome/userContent.css containing the
following CSS content:

input {
  -moz-appearance: none !important;
  background-color: white;
  color: black;
}

textarea {
  -moz-appearance: none !important;
  background-color: white;
  color: black;
}
