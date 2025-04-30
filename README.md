# Machiavellian-ChatBot

Below are the complete instructions to run the `MachiavellianChatbot` Python script, along with a `README.md` file tailored for uploading to your GitHub repository. The instructions cover setting up the environment, installing dependencies, and running the script. The `README.md` provides an overview of the project, setup instructions, usage, and contribution guidelines.

### Complete Instructions to Run the MachiavellianChatbot

#### Prerequisites
- **Python 3.12 or higher**: Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- **Operating System**: The script is compatible with Windows, macOS, or Linux.
- **pip**: Python’s package manager, which typically comes with Python installations.
- **Terminal or Command Prompt**: For executing commands.
- **Optional**: A code editor like VS Code, PyCharm, or any text editor for viewing/editing the script.

#### Step-by-Step Instructions
1. **Save the Script**:
   - Copy the provided `MachiavellianChatbot.py` code into a file named `MachiavellianChatbot.py`.
   - Save it in a directory of your choice (e.g., `~/Projects/MachiavellianChatbot/`).

2. **Set Up a Virtual Environment** (Recommended):
   - Open a terminal or command prompt and navigate to the directory containing `MachiavellianChatbot.py`:
     ```bash
     cd ~/Projects/MachiavellianChatbot
     ```
   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - **Windows**:
       ```bash
       venv\Scripts\activate
       ```
     - **macOS/Linux**:
       ```bash
       source venv/bin/activate
       ```
   - You should see `(venv)` in your terminal prompt, indicating the virtual environment is active.

3. **Install Dependencies**:
   - The script has no external dependencies (e.g., NLTK has been removed), so no additional packages are required. The standard Python libraries (`random`, `asyncio`, `platform`, `sys`) are included with Python.

4. **Run the Script**:
   - Ensure you’re in the directory containing `MachiavellianChatbot.py` and the virtual environment is activated.
   - Execute the script:
     ```bash
     python MachiavellianChatbot.py
     ```
   - The chatbot will start, displaying:
     ```
     *burp* Wubba lubba dub-dub! Ricky-AIMbot 3000, ready to manipulate the multiverse!
     Pathetic Mortal:
     ```
   - Interact with the chatbot by typing inputs:
     - Type greetings like `hello` or `hi` for sarcastic responses.
     - Type questions like `how to gain power` for strategic advice.
     - Type commands like `do something` for compliance responses.
     - Type `exit` or `quit` to stop the chatbot.
     - Press `Ctrl+D` (Linux/macOS) or `Ctrl+Z` (Windows) to send an EOF signal, which will also exit the chatbot.

5. **Troubleshooting**:
   - **Python Version Error**: If you encounter a version error, ensure Python 3.12 or higher is installed (`python --version`).
   - **Script Doesn’t Run**: Verify the file is named `MachiavellianChatbot.py` and you’re in the correct directory.
   - **Input Issues**: If the script doesn’t accept input, ensure your terminal is active and not blocked by another process.
   - **Deactivate Virtual Environment**: When done, deactivate the virtual environment by typing:
     ```bash
     deactivate
     ```

6. **Optional: Run in an IDE**:
   - Open `MachiavellianChatbot.py` in an IDE like VS Code or PyCharm.
   - Use the IDE’s “Run” or “Debug” feature to execute the script. Ensure the Python interpreter is set to version 3.12 or higher in the IDE settings.
   - Interact with the chatbot in the IDE’s terminal or console.

### README.md for GitHub
Below is a `README.md` file to accompany your GitHub repository. It includes an overview, setup instructions, usage details, and contribution guidelines, formatted in Markdown for GitHub rendering.


# MachiavellianChatbot

A Python-based chatbot inspired by Machiavellian principles and the cynical, irreverent persona of Rick Sanchez from *Rick and Morty*. The chatbot, dubbed "Ricky-AIMbot 3000," responds to user inputs with manipulative, sarcastic, and strategic responses, designed to entertain and provoke with its amoral and cunning dialogue.

## Features
- **Intent Recognition**: Identifies user intents (greeting, question, command) based on keyword matching.
- **Context Awareness**: Detects contexts like power, deception, or strategy to tailor responses.
- **Dynamic Tones**: Applies sarcastic, condescending, or scheming tones to responses.
- **Machiavellian Advice**: Offers strategic, manipulative advice for questions related to power or deception.
- **No External Dependencies**: Runs with standard Python libraries, ensuring easy setup.

## Prerequisites
- Python 3.12 or higher
- A terminal or command prompt
- Optional: A code editor (e.g., VS Code, PyCharm)

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/MachiavellianChatbot.git
   cd MachiavellianChatbot
   ```

2. **Set Up a Virtual Environment** (Recommended):
   ```bash
   python -m venv venv
   ```
   Activate the virtual environment:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

3. **No Additional Dependencies**:
   - The script uses only standard Python libraries (`random`, `asyncio`, `platform`, `sys`).

## Usage
1. **Run the Chatbot**:
   ```bash
   python MachiavellianChatbot.py
   ```
   The chatbot will start with a welcome message:
   ```
   *burp* Wubba lubba dub-dub! Ricky-AIMbot 3000, ready to manipulate the multiverse!
   Pathetic Mortal:
   ```

2. **Interact with the Chatbot**:
   - **Greetings**: Type `hello`, `hi`, or `hey` for a sarcastic response.
   - **Questions**: Type `how to gain power` or `why deceive` for strategic, Machiavellian advice.
   - **Commands**: Type `do something` or `create a plan` for a compliant response.
   - **Exit**: Type `exit` or `quit`, or press `Ctrl+D` (Linux/macOS) or `Ctrl+Z` (Windows) to stop.

3. **Example Interaction**:
   ```
   Pathetic Mortal: hello
   Ricky-AIMbot 3000: You’re stepping into my game, and I always win. *burp* Greetings, you insignificant speck. What do you want?... or whatever, like I care.
   Pathetic Mortal: how to gain power
   Ricky-AIMbot 3000: Predictable. But I’ll play along—for now. Heh, To gain power, always let others think they’re in control—then pull the strings. You’re playing right into my hands.
   Pathetic Mortal: quit
   Ricky-AIMbot 3000: *burp* Fine, I’ll portal out. You’re boring anyway.
   ```

## Troubleshooting
- **Python Version**: Ensure Python 3.12 or higher is installed (`python --version`).
- **Script Fails to Run**: Verify the file is named `MachiavellianChatbot.py` and you’re in the correct directory.
- **Input Issues**: Ensure your terminal is active and not blocked.
- **Deactivate Virtual Environment**: Run `deactivate` to exit the virtual environment.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please ensure your code follows the existing style and includes appropriate comments.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by Niccolò Machiavelli’s principles of power and deception.
- Persona based on Rick Sanchez from *Rick and Morty*, created by Justin Roiland and Dan Harmon.


### Additional Notes
- **GitHub Repository Setup**:
  - Create a new repository on GitHub (e.g., `MachiavellianChatbot`).
  - Initialize it with a `README.md` file, or overwrite it with the provided one.
  - Upload `MachiavellianChatbot.py` and `README.md` to the repository:
    ```bash
    git init
    git add MachiavellianChatbot.py README.md
    git commit -m "Initial commit with chatbot script and README"
    git branch -M main
    git remote add origin https://github.com/your-username/MachiavellianChatbot.git
    git push -u origin main
    ```
  - Optionally, add a `LICENSE` file (e.g., MIT License) as referenced in the `README.md`.

- **File Structure**:
  Your repository should look like this:
  ```
  MachiavellianChatbot/
  ├── MachiavellianChatbot.py
  ├── README.md
  └── LICENSE (optional)
  ```

- **Testing the Script**:
  - After following the setup instructions, test the script with various inputs to ensure it responds as expected (greetings, questions, commands, and exit).
  - If you encounter issues, refer to the troubleshooting section in the `README.md`.

This setup ensures the chatbot runs smoothly and your GitHub repository is professional and informative. Let me know if you need further assistance with the GitHub upload process or additional features for the chatbot!
