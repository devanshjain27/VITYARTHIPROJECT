# VIT Guide

## Project Overview
VIT Guide is a simple Python-based console application designed to help students quickly explore useful information about a VIT campus. The program provides different sections for places, food outlets, hostel blocks, sports courts, shops and the AB1 building.

The project uses basic Python concepts such as dictionaries, lists, functions, loops, conditional statements, user input and simple searching.

## Main Features

- **Special Block**
  - View available food places.
  - Check menu items and prices.
  - Order food and generate a simple bill.
  - Add places to favourites.

- **Boys Hostel**
  - Displays hostel block information.
  - Shows basic facilities.

- **Sports Courts**
  - Displays available sports courts.
  - Allows a selected court to be added to favourites.

- **Shops**
  - View shop locations.
  - View item prices.
  - Buy items and calculate the total bill.

- **AB1 Building**
  - Shows teachers' cabin information.
  - Displays cafes available in AB1.

- **Search**
  - Search for places, courts, shops, hostel blocks and shop items by name.

- **My Favourites**
  - View saved favourites.
  - Remove a favourite when required.

## Technologies Used

- Python 3
- Console/terminal interface
- Lists
- Dictionaries
- Functions
- Loops
- Conditional statements
- User input and basic string operations

## How to Run

1. Install Python 3 on your computer.
2. Save the program as `project.py`.
3. Open Command Prompt/Terminal in the project folder.
4. Run:

```bash
python project.py
```

5. Enter your name and use the numbered menu to navigate through the program.

## Program Flow

1. The program welcomes the user and asks for their name.
2. A main menu is displayed.
3. The user selects a section using numbers.
4. The selected function displays the required information or performs the requested action.
5. The user can return to the main menu at any time.
6. Selecting `0` exits the program.

## Data Used

The program stores campus-related information using Python dictionaries and lists. Examples include food menus and prices, hostel blocks, sports courts, shop locations and shop items.

## Important Functions

- `ask_number()` – accepts numeric input and keeps asking until a number is entered.
- `add_favourite()` – adds a place or court to the favourites list.
- `make_order()` – handles item selection, quantity, total calculation and bill display.
- `show_menu()` – displays the menu and information of a food place.
- `special_block_section()` – manages Special Block options.
- `hostel_section()` – displays boys hostel information.
- `courts_section()` – displays sports courts.
- `shops_section()` – handles shop-related options.
- `search_section()` – searches different categories.
- `favourites_section()` – displays and removes favourites.
- `main()` – controls the complete application and main menu.

## Limitations

- It is a console-based application, so there is no graphical interface.
- The information is stored directly in the Python program.
- Orders are only calculated locally and are not actually placed.
- There is no database or online connection.
- Search is based on simple text matching.

## Future Improvements

- Add a graphical user interface.
- Add more campus buildings and locations.
- Connect the project with a database.
- Add maps and navigation.
- Add login/student profile support.
- Save favourites permanently.
- Add more detailed food ordering and booking features.

## Conclusion

VIT Guide is a beginner-friendly Python project that combines several basic programming concepts into one useful campus information application. It demonstrates how lists, dictionaries, functions, loops and conditions can be used to build a menu-driven program.
