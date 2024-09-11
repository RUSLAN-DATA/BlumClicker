
# BlumClicker

**BlumClicker** is an enhanced tool for automating the collection of stars in Blum games. The program automatically collects stars using random click sequences and supports the automatic launching of games until tickets run out. You can also enable the option to collect freeze items.

## Key Features:
- Full automation of star collection.
- Configurable randomization of clicks for natural behavior.
- Option to collect freeze items.
- Automatic scrolling and continuous game launching while tickets last.

## Requirements:
- **Python version 3.10 or higher**.

### 1. Installing Python  
Download and install Python version 3.10 or higher from [python.org](https://www.python.org/). Be sure to check the "Add Python to PATH" option during installation.

### 2. Verifying Installation  
Open the command prompt and run the following commands to ensure Python and pip are installed correctly:
```bash
python --version
pip --version
```

### Installation and Setup — Part 2:

### 3. Cloning BlumClicker  
Download the **BlumClicker** project from GitHub.

### 4. Installing Dependencies  
Navigate to the project folder using the command prompt and install the required libraries:
```bash
cd /path/to/your/folder
pip install -r requirements.txt
```

### Running and Setup — Part 1:

### 5. Launching the Game  
Open the Blum game in Telegram Desktop or via the Telegram web version.

### 6. Running BlumClicker  
Run the script with the command:
```bash
python main.py
```

### Running and Setup — Part 2:

### 7. Selecting the Game Window  
The console will prompt you with a list of available windows. Select the Blum game window by specifying its number. Make sure to choose the correct window. For example, I usually choose the TelegramDesktop window with Blum.

### 8. Setting Randomization  
Enter a value between 0 and 1 to adjust the randomization of click timing. A value of 1 means all stars will be collected, while 0.6 is suitable for collecting about 140–150 stars. I recommend using 0.9 for the most efficient collection.

### 9. Running the AutoClicker  
After launching the mini-game, press ***F6*** to start (Explanation: open BLUM, but don’t start the game yet, and after selecting the window in the console, press ***F6***. If you’re on a laptop, press ***FN+F6***. The AutoClicker should find the play button and launch the game).

### P.S.  
Download and extract the folder with images into one folder – you should have two files in the folder (main.py and requirements.txt) and a folder called template_png.
