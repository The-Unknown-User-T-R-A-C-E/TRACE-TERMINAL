# Trace Terminal Setup Guide

## Steps to Run Trace Terminal:

1. **Create the Python Script:**
   - Open a text editor (e.g., Notepad).
   - Copy and paste the code for Trace Terminal (the `trace_terminal.py` file).
   - Save the file with the name **`trace_terminal.py`** (make sure the extension is `.py`).

2. **Contact for `users.json`:**
   - To use the terminal, you will need the `users.json` file.
   - DM **`the_unknown.user_`** on Discord to request the `users.json` file. Make sure to mention that you're setting up Trace Terminal.

3. **Run the Terminal:**
   - Open your Command Prompt (Windows) or Terminal (Linux/macOS).
   - Navigate to the folder where you saved `trace_terminal.py` (use `cd` to change directories).
   - Run the terminal by typing:
     ```bash
     python trace_terminal.py
     ```

4. **Set Up the `trace` Command:**
   - To make the terminal run when you type `trace`, follow these steps:
   
     **For Windows:**
     - Open Command Prompt and type:
       ```bash
       doskey trace=python path\to\trace_terminal.py
       ```
     - This will run the Trace Terminal script when you type `trace` in the command prompt.
   
     **For Linux/macOS:**
     - Open your terminal and type:
       ```bash
       alias trace='python /path/to/trace_terminal.py'
       ```
     - This will run the Trace Terminal script when you type `trace` in the terminal.

5. **Start Using Trace Terminal:**
   - Now, whenever you type `trace` in the terminal, it will start the Trace Terminal.
   - Follow the on-screen prompts to interact with the terminal.

---

## Notes:
- Make sure you have **Python 3** installed on your machine.
- The terminal will require the `users.json` file, which contains the necessary user authentication details. Please ask **`the_unknown.user_`** for the file.
- Enjoy using the Trace Terminal!

- Usage and License Agreement:

By using Trace's Terminal, you agree that the software and its components are protected under copyright law. Reuse, modification, redistribution, or any form of sharing is not permitted unless explicitly authorized by the creator. All rights to Trace's Terminal, including but not limited to its source code, functionalities, and license terms, are reserved by the creator. Unauthorized use, alteration, or distribution is prohibited.
