# NBA Player Stats Explorer

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/03/National_Basketball_Association_logo.svg/400px-National_Basketball_Association_logo.svg.png" alt="NBA" width="200" height="300">


The NBA Player Stats Explorer is a Streamlit web application designed to provide users with an interactive platform for exploring and analyzing NBA player statistics from basketball-reference.com.

## Features

- **Dynamic Filtering**: Users can filter player statistics by selecting specific criteria such as year, team, and position using intuitive sidebar controls.
- **Data Visualization**: The app generates visualizations, including data tables and intercorrelation heatmaps, to help users gain insights into player performance.
- **Data Download**: Users have the option to download the displayed player statistics as a CSV file for further analysis.
  
## How to Use

1. Clone this repository to your local machine.
2. Install the required Python libraries listed in `requirements.txt` using pip.
3. Run the app by executing `streamlit run app.py` in your terminal.
4. Select the desired year, team(s), and position(s) from the sidebar to filter the player statistics.
5. Explore the displayed data and visualize intercorrelation heatmaps by clicking the corresponding buttons.

## Demo
[Live Demo](https://eda-basketball-jb.streamlit.app/)

## Technologies Used

- Python
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- NumPy
- Base64

## Data Source

The NBA player statistics data is scraped from [Basketball-reference.com](https://www.basketball-reference.com/) using the Pandas `read_html()` function.

---

Made with ❤️ by Jaweria Batool
