# Cub3D

Cub3D is a project that immerses you in the fundamentals of ray-casting. The goal is to navigate through a dynamic 3D view within a complex maze. This project will help you enhance your understanding of real-time rendering and maze exploration.

## Features

- **Ray-Casting Engine**: Experience a simple but effective 3D graphics engine based on ray-casting.
- **Maze Exploration**: Navigate through intricate mazes, testing your spatial awareness and problem-solving skills.
- **Texture Mapping**: Apply various textures to walls, enhancing the realism of the environment.
- **Mouse and Keyboard Controls**: Enjoy fluid interaction with mouse look and WASD keyboard controls.

## Installation

To compile and run the project, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Cub3D.git
    cd Cub3D
    ```

2. **Install Dependencies**:
    Make sure you have the necessary libraries installed (e.g., MiniLibX, math library).
    ```bash
    sudo apt-get install libmlx
    sudo apt-get install libmath
    ```

3. **Build the Project**:
    ```bash
    make all
    ```

4. **Run the Program**:
    ```bash
    ./cub3D path/to/your/map.cub
    ```

## How to Play

- Use `W`, `A`, `S`, `D` to move your character.
- Use the mouse to look around and rotate your view.
- Navigate through the maze and try to find the exit.

## Map Format

The project uses `.cub` files to define the map layout. The format is straightforward:

- **1**: Wall
- **0**: Walkable space
- **N**, **S**, **E**, **W**: Player start position (North, South, East, West)

Example:
```bash
111111
100001
1010N1
100001
111111
```

## Textures

The project supports custom textures for walls, floor, and ceiling. Make sure to include your texture files in the `textures/` directory.

## Troubleshooting

- **Segmentation Fault**: Ensure that the player does not move into walls by checking collision boundaries.
- **Textures Not Displaying**: Double-check the file paths in your `.cub` file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contribution

Feel free to fork the project, submit pull requests, or open issues to improve the project.

## Acknowledgments

This project is inspired by the classic Wolfenstein 3D and similar early 3D games. Special thanks to the [42 School](https://42.fr) for the educational environment and resources that made this project possible.
