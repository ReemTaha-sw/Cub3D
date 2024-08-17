<h2 align="center">Cub3D 🕹️</h2>
  
<p align="center">  
Dive into the world of retro gaming with **Cub3D**—an immersive project that challenges your understanding of ray-casting and real-time 3D rendering. Navigate through a complex maze and experience the foundational principles that powered the early days of 3D graphics.
Get a glimpse of the gameplay and features of **Cub3D** in action 🌟
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a7647355-6ba7-4a67-aa11-a9d2605901db" width="45%" />
  <img src="https://github.com/user-attachments/assets/c45ebaa5-9c30-4e17-9df5-01f567c96090" width="45%" />
</p>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/badge/Top%20Language-C%20-blue">
  <img alt="Made with" src="https://img.shields.io/badge/Made%20with-MiniLibX-red">
  <img alt="Made by" src="https://img.shields.io/badge/Made%20by-Reem Taha-green">
  <img alt="Repository size" src="https://img.shields.io/badge/Repo%20Size-1.2%20MB-blue">
  <img alt="GitHub last commit" src="https://img.shields.io/badge/Last%20Commit-August%202024-red">
</p>

<p align="center">
  <a href="#features-">Features</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#installation-">Installation</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#getting-started-">Getting Started</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-play-">How to Play</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#map-format-">Map Format</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#textures-">Textures</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#troubleshooting-">Troubleshooting</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license-">License</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#contribution-">Contribution</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#acknowledgments-">Acknowledgments</a>
</p>

---

## Features ✨

- **Ray-Casting Engine**: Explore a powerful yet simple 3D graphics engine, reminiscent of classic first-person shooters.
- **Maze Exploration**: Sharpen your navigation skills as you explore intricate mazes, with increasing levels of difficulty.
- **Texture Mapping**: Bring the environment to life with customizable textures that add depth and realism to the game world.
- **Intuitive Controls**: Navigate effortlessly with smooth mouse look and responsive WASD keyboard controls, enhancing the overall gameplay experience.

## Installation 🛠️

Set up and run **Cub3D** on your machine by following these steps:

1. **Clone the Repository**:
    ```bash
    git clone git@github.com:ReemTaha-sw/Cub3D.git
    cd Cub3D
    ```

2. **Install Dependencies**:
    Ensure that you have all the necessary libraries installed:
    ```bash
    sudo apt-get install libmlx
    sudo apt-get install libmath
    ```

3. **Build the Project**:
    Compile the project using the provided `Makefile`:
    ```bash
    make all
    ```

4. **Run the Program**:
    Execute the program with your map file:
    ```bash
    ./cub3D path/to/your/map.cub
    ```


## Getting Started 🚀

After setting up the project, try running the game with a sample map provided in the `maps/` directory. Here's how:

```bash
./b_cub3D maps/african.cub
```

## How to Play 🎮

- **Movement**: Use `W`, `A`, `S`, `D` to move your character.
- **Look Around**: Use the arrows or mouse to look around and rotate your view.
- **Objective**: Navigate through the maze and try to find the exit.


## Map Format 🗺️

The project uses `.cub` files to define the map layout. Here's a breakdown of the format:

- **1**: Wall
- **0**: Walkable space
- **N**, **S**, **E**, **W**: Player start position (North, South, East, West)


### Example Map:

```bash
111111
100001
1010N1
100001
111111
```
This example defines a simple room with the player starting at the position marked by N.


## Textures 🖼️

The project supports custom textures for walls, floors, and ceilings. Ensure to place your texture files in the `textures/` directory for proper application.


## Troubleshooting 🛠️

- **Segmentation Fault**: Ensure that the player does not move into walls by checking collision boundaries.
- **Textures Not Displaying**: Double-check the file paths in your `.cub` file to make sure they are correct and `Make sure that the image you choose has equal height and width and is within the range of 256 px`.


## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


## Contribution 🤝

Feel free to fork the project, submit pull requests, or open issues to contribute to the project.


## Acknowledgments 👏

This project draws inspiration from the classic **Wolfenstein 3D** and other early 3D games. Special thanks to the **42 School** for providing the educational environment and resources that made this project possible, and to the developers of **MiniLibX** for their invaluable tools in 2D graphics. 🎉
