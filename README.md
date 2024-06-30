https://divyanshrajpoot9.github.io/Uptown-Skylla/
# N_Queens_Visualizer_Puzzle:
### Hosted Link: https://divyanshrajpoot9.github.io/N_Queens_Visualizer_Puzzle/
### Technologies Used: HTML5/CSS3/JavaScript/ES6/Git/GitHub/VSCode/Figma/FontAwesomeCDN.
This code is a JavaScript implementation of the N-Queens problem visualization using HTML, CSS, and JavaScript. 
Here's a breakdown of the code:
1. **HTML Structure**: The HTML file contains elements with IDs "numberbox", "slider", "progress-bar", "play-button", "pause-button", "n-queen-board", and "queen-arrangement". These elements are manipulated by JavaScript.

2. **JavaScript Variables**:
   - `numberbox`, `slider`, `progressBar`, `playButton`, `pauseButton`: Variables referencing various HTML elements.
   - `queen`: HTML markup for a chess queen icon.
   - `n`, `speed`, `tempSpeed`, `q`, `Board`: Variables used for controlling the visualization and solving the N-Queens problem.
   - `array`: Pre-calculated number of possible arrangements for different N values.
   - `pos`: Object used to store the state of the boards.
   - `Queen`: Class representing a Queen object with methods to solve the N-Queens problem and visualize the process.

3. **Event Listeners**:
   - `slider.oninput`: Updates the speed of visualization based on slider input.
   - `playButton.onclick`: Initiates the visualization process when the play button is clicked.

4. **Queen Class**:
   - `constructor`: Initializes the Queen object.
   - `nQueen`: Method to start solving the N-Queens problem.
   - `isValid`: Method to check if placing a queen in a certain position is valid.
   - `clearColor`: Method to clear colors on the chessboard.
   - `delay`: Method to introduce delays in visualization.
   - `solveQueen`: Recursive method to solve the N-Queens problem.

5. **Visualize Function**:
   - Triggered when the play button is clicked.
   - Parses input from the number box to set the size of the chessboard.
   - Clears previous arrangements and boards.
   - Generates HTML elements for the chessboard.
   - Initiates the N-Queens visualization process.

This code aims to demonstrate how the N-Queens problem can be solved and visualized using JavaScript, providing insights into the process of finding solutions. It utilizes HTML and CSS for the user interface and JavaScript for the logic and animation.
## The approach followed in this code can be summarized as follows:

1. **User Interface Setup**:
   - HTML is used to create the necessary elements for the user interface, such as input boxes, buttons, and the chessboard visualization area.
   - CSS is used to style these elements for a visually appealing interface.

2. **Event Handling**:
   - Event listeners are set up to handle user interactions, such as changing the speed of visualization with a slider and initiating the visualization process with a play button click.

3. **Data Representation**:
   - The chessboard and queen placements are represented using HTML tables.
   - JavaScript variables store data related to the state of the chessboard, queen positions, and visualization parameters.

4. **N-Queens Solver**:
   - The core logic of solving the N-Queens problem is encapsulated within the `Queen` class.
   - The `isValid` method checks whether a queen can be placed in a specific position without conflicting with existing queens.
   - The `solveQueen` method recursively attempts to place queens on the chessboard while ensuring no conflicts occur.

5. **Visualization**:
   - Visual cues are provided to represent valid and invalid queen placements on the chessboard.
   - Delays are introduced between steps to create a visual animation of the solving process.
   - Colors are used to highlight valid and invalid placements, as well as to distinguish between different boards.

6. **User Interaction and Feedback**:
   - Users can input the size of the chessboard via an input box.
   - Feedback messages are displayed for invalid inputs or when the N-Queens problem is being solved.

7. **Optimizations and Performance**:
   - The code includes optimizations such as pre-calculating the number of possible arrangements for different N values to provide efficient feedback to users.

Overall, this approach combines elements of user interface design, algorithm implementation, and visualization techniques to solve and demonstrate the N-Queens problem in an interactive and engaging manner.

  ## User Interface:
![Screenshot 2024-05-19 080017](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/eeaf1af3-a69a-47c5-893a-d83b68e3d86b)
![Screenshot 2024-05-16 105625](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/17aa140f-932c-4710-aa6f-4bf23f7d5435)
![Screenshot 2024-05-16 105834](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/02884cc3-44c3-483a-a2fa-e22647041494)
![Screenshot 2024-05-16 105929](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/2caeff61-2429-4dee-9f12-dc1effdfc8f9)
![Screenshot 2024-05-16 110054](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/0320125b-1b5c-4a18-af12-d88911508ee5)
![Screenshot 2024-05-16 110155](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/5dd56300-ca8f-4a88-8154-539b4f1d6e5e)
![Screenshot 2024-05-16 112448](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/563f5424-b192-41a0-aa94-51b238514bf0)
![Screenshot 2024-05-16 112550](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/2c3fce85-d3b3-438c-b719-1c0e58984b08)
![Screenshot 2024-05-16 112634](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/6ab3d176-8307-4a42-8d46-c91788342843)
![Screenshot 2024-05-16 112713](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/be383c8c-fc61-4dba-9696-f27b3db05b59)
![Screenshot 2024-05-16 112801](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/84c56be8-9e4c-4cb9-9834-ad7c0dde8c6e)
![Screenshot 2024-05-16 112947](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/10139f2f-707d-43d4-a6ad-e41f887b2787)
![Screenshot 2024-05-16 113022](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/a206c383-8119-4309-b4c4-b5354bcb9ef5)
![Screenshot 2024-05-16 113053](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/d2c11fe9-a3d2-40a6-92c3-9b5311a96ce3)
![Screenshot 2024-05-16 131521](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/8a6f25d6-daf5-4f17-a4c4-a2fce73d8819)
![Screenshot 2024-05-16 131557](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/b474c9ec-c93d-4c51-84d6-5ebae200331c)
![Screenshot 2024-05-16 152123](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/c1483b31-06f3-4e99-a584-68d11e513f6d)
![Screenshot 2024-05-16 163231](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/875277b0-544a-4905-81ad-d455a6589ab1)
![Screenshot 2024-05-16 163639](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/250cb3ba-541d-4763-a9a0-b4d8b2ff13ed)
![Screenshot 2024-05-16 163709](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/fbe16060-f390-4c17-bc6b-14e5fd64aee2)
![Screenshot 2024-05-16 163759](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/c3f44ca0-01fd-4282-82be-fb2023d54424)
![Screenshot 2024-05-16 163943](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/64287f27-8859-4884-af1f-02f1dba3704c)
![Screenshot 2024-05-19 075359](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/c6470607-733f-4d88-8238-7021a2f3f211)
![Screenshot 2024-05-19 075435](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/c3828a1d-22df-4c30-a09f-2604b9269bdd)
![Screenshot 2024-05-19 075506](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/2277af1a-93e3-4731-9db7-bb9c89f32ef1)
![Screenshot 2024-05-19 075529](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/51f8a6b4-fa75-4029-b423-64e9aa67ef70)
![Screenshot 2024-05-19 075557](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/274976c1-8549-4d95-a231-d9ff90070735)
![Screenshot 2024-05-19 075638](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/170d71bb-16ca-4b1f-a776-fba1c6cab096)
![Screenshot 2024-05-19 075700](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/f0b36757-ba8d-4baa-b6f1-8831141d174f)
![Screenshot 2024-05-19 075831](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/95f9161e-7e2f-4028-8f78-dc138c7670d7)
![Screenshot 2024-05-19 075853](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/e5036a49-239a-46cd-8738-4c245087950f)
![Screenshot 2024-05-19 075913](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/7ac433fc-a5b4-4f24-9492-9cc747a2149e)
![Screenshot 2024-05-19 075937](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/640577ff-615e-4451-a145-7d005bbce991)
![Screenshot 2024-05-19 080017](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/3683fd7f-c16d-4fd2-aee2-b73d08b33196)
![Screenshot 2024-05-19 075958](https://github.com/divyanshrajpoot9/Uptown-Skylla/assets/114856467/2264529d-4f99-4138-8f7e-2193418be31f)
