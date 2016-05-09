# Evolution

This project implements my project for Northeastern's CS4500 with Matthias Felleisen, better known as 'Hell'.* To see the specifications, check the [course website](http://www.ccs.neu.edu/home/matthias/4500-s16/index.html). To see the canonical implementation, check [Matthias's version](https://github.com/mfelleisen/Evolution)

*I can assure you that on the first day, Matthias walks in and says "Welcome to Hell."

# Tests
are insufficient, but can be run with `python3 -m unittest`

#Known Issues
- when players are kicked, either too many or kicked, or the wrong ones are.
- there's a bug in the game logic on the server somewhere that causes full games to end with incorrect scores.
I suspect that both have to do with the logic to rotate players, but I haven't fixed them in the interest of leaving the code as it was at the end of the course.