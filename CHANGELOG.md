# Changelog

## Release 7.46.0

### Changes

* Shynixn/BlockBall#739 Added a new /mcbasketball rejoin command to rejoin the last game you played if it is still running. This command will also restore you to the same team you played on. This is not enabled per default and you need to give players the new permission mcbasketball.rejoin.<arena_name> to allow them to use it. You can also give the permission /mcbasketball.rejoin.* to allow players to rejoin any arena they played in.

---

## Release 7.45.0

### Changes

* Shynixn/BlockBall#768 Added support for Minecraft 26.3.x

---

## Release 7.44.3

### Changes

* #763 Updated the GeyserMC zip file to support the latest GeyserMC by switching to mapping files for the ball texture.
* #722 Changed `/mcbasketball club join <arena> <club>` to support referee now. Club VS club games can now also be played with a referee. The referee does not need to be a member of any club and just uses "referee" as the club name.

### Bugs/Issues

* #765 Fixed ball is not correctly dereferenced when a player leaves the game while grabbing it.

---

## Release 7.44.0

### Changes

* Initial release of MCBasketball

---
