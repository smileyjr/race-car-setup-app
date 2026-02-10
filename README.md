# race-car-setup-app
a project made on free time for north-east modified such as 602 sportsman 358/BB mod in real life to keep track of your setup and also predict thing such as gas need. its all made in python and its FOSS.

🏁 Race Car Setup Tool (v1)

A clean, easy‑to‑use, open‑source desktop application for managing and analyzing left‑turn oval track race car setups.
Built with Python and Tkinter, this tool helps racers and crew members quickly calculate weight distribution, stagger, fuel usage, shock settings, and more — all in one organized interface.

This project is licensed under the GNU Affero General Public License v3 (AGPLv3) to ensure it always remains free, open, and community‑driven.
🚦 Features
✔ Corner Weights

    Enter LF, RF, LR, RR

    Automatic calculations:

        Total weight

        Rear bite

        Wedge (both LR+RF and LF+RR)

        Front/Rear/Left/Right percentages

✔ Ride Heights

    Track all four corners

    Supports fractional input (e.g., 1 3/8, 3/4, 1-1/2)

✔ Tires & Stagger

    Enter tire diameters

    Automatic front and rear stagger calculation

    Real‑time updates as you type

✔ Tire Pressure

    Track pressures for all four corners

✔ Fuel Usage

    Enter start fuel, end fuel, laps run, and current fuel

    Calculates:

        Fuel used

        Fuel per lap

        Estimated laps remaining

✔ Shocks

    Spring rate

    Valving (C/R)

    Shock pressure

    Rubber packers

✔ Notes Tab

    Free‑form text area for setup notes, track conditions, or driver feedback

✔ Summary Tab

    Clean, formatted output of all major calculations

✔ Setup Helper (Beta)

The Setup Helper provides suggestions for common handling issues,
but it is currently in beta and not fully accurate.
Future versions will refine the logic and expand the adjustment database.
✔ Quick‑Change Gear Ratio Calculator

    Enter top gear, bottom gear, and center section

    Calculates final drive ratio

✔ Save & Load

    Saves everything (weights, heights, tires, pressures, shocks, notes, fuel, etc.)

    Loads full setups from .json files

🛠 Requirements

    Python 3.x

    Tkinter (included with most Python installations)

To run:
bash

python3 racecar_setup.py

📦 Installation

Clone the repository:
bash

git clone https://github.com/YOUR_USERNAME/racecar-setup-tool.git
cd racecar-setup-tool
python3 racecar_setup.py

📜 License

This project is licensed under the GNU Affero General Public License v3 (AGPLv3).

This ensures:

    The software always remains free and open

    Any modified versions must also remain open

    If someone runs a modified version on a server, they must share the source

This project is built for the racing community — not for commercial exploitation.
🤝 Contributing

Contributions are welcome.
If you improve the tool, fix bugs, or add features, feel free to open a pull request.

Because this project uses AGPLv3, all contributions must remain open‑source.
🏎 Why This Exists

This tool was created to make race‑night setup work faster, cleaner, and more consistent — without relying on paid software or closed‑source tools.
It’s built for racers, by racers, and will always stay free.
