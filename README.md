# Nuketown Perks Manager
A small little thing I made where you can choose various options on how Nuketown drops the perks.

## Installation
Download nuketownperks.gsc and put it in your Plutonium T6 scripts folder

```%localappdata%\Plutonium\storage\t6\scripts\zm\zm_nuked\```

(if the folder isnt there create them)

## Configuration
The only dvar is ``nuketown_perks_mode`` and can be used as ``set nuketown_perks_mode number`` in the console or server config

* 0 - Default, Randomized every few rounds like normal
* 1 - All perks and pack spawn in at once
* 2 - Perks fall down after every bell chime (aka every 100 Zombie kills)
* 3 - A perk after every round
