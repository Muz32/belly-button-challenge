# belly-button-challenge

In this assignment challenge, I built an interactive dashboard for data visualizations using JavaScript. This involved utilizing the JavaScript libraries Plotly and D3 (Data-Driven Documents). The dashboard dynamically represents data from a study examining microbial species found in human navel samples. Further information about the dataset can be found on the following webpage: https://robdunnlab.com/projects/belly-button-biodiversity/.

# App deployment on GitHub
The interactive dashboard for the visualisations can be accessed via the following link: https://muz32.github.io/belly-button-challenge/.
In the top left corner of the dashboard, there is a dropdown menu under "Test Subject ID Number:". In this menu, datasets can be selected based on different samples related to the people who participated in the experimental study. Selecting a Test Subject ID Number will immediately provide demographic information about the person, as well as a bar chart and bubble chart presenting the top 10 types and quantities of bacteria present in the sample size for that person. The charts and demographic information on the dashboard update as soon as a different Test Subject ID Number is selected.

# Files and Folders
- `index.html`: The main HTML file that contains the structure of the dashboard and links to the JavaScript files for functionality.
- `samples.json`: Copy of Dataset used for the visualizations.
  - `static`(folder)
    - `js`(folder)
      - `app.js`: JavaScript code for rendering the visualizations on the dashboard.

# Source of Data
The data was provided by **edX Boot Camps LLC** and sourced from **The Public Science Lab, Department of Applied Ecology, North Carolina State University**. For more information, please visit the [Rob Dunn Lab's Belly Button Biodiversity project page](https://robdunnlab.com/projects/belly-button-biodiversity/results-and-data)
