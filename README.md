# fire-zero
fire 8.2 self-play nnue

## tools used:

- fire 8.2 https://github.com/FireFather/fire
- cutechess https://github.com/cutechess/cutechess
- deeds tools https://outskirts.altervista.org/forum/viewtopic.php?t=2009
- nnue-gui https://github.com/FireFather/nnue-gui
- sf-nnue https://github.com/FireFather/sf-nnue
- pgn-extract https://www.cs.kent.ac.uk/people/staff/djb/pgn-extract/

## opening book creation:
- chessbase 16 64-bit https://shop.chessbase.com/en/products/chessbase_16_fritz18_bundle 
(or another suitable program to removes duplicate games from a pgn file)
- 40H-pgn tools http://40hchess.epizy.com/

## efficiently-updatable neural network (nnue) for any engine:
- setting up a suitable Windows environment
- creating an efficient opening book using cutechess-cli
- running selfplay games for a 'zero' nnue approach
- using eval-nnue eval-extract (Deeds Tools https://outskirts.altervista.org/forum/viewtopic.php?f=41&t=2009&start=30)
- position (fen) extraction from pgn files
- conversion to plain text
- conversion ofplain text files to nnue .bin training format
- training management using nnue-gui (https://github.com/FireFather/nnue-gui)
- creating an initial nnue
- testing the generated nnues
- improving the NNUE with supervised and reinforcement learning
