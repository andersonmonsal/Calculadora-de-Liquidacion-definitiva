##  Final Settlement Calculator
The project aims to develop a Python application that allows the calculation of labor settlements. This tool facilitates identifying the different components that must be paid to an employee upon the termination of their contractual relationship, such as severance pay, unused vacation days, severance, severance interest, service bonuses, and tax withholdings. The application receives information such as the base salary, start and end dates of employment, and accumulated vacation days to perform the necessary calculations according to current formulas and regulations.

## Team Members
Anderson Monsalve Monsalve

Dubin Andres Soto Parodi
## Project Structure

- `src/`
  - `controller/`
    - `controlador.py`: Contains the controller logic that connects the views and the model.
  - `model/`
    - `calculadora.py`: Contains the `LiquidationCalculator` class, which performs the settlement calculations.
  - `Gui/`
    - kivy_test.py:It is where the interface of our program is located.
  - `view/`
    - `consola.py`: Console interface that allows user interaction.
    - `consolacontrolador.py`: Manages the interaction between the console and the controller.
- `test/`
  - `controllertest.py`: Contains unit tests for the controller.

## Requirements

Make sure you have installed:

- Python 3.8 or higher
- `unittest` (included by default in Python)

## How to Run the Project

### Step 1: Clone the repository

Clone this repository to your local machine using Git:

```bash
git clone https://github.com/your-username/proyecto-liquidacion.git
cd proyecto-liquidacion

cd src/view

python consola.py

python-m unittest test.controllertest

python src/ view/consolacontrolador.py
python src/model/Gui/kivy_test.py
  ```
### step 2 : how to operate the console and controller
First you run console.py, which is located in the scr/view folder
This same process is done with this folder src/ view/consolacontrolador.py

### step 3 : For Kivy to work
The first thing you should do is install Kivy and when you do, click Run and the calculator will appear with the graphical interface. To see it correctly, put it in the large tab. The folder to run is located in the GUI, with the name kivy_test. .py
there you will be executed


