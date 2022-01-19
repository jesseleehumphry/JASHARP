# JA#

JA# is a fork of JA++ developed to return to a form closer to JA+ while adding a few elements that are intended more for the roleplaying community that still frequents the game.

The mod will intend to address the following shortcomings that JA+ and JA++ had in common.

## Server-Side

* Ability to auto-login all players into a default clan chat if they don't have a cp_clanPwd set. 
* Ability to grant particular commands, like /ammerc and /amtele, to all players regardless of admin login level
    * Alternatively, auto-login all players into the admin level that has these commands
* Ability to set the clan tag, limit the number of varied clan channels, and automatically assign the current channel to the <> tag.
* Ability to use some GalaxyRP-esque features, like a /me text emote
* Expose more animations to the /am system
* Customize the submittable length of text in the server
* Pseudo-account system that tracks by IP, or possibility of SQL-based account
   * Account tracks kills, deaths, total time played, and a player name that a player can claim or change at any time. This does not take on the in-game display name.
   * Set up a database that can push this to a JSON object, which can be gathered via REST verbs or displayed in an on-server HTML page to be embedded in an iframe.


## Client-side
* Dramatically increase the customization selection limitation based on the player's hardware or desires.
* Tie text triggers to colors via .cfg
  * Player can link an inline phrase or symbol that would automatically trigger a temporary change in color or a permanent one.
* 

# Roadmap

## Server-side
* Expansion of animations to accomodate roleplaying groups
* Granularity of admin powers for finer control over server staff

## contributors
* JesseLeeHumphry (lead)

## credits
* JK2MV
* loda
* OJP
* OpenJK
* JA++
