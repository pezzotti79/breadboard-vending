# breadboard-vending
A breadboard vending machine relies on a breadboard with routers and wires to function properly. The placement of these components is crucial, as incorrect positioning can cause malfunctions or failure.

A latch is a type of memory that stores one bit of information. An SR latch has two inputs: S (Set) and R (Reset), and an output Q, which holds the stored value.
	•	When S = 1, Q becomes 1 and stays 1 even after S returns to 0.
	•	The vending machine uses this concept to track whether a coin has been inserted.

Example: Coin-Operated Vending Machine
	1.	Coin Slot (S Input): When a coin is inserted, the machine remembers this state.
	2.	Vend Button (Trigger): Pressing the button checks the memory to see if a coin has been inserted.
	3.	Product Dispensing (R Input): If a coin is present, the machine activates and dispenses the selected item.

The memory system ensures the machine only vends when a coin is inserted, preventing it from giving out free items.

# Phase 1 SET
![IMG_5592](https://github.com/user-attachments/assets/376aaba9-7300-4c52-92c6-501a1efdc6c1)
# Phase 2 REMEMBER
![IMG_5593](https://github.com/user-attachments/assets/4479f7aa-0c2e-42a6-aa01-5447a7fe5dae)
# Phase 3 VEND/RESET
![IMG_5591](https://github.com/user-attachments/assets/b1b46d82-cc9b-4c68-9cdf-3b831a38f2fc)

# REFERENCES
Justice, M. (2020). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine. No Starch Press.
