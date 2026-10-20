# HEARTS OF IRON IV PARADROPPER ROUTE CALCULATOR

This calculator is used to calculate (duh) which route your paradroppers will take between point X to Y. HOI4 uses A\* algorithm to calculate it.

Actual in-game algorithm is: Entering a zone costs `(N + 1) × 100,000 . N' where N is zone’s size in pixels. They also need to be neighbors to route of course. Game will take the lowest TOTAL cost route possible. This is why for example when you launch from jutland to Scotland you wont take Northern Sea route like ingame arrow shows cause Northern Sea is giant.

Every zone on the route is checked. A zone only blocks you if the enemy has air presence there and you have less than 70% air superiority in it. If enemy has no air presence it doesnt matter.

Good luck with your airlions/paradrop memes. I might upload a workshop mod to have this ingame some time later i dont know how to mod HOI4.

I used claude to make the app. You need .NET 10 SDK to run this. 
