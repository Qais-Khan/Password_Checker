# Password_Checker
An automated password checker to scan for compromised passwords and advise you to change compromised passwords

Takes a list of passwords input by the user in the shell, hash them, send a small portion of the hash to the API, receive a full list of matching potential hashes, and search for hash match in the list of received hashes

It displays the amount of times a password has been breached or if it has not been breached
