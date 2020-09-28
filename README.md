# Wukong
Modular & didactic UCI chess engine written by Code Monkey King

# Strength CCRL 1474 ELO
https://www.computerchess.org.uk/ccrl/404/cgi/engine_details.cgi?print=Details&each_game=1&eng=Wukong%202020-09-16%2064-bit#Wukong_2020-09-16_64-bit

# Features ( absolutely modular - movegen/search/eval )
  - 0x88 board
  - pseudo-legal move generator
  - copy/make approach for making moves
  - material + positional scores + double pawns penalty evaluation
  - negamax search with alha-beta pruning
  - PV table
  - killer moves/history moves move ordering
  - iterative deepening
  - material and PST evaluation
  - fixed depth UCI protocol (plays whatever but fixed depth mode with hardcoded 6 plies)

# Limitations
  - no 3 fold repetition detection
  - no 50 move rule detection
