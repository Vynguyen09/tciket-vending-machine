# tciket-vending-machine
Ticket vending machine, i.e. vending machine that sells and produces tickets to commuters, is a subject of the example use case diagram. This kind of a machine is a combination of both hardware and software, and it is only a part of the whole system selling tickets to the customers. So we will use «Subsystem» stereotype.

Ticket vending machine allows commuters to buy tickets. So Commuter is our primary actor.
The ultimate goal of the Commuter in relation to our ticket vending machine is to buy a ticket. So we have Purchase Ticket use case. Purchasing ticket might involve a bank, if payment is to be made using a debit or credit card. So we are also adding another actor - Bank. Both actors participating in the use case are connected to the use case by association.

Use case behaviors may be described in a natural language text (opaque behavior), which is current common practice, or by using UML behavior diagrams. UML tools should allow binding behaviors to the described use cases. Example of such binding of the Purchase Ticket use case to the behavior represented by activity is shown below using UML 2.5 notation.
