# space_eq_ext
Space Equilibrity Extended

This is a binary patch (space_eq.patch) and a tool to apply it (xdelta3.exe) for Stellaris 3.4.3 (steam version).
It won't work for any other version of stellaris.

Changes:
* AI can build colony ships during the war.
* AI can use colony ships to colonize planets during the war.
* AI won't disband ships when naval capacity is exceeded.



To apply:
xdelta3.exe -d -s stellaris.exe space_eq.patch stellaris_patched.exe

Then replace the old stellaris.exe file in the game folder with the patched one.
