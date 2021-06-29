# Mediator Design Pattern

This pattern comes under behavioral design pattern category.
It reduces communication complexity between multiple object, when they are dependent on each other. 

When there are n-number of classes interacting with each other, it is really a good architecture decision if we segregate the communication responsibility to someone else and impose a single communication mechanism across these classes. That way code maintenance becomes easy as well as definitely it will reduce system bugs because generally most of the bugs are injected during the interactions between objects.

This pattern is defined as - 

"Defines an object that encapsulates how a set of objects interact. Promotes loose coupling by keeping the objects from referring to each other directly."

In short mediator pattern encapsulates how objects communicate with each other without referring to each other directly.

# For detailed explanation visit - https://youtu.be/x_H4_bbLZ8Y

and 

# for more generic implementation visit - https://youtu.be/r8mThhyuh9U
