# Football Player Stats Visualization

This script fetches and visualizes football player statistics using the FBref website data. It generates pizza chart visualizations for selected player statistics.

## Prerequisites

Before running the script, make sure you have the necessary libraries installed:
```bash
pip install -r requirements.txt
```

## How to Use

1. Clone the repository or download the script.

2. Run the script using a Python interpreter.

3. Enter the name of the football player you want to visualize the statistics for when prompted.

4. The script will fetch player data, create a pizza chart visualization, and save the result as a JPEG image.

## Script Explanation

The script does the following:

1. Fetches the HTML content of the FBref Premier League stats page.

2. Extracts links to player profiles and saves them to an Excel sheet.

3. Defines functions to generate player data and display it using a pizza chart.

4. Reads player names, statistics keys, and values from the Excel sheet.

5. Generates a pizza chart using the `mplsoccer` library and overlays the player's image.

6. Saves the pizza chart visualization as a JPEG image.

## Credits

- The script is inspired by similar projects by @Worville, @FootballSlices, @somazerofc, and @Soumyaj15209314.
- Automated by @josephnk23.

## Example

Here's an example of how the script is used:

1. Enter the name of the player (e.g., "Hakim Ziyech").
2. The script fetches and visualizes the player's statistics using a pizza chart.
3. The visualization is saved as a JPEG image in the current directory.

## Notes

- Make sure you have an internet connection to fetch player statistics and images.
- The script requires the listed libraries to be installed.
- The execution time may vary based on internet speed and data processing.
- The generated JPEG image will be named after the player (e.g., "Hakim Ziyech.jpg").

Feel free to experiment with different player names and explore their statistics through the pizza chart visualizations!
- Automated by @josephnk23.
