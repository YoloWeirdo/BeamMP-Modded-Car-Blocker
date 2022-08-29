# BeamMP-Modded-Car-Blocker
BeamMP plugin that blocks any modded car from being spawned in. No more blobs! There's also ability to stop any other car, prop and trailer from being spawned by removing them from any of the arrays. This can prevent grieving with the bigger props.

If your server has modded cars, don't worry. You're able to whitelist any mod you like by getting its code name, this isn't always the name of the car. Make sure to open the mods .zip file, then go to the vehicles folder and the car name will show up.

There's also some extremely simple logging. This can help with finding a vehicles name or a player who consistently tries spawning modded cars. 
By default any time someone spawns a mod or blacklisted car a message will be sent in the server console and the 'logs.txt' file (will be created in your main BeamMP directory) will also get that same message added.
The car name in those messages are the names you should whitelist if needed.
You can change the first line in the main file to only log to the file or console or not log anything.
