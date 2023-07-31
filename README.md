[<img src="GitHubLogo.png" alt="https://github.com/ZorPastaman" height="32">](https://github.com/ZorPastaman) &nbsp;
[<img src="InstagramLogo.png" alt="https://www.instagram.com/pastaman48/" height="32">](https://www.instagram.com/pastaman48) &nbsp;
[<img src="FacebookLogo.png" alt="https://www.facebook.com/vladimir.popov.5059" height="32">](https://www.facebook.com/vladimir.popov.5059) &nbsp;
[<img src="InLogo.png" alt="https://www.linkedin.com/in/vladimir-popov-27a213130" height="32">](https://www.linkedin.com/in/vladimir-popov-27a213130) &nbsp;
[<font size="24">@</font>](mailto:zor1994@gmail.com)

Hi! I'm Vladimir Popov. I'm a passionate gamer and game developer.
This is my site where I publish my open source projects.

# Unity

## [Event Based Blackboard](https://github.com/ZorPastaman/Event-Based-Blackboard)

Event Based Blackboard for Unity is a flexible data storage that can contain any count of properties of any type. 
The properties can be accessed with property names. 
Any part of a code can subscribe to a blackboard value change and receive a callback.

The main advantage of Event Based Blackboard is that it allocates as little as possible. 
Also it has good enough performance.

## [Event Based Blackboard Extensions](https://github.com/ZorPastaman/Event-Based-Blackboard-Extensions)

Event Based Blackboard Extensions is an extension for
[Event Based Blackboard](https://github.com/ZorPastaman/Event-Based-Blackboard).
It contains a lot of useful extensions for Blackboard component usage as well as for regular c# Blackboard usage.

## [Simple Blackboard](https://github.com/ZorPastaman/Simple-Blackboard)

Simple Blackboard for Unity is a flexible runtime data container that can contain any count of properties of any type. 
The properties can be accessed with property names.

The main advantage of Simple Blackboard is that it allocates as little as possible. 
Also, it has good enough performance and supports derivation.

## [Random Generators](https://github.com/ZorPastaman/Random-Generators)

Random generators for Unity is a collection of random generators, 
different random engines, distributions, modificators and filters.

The library has a useful infrastructure that makes it easy to expand it and add new
distributions, modificators, filters and random generators.

The library is very fast and heap allocation free.

## [Behavior Tree](https://github.com/ZorPastaman/Behavior-Tree)

Behavior Tree for Unity is an implementation of a classical behavior tree for Unity engine. 
Behavior trees allow you to easily set up a behavior switcher based on different conditions. 
Usually, it's used for game AI.

# C++

## [Linear Memory Allocator](https://github.com/ZorPastaman/Linear-Memory-Allocator)

Usual operators malloc and new are awesome but they have some disadvantages: memory allocation is random and memory fragmentation is very possible. 
One of the solutions is a linear memory allocator. Such an allocator preallocates a buffer of a linear memory segment and allocates all the object linearly into the buffer.

A linear memory allocator is especially useful if you want to keep pointers to different objects (especially of different size) and you know that you access them in a special order.

## [Stack Memory Allocator](https://github.com/ZorPastaman/Stack-Memory-Allocator)

Usual operators malloc and new are awesome but they have some disadvantages: memory allocation is random and memory fragmentation is very possible. 
One of the solutions is a stack memory allocator. Such an allocator preallocates a buffer of a linear memory segment and allocates all the object linearly into the buffer. 
Also, it can free allocations from the end to the beginning.

A stack memory allocator is especially useful when you want to allocate and free objects frequently and you know that you access them in a special order.
