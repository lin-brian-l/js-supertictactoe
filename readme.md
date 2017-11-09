General Plan
- Create 9 little board objects w/ IDs (and win conditions)
- 1 big board object inheriting from little board w/ dominance rules
- bigBoard.id = 9
- littleBoards.ids = [0, 1, 2, 3, 4, 5, 6, 7, 8]
- littleBoards have spaces with indices [0, 1, 2, 3, 4, 5, 6, 7, 8]

Movement
- boardOfNextMove = spaceIndex of littleBoard

If Board is Full:
- Cat's Game
- - Player w/ most moves in board decides movement
- Claimed Little Board
- - If currentPlayer owns board, moves w/e they want
- - Else opponent decides littleBoard to move
