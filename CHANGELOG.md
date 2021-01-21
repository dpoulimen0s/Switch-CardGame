# CHANGELOG
* v2.0.2 [2021-01-21]:Updates
  - In cards.py line 13 i have fixed the def with the right value this time.
  - In test_switch.py lines 155,156,157 changed K to Q.
* v2.0.1 [2021-01-19]:Updates
  - In players.py line 50 changed this return random.choice() into this return random.choice(choices).
  - In cards.py line 16 removed value from parameters.
  
* v2.0.0 [2021-01-17]: Major Updates 
  - In switch.py line 52 changed (name) into [name] and added (typ) as well.
  - In user_interface.py line 113 changed the for loop into this: for i, card in enumerate(cards): .
  - In user_interface.py line 127 changed "for player, idx" into "for idx, player".
  - In user_interface.py line 128 fixed the print statement.
  - In user_interface.py typo in line 1.
  - In cards.py line 11 removed double "2" from the values.
  - In switch.py line 74 changed "elif won" to "elif not won".
  - In switch.py line 79 changed players[1] to players[i].
  - In switch.py line 111 broke down the long line to fit  the character limit per line.
  - In switch.py line 97 changed "==" to "=".
  - In switch.py line 161 changed False to True. 
  - In README.py line 37 fixed a typo.
  - In user_interface.py line 2 removed unused "import random".
  - In switch.py line 68 added a space due to PEP 8: E261.
  - In switch.py line 185 added "global i" due to a warning from line 202.
  - Description added in README.md file line 30 for A card. 
  
* v1.1.1 [2021-01-17]: Errors have been fixed that prevent the program from starting
  - In switch.py line 285 added the missing parenthesis.
  - In players.py line 50 added the missing parenthesis.
 
* v1.1.0 [2021-01-17]: File Updates
  - Updated LICENCE.MD file accordingly.
  - Added REPO.txt with the link to Nucode.
  - Added folder doc and I have created doc folder with Report.md file as requested.

* v1.1.0 [2019-11-08]: Added a SmartAI computer opponent
  - Added strategy players.SmartAI.
  - None of the bugs have been fixed.

* v1.1.0 [2019-10-25]: First major release.
  - This version is known to contain some bugs.
