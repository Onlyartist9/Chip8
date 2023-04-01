# Chip8
A simple CHIP-8 emulator in C++.

I always wanted to know how emulators worked. The common wisdom of the internet was that starting with the Chip-8 emulator set a great path onward not merely for the implementation
of Emulators but more Systems-oriented programming in general.

Having had C++ skills this was a great way to see more indepthly its use in a low-level programming environment.

### To run the emulator
1. Navigate to your terminal/shell.
2. Make sure you've installed SDL. This can easily be done with: 
```
sudo apt-get install libsdl2-dev
```
For Debian based systems or Debian based systems on WSL for Windows.

3. Clone the repo.
4. Change directories into the repo.
5. Compile the program like so:
```
g++ Chip_8.cpp -o Chip8 `sdl2-config --cflags --libs`
```
6. Play games by using the binary like so:
```
./Chip8 10 3 'Tetris [Fran Dachille, 1991].ch8'
```
For example. The repo comes with a test Tetris ROM to test the emulator.s