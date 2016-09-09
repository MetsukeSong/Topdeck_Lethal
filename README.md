# Topdeck_Lethal

Create a decktesting program in Java.

Superclasses:
Card
  string name:
  string text:
Zone
  unbounded array: contents
  method: add contents
  method: remove contents
  
Classes:
Land < Card
Nonland < Card
  string cost:
  string type:
  bool permanent: 
Hand < Zone
  int handLimit:
  method: draw
  method: discard
Grave < Zone
  ???? (does this zone deserve a subclass?)


Data Repository: 
Cards
