# ChildServ bot for matrix Degeneracy room (and it's sisters room)

This bot is here to help welcome members that log in the room and leave because
they feel the room is dead.

## Changelog

### v1.0.0

- Use the https://github.com/JojiiOfficial/Matrix-ClientServer-API-java library
- Don't do much, the API is old and have bug in the room creation api call

### v1.0.1

- Use the https://github.com/ma1uta/jmsdk/ SDK
- ✅ Can create welcome DM room
- ✅ Send welcoming message in HTML after a Markdown transformation
- ✅ Can re-join on a kick
- ✅ Simpler config file
- ✅ Have debug mode to help don't disturb the deployed bot during dev phases
- 🚧 Skeleton to process encrypted messages payloads

### v1.0.2

- ✅ Will leave welcome room 1 hour after the room creation
- ✅ Switched config to NBT
- ✅ Have a list of rooms with modes
- ✅ Have a list of admin member nick that have the right to send commands
- ✅ Command engine based on Brigadier from Mojang
- ✅ Ban list functionality that will synchronise ban across a list of rooms