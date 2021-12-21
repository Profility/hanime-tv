# hanime-scraper
A simple python scraper for hanime.tv I wrote because I was extremely bored.

## Getting Started

### Prerequisites

You need these modules:

* [bs4](https://pypi.org/project/bs4/)
* [requests](https://pypi.org/project/requests/)

## Usage
Take a peek inside the hanime.py file and you will see comments on what the functions are, what they return, etc.

Sample usage:
```python
$ import hanime
$ print(hanime.info("https://hanime.tv/videos/hentai/lovely-heart-2"))
```

Output:
```python
{
  'brand': 'Mary Jane'
  'branduploads': '118'
  'releasedate': 'February 6, 2020',
  'uploaddate': 'February 11, 2020',
  'views': '3,669,440 views',
  'censored': True,
  'alternatetitles': ['Lovely Heart', 'らぶりー♡', '러블리 하트', 'Lovely', 'Lovely ♡', 'Lovely Heart']
}
```
