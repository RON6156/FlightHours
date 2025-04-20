# FlightHours

**FlightHours** is a lightweight, browser-based flight time calculator designed for aviation enthusiasts, airline simulation gamers, or anyone curious about how long a flight might take between two points.

## Features

- Select from a list of real-world aircraft
- Enter a custom route distance (in kilometers)
- Instantly calculate flight duration in hours and minutes
- Stylish UI with responsive design
- Uses:
  - [Select2](https://select2.org/) for enhanced dropdowns
  - [SweetAlert2](https://sweetalert2.github.io/) for modern alert dialogs
  - [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins) for clean typography
  - [Ionicons](https://ionic.io/ionicons) for scalable icons (if needed in future updates)

## Live Demo

Just open `index.html` in your browser — no installation required.

## Usage

1. Select your **Aircraft Type** from the dropdown.
2. Enter the **Route Distance** in kilometers (e.g., `13700`).
3. Click **Calculate** to get the estimated flight time.

## Aircraft Speed Reference

| Aircraft             | Speed (kph) |
|----------------------|-------------|
| ATR 72-600           | 551         |
| Dash 8 Q400          | 734         |
| A320-200             | 881         |
| A321-200             | 835         |
| A321-NEO             | 884         |
| A330-300 / 900neo    | 801         |
| B777-300ER           | 1036        |
| A350-900 / -1000     | 860         |
| A350-900ULR          | 848         |
| A380                 | 964         |

> Note: Aircraft with the same speed are grouped under one key.

## How It Works

The calculator divides the input distance by the selected aircraft's speed to compute the time. The result is then split into hours and minutes and displayed via a modal dialog.

## License

This project is open source and free to use. Feel free to modify or expand upon it for your own purposes.

---

Created by **@RonDev**
