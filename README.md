# Video_Games_Analysis_PowerBI

## Overview 
The goal of this project is to :

- Analyze and compare global video game sales by region, platform, genre, and publisher

- Identify top-performing games by sales volume

- Understand regional market trends in video gaming

- Demonstrate how Power BI can be used to build interactive reports from raw tabular data

  ##
  
## Key Features of the Power BI Report

- Top 10+ Games by Global Sales

- Sales Breakdown by Region (NA, EU, JP, Other)

- Sales by Platform and Genre

- Publisher Performance Analysis

- Fully Interactive Visuals with Filters and Slicers

##

## Data Description

The dataset consists of the top-selling video games across different gaming platforms and regions. The key metrics include North America Sales, Europe Sales, Japan Sales, Other Region Sales, and Global Sales (in millions of units).

| Column Name    | Description                                                    |
| -------------- | -------------------------------------------------------------- |
| `Rank`         | Rank based on global sales                                     |
| `Name`         | Name of the video game                                         |
| `Platform`     | Platform on which the game was released (e.g., Wii, PS3, X360) |
| `Year`         | Release year of the game                                       |
| `Genre`        | Game genre (e.g., Action, Sports, Role-Playing)                |
| `Publisher`    | Company that published the game                                |
| `NA_Sales`     | North America sales (in millions of units)                     |
| `EU_Sales`     | Europe sales (in millions of units)                            |
| `JP_Sales`     | Japan sales (in millions of units)                             |
| `Other_Sales`  | Sales in other regions (in millions of units)                  |
| `Global_Sales` | Total global sales (in millions of units)                      |

##

## Data Preparation Steps

The data was cleaned and pre-processed using Power BI's Power Query Editor. Here’s a summary of the steps taken:

### Cleaning & Transformation

- ***Verified Column Types***: Ensured all numerical columns (sales figures) are correctly formatted as decimal numbers and categorical fields as text.

- ***Renamed Columns***: Simplified and standardized column names (e.g., NA_Sales, EU_Sales, etc.)

- ***Handled Null Values***: Checked for and confirmed no missing values in all records used.

##

## Power BI Report

The Power BI dashboard includes the following visuals:

**1. Global Sales Leaderboard**

  - Bar chart of the top-selling games by Global Sales

**2. Sales by Region (NA, EU, JP, Other)**

  - Region sales Matrix and Card Visualizations.

  - Dynamic interactivity to analyze regional preferences

**3. Publisher and Platform Analysis**

   - Slicers for Publishers

   - Sales comparison across platforms like Wii, NES, PS3, DS, etc.

**4. Genre Trends**

   - Sales distribution across genres (e.g., Sports, Action, Platform)


 ##
 
<img width="1342" height="747" alt="image" src="https://github.com/user-attachments/assets/d602c9f7-a66e-4d0f-be4d-a8ac9d13066c" />

##

## Conclusion

The analysis of global video game sales across platforms, genres, regions, and titles reveals several key market trends and insights that can inform decisions for publishers, developers, and marketers in the gaming industry.

- **Top Performing Games**

    - Wii Sports stands out as the best-selling video game globally with 83 million units sold, significantly ahead of the second-ranked Super Mario Bros. (40 million).

    - Other major performers include Mario Kart Wii, Wii Sports Resort, Pokemon Red/Blue, and Tetris, indicating the dominance of legacy franchises and Nintendo's consistent success over time.

- **Regional Market Insights**

    - North America leads with 4,200+ million units sold, making it the largest video game market in the dataset.

    - Europe follows with 2,338 million units, while Japan contributes around 1,184 million units, and other regions total 774 million units.

- **Regional preferences**

    - Role-Playing and Simulation genres perform strongly in Japan.

    - Action and Sports dominate in North America and Europe.

- **Genre Analysis**

    - Action is the most popular genre overall with 1,751.18 million units sold, followed by Sports (1,330.93M) and Shooter (1,037.37M).

    - These top genres highlight player preferences for fast-paced, competitive gameplay and real-world simulations.

- **Platform Performance**

    - PS2 is the most successful platform by total global sales (1,255.64M), followed by X360, PS3, and Wii.

    - Platforms from Sony, Microsoft, and Nintendo dominate, reflecting strong brand loyalty and massive install bases during their respective generations.

- **Publisher Dominance**

    - Nintendo is the clear market leader, publishing most of the top 20 games and consistently generating high sales across all regions and platforms.

    - Nintendo’s family-friendly, accessible, and nostalgic titles have helped it maintain strong performance globally.
