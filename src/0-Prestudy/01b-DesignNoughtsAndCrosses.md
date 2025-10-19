// ================================
// Designing Noughts And Crosses
// ================================

For this exercise, come up with a design for playing "Noughts And Crosses" aka "Tic-Tac-Toe".
I chose this because it's simple and everybody knows the rules.

As always, there are no "right" answers -- I am interested in seeing different approaches. We will be discussing these answers in the first session of the course.

# 1. Write down a "design" for playing Noughts And Crosses

I would have some types in my system for pieces, the board and a player, and turns. A game style
type as well that brings these concepts together. Game has a board and players with state that can 
be derived by the state of the board.

# 2. How is your design different from code?

It just models the concepts, not the implementation. Different implementations may be required for leveraging
different technologies of paradigms. I could use OOP I could use a functional style, my model may represented how
I want it stored in a relational database instead of a document database.