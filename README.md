# enpm-661-project-2-dijkstras-path-planning
This project implements a path planning algorithm using Dijkstra's algorithm to find the shortest path from a start node to a goal node in a given map environment.

## How to Run the Code:

1. Clone the repository to your local machine:
git clone [https://github.com/your-username/path-planning.git](https://github.com/hoangpm99/enpm-661-project-2-dijkstras-path-planning)

2. Navigate to the cloned directory:
cd enpm-661-project-2-dijkstras-path-planning

3. Ensure you have the necessary dependencies installed:
- Numpy
- OpenCV (cv2)

4. Run the main script to execute the path planning algorithm:
python dijkstra_hoang_pham.py

5. Follow the prompts to input the start and goal coordinates when prompted.
Make sure the start and goal coordinates are within the free space.

6. Adjust the frame skip value in the visualization script (`visualize_path`) for faster or slower visualization.

## Map Configuration:

- The map used for configuration space representation is a 1-channel grayscale image, where obstacles are represented by white pixels (255), borders are represented by gray pixels (128) and free space by black pixels (0).

## Output Visualization:

- The output visualization displays the path planning process and the final path on the map.
- The visualization uses a 3-channel color image with obstacles represented in gray, the explored nodes in blue, and the path in green.
- OpenCV (cv2) library is used for visualization.
- Default OpenCV color code is (B,G,R)

## Note

- Depending on the distance between the start and goal nodes, the program's execution time may vary significantly.
