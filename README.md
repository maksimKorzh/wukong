# Wukong ( around 1500 ELO strength )
Modular & didactic UCI chess engine written by Code Monkey King

# Features ( absolutely modular - movegen/search/eval )
  - 0x88 board
  - pseudo-legal move generator
  - copy/make approach for making moves
  - material + positional scores + double pawns penalty evaluation
  - negamax search with alha-beta pruning
  - PV table
  - killer moves/history moves move ordering
  - iterative deepening
  - fixed depth UCI protocol (plays whatever but fixed depth mode with hardcoded 6 plies)

# Limitations
  - no 3 fold repetition detection
  - no 50 move rule detection
