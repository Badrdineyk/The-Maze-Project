
# 3D Maze Project 🎮
## Introduction 🌀

The 3D Maze Game is a first-person maze exploration game built using C programming language and the SDL2 library. The game utilizes ray-casting techniques to transform a 2D map into a 3D environment, creating an immersive experience where players navigate through a dynamically generated maze. This project was inspired by classic maze games and a love for puzzles and problem-solving.

- Project Landing Page: [Landing Page](https://erikjmayhew.wixsite.com/3d-maze-1)
- Final Project Article: [Link to the Article](https://www.linkedin.com/pulse/3d-maze-project-badreddine-toumani-zwg4e/)


## Authors 👨‍💻

- [Badreddine Toumani](https://github.com/Badrdineyk)
- [Zakaria Elorche](https://github.com/ezakariaa)



## Installation ⚙️

### Prerequisites:
1. Ensure SDL2 is installed:
```sh
sudo apt-get install libsdl2-dev
```
2. Clone the repository:
```sh
git clone https://github.com/Badrdineyk/The-Maze-Project/
```
### Compile the Project:
```sh
gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```
### Run the Game:
```sh
./maze or type make run
```


## Usage 🕹️

Once the game is running, you can control your character using the keyboard:

- Arrow keys: Move forward, backward, and rotate.

- Objective: Navigate through the maze and find the exit as quickly as possible.


## Contributing 🚀

We welcome contributions! Please follow these steps:

    1. Fork the repository
    2. Create a new branch (git checkout -b feature-name)
    3. Commit your changes (git commit -m 'Add feature')
    4. Push to your branch (git push origin feature-name)
    5. Open a pull request and describe the feature you've added


## License 📄
This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.

