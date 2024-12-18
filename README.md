# Trump Comments and Tweets Comparison Project

## Overview

This project aims to analyze and compare comments about Donald Trump from Reddit with his tweets. By linking the sentiments and discussions from Reddit with Trump's official statements on Twitter, we hope to gain insights into public perception and discourse surrounding his presidency.

## Data Sources

1. **Reddit Comments Database**: 
   - File: `reddit_trump.txt`
   - Structure:
     ```
     Points|Composite_Score|Post|comments_lang|Post_Location|Meta|Submission_Location|Title|latlon|Comments|Comments__count_|Post_Date
     ```
   - Example Entry:
     ```
     477647774778|Sunday Times writer complains in tweet that Trump hasn't been assassinated yet. OUT OUT OUT!!|en|[]|4,782 points 38 comments submitted 1 day ago by Zig_Zagged to /r/The_Donald|/r/The_Donald|Sunday Times writer complains in tweet that Trump hasn't been assassinated yet. OUT OUT OUT!!|[49.09521549999999, -123.0264759]|"all 38 comments sorted by: best top new controversial old random q&alive (beta)[–]Leatherwood123 TN 46 points 47 points 48 points 1 day ago (8 children) Her mother was 17 years old when she was born, according to Wikipedia. Her father was 20 years older (37 yrs). Does that maybe make him a pedo?
     ```

2. **Trump Tweets Database**:
   - File: `trump_tweets.csv`
   - Structure:
     ```
     id,text,is_retweet,is_deleted,device,favorites,retweets,datetime,is_flagged,date
     ```
   - Example Entry:
     ```
     98454970654916608,Republicans and Democrats have both created our economic problems.,FALSE,FALSE,TweetDeck,49,255,2011-08-02T18:07:48Z,FALSE,2011-08-02
     ```

## Project Goals

- To extract and analyze comments from Reddit related to Donald Trump.
- To correlate these comments with tweets made by Trump.
- To visualize the sentiment and trends over time.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the required packages:
   ```bash
   pip install pandas matplotlib
   ```

## Usage

1. Load the data from `reddit_trump.txt` and `trump_tweets.csv`.
2. Perform analysis to compare comments and tweets.
3. Generate visualizations to represent the findings.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.