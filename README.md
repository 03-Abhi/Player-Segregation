# Player Segregation - Final Submission

**College ID**: iit2021011@iiita.ac.in

---

## Project Structure:

- **Report**: 
  - The report that outlines all the ideas, approaches, and detailed descriptions of the implementations can be found in `report.pdf`. 
 
- **Implementation Directories**: 
  - Each implementation follows a different approach for player classification. The structure is as follows:
  
  - `Implementation_1`: Contains the code for the first approach, including the shell script (`execute.sh`) for running the code.
  - `Implementation_2`: Contains the code for the second approach, including the shell script (`execute.sh`) for running the code.

  
- **Output Folder**:
  - After execution, the code creates an `output` folder inside the respective `Implementation_{index}` directory.
  - Inside the `output` folder, there will be four subfolders: `player1`, `player2`, `player3`, and `player4`. 
  - The images corresponding to each player will be saved in the respective subfolders.

---

## Execution Instructions:

1. **Operating System**: 
   - The code is developed on **macOS Sequoia**.

2. **Python Version**: 
   - The code is developed and tested using the latest version of **Python 3**.

3. **How to Run**:
   - To execute the code, simply run the following command inside the `Implementation_1` folder (or any other implementation folder you are testing):
   ```bash
   ./execute.sh

4. **Shell Script (`execute.sh`)**:
   - The shell script will:
     - Install all the required dependencies.
     - Execute the player classification code.
     - Create the `output` folder with the subfolders (`player1`, `player2`, `player3`, `player4`).
     - Place the classified player images in the appropriate subfolders.

5. **Dependencies**:
   - All necessary Python packages will be automatically installed through the `execute.sh` script.
   - Alternatively, you can install the required packages manually by running:
   ```bash
   pip install -r requirements.txt


6.**Resume**:
My resume is located inside the Resume folder.
