![IMG_20220705_005633](https://user-images.githubusercontent.com/74001397/177223778-7c4cba1b-d97a-47f6-8356-c6c3b245f9fd.jpg)

Given a subreddit name and a keyword, this script will return all posts from a specified listing (default is 'top') that contain the provided keyword.

## Installation
```
git clone https://github.com/rly0nheart/reddit-post-scraping-tool.git
```

```
cd reddit-post-scraping-tool
```

## Usage
```
python reddit-post-scraping-tool.py --keyword [keyword] --subreddit [subreddit name (without 'r/')]
```

## Optional arguments
| Option       | Argument    | Choices    | Usage     |
| -------------|:-----------:|-----------:|:---------:|
| -l/--listing | LISTING     | [controversial, hot, best, new, rising]  |  listing: controversial, hot, best, new, rising (default: top)  |
| -c/--limit   | NUMBER      | 1-100      |  results limit (default: 10)|
| -t/--timeframe| TIMEFRAME  | [hour, day, week, month, year]           |  timeframe: hour, day, week, month, year (default: all) |
