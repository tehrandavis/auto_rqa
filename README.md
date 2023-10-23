
# A is for Auto-Recurrence: 
**_Exploring Song Lyrics with Auto-Recurrence Analysis_**

This project contains a written walkthrough exploring patterns in song lyrics through the lens of Auto-Recurrence Quantification Analysis (aRQA). A webpage describing the methods and insights from this project can be found at: http://tehrandav.is/a_to_z_project/auto_recurrence.html

## Dependencies
This project was written in Julia 1.9.0. The following packages are required to run the code:

```
using CSV, # For reading CSV files
    DataFrames, # For working with dataframes
    Random, # For generating random numbers
    PrettyTables, # For printing tables
    TextAnalysis, # For text preprocessing
    Statistics, # For statistical analysis
    PyPlot, # For plotting
    Tidier, # For data wrangling
    StatsBase # For statistical functions
    DynamicalSystems # For calculating recurrence quantification analysis
``      

## Repo Contents

auto_rqa
├─ README.md
├─ data
│  ├─ lyrics_series.csv (lyrics series for 1 song)
│  └─ playlist_lyrics.csv (sample dataset)
├─ notebooks
│  └─ auto_recurrence.ipynb (notebook walkthrough)
└─ src (Julia environment files)
   ├─ .DS_Store
   ├─ Manifest.toml
   ├─ Project.toml
   └─ auto_rqa.jl
   
   
## Usage

- `auto_recurrence.ipynb`: A Jupyter Notebook containing code for analyzing the song lyrics data.

- `playlist_lyrics.csv`: A CSV file containing song lyrics for a selection of songs. The lyrics were obtained from [this dataset on Kaggle](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information).



**Project Overview:**
- Auto-Recurrence Quantification Analysis (aRQA) is a data analysis technique used to uncover patterns and structures in time series data. In this project, we apply aRQA to song lyrics to reveal and quantify rhythmic and thematic elements.



**Contributors:**
- Tehran Davis, 2023, [tehrandav.is](http://tehrandav.is)

**License:**
- This project is open-source and available under the [MIT License](LICENSE).