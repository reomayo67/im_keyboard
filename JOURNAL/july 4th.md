July 4th

After looking at plaids pcb, im gonna use his idea of alternatying between top cu adn bottom cu for the diode intersections.

<img width="1016" height="106" alt="Screenshot 2026-07-04 094126" src="https://github.com/user-attachments/assets/ed0f2d96-0b71-4984-a25d-e9d5a23439e4" />

After thinking for a bit, I wanna use the rows that Plaid used for his diodes, as they are so organized and optimized. Other thn placing the diodes directly next to their switch

As you can see, he rotates between the two copper layers to allow for all the diodes to coexist in such a tiny area without conflict.
I got all of the columns wired together and connected the the mcu, as well as the first row connected to their diodes. I will have to use vias to be able to organize the tracks so they can coexist peacfully.

After some revisions of the diodes and to where they orintate, i got smth like this.

<img width="1232" height="685" alt="Screenshot 2026-07-04 204827" src="https://github.com/user-attachments/assets/b77f26b6-355b-4591-bcdd-ad3f5790fc81" />

They are alligned so the top layer is row 1, second layer is row 2, and so on. And going right, are the keys in that row. So after alligning ALL of them to their switches and tracking the columns together, adding the inverted fill zone, and a general pcb cutout, I got this.

<img width="1199" height="678" alt="Screenshot 2026-07-04 232023" src="https://github.com/user-attachments/assets/a812cbca-fc23-4194-8ce0-c66062f8fe4e" />

Now, as you can see, for the diode tracking I alternate between front cu and bottom cu so all the tracks can be around eachother in the same congested area with the diodes. I ran the DRC and didnt get any errors :D, but there are a couple warnings and other unchecked tests that I wanna dive deeper into before exporting the board. Allat is a task for tmrw.

Here is the 3d model with the visual renders of the components

<img width="667" height="441" alt="Screenshot 2026-07-04 232004" src="https://github.com/user-attachments/assets/99616f8b-e15f-4827-8065-3f48e4e5452e" />

Today was Chalk full of getting to know kicad better, which is amazing.

2 hours