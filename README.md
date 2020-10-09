# Github Archiver Template

A template to create a self-scraping archiver using Github Actions. Based entirely on @simonw's [clever idea](https://simonwillison.net/2020/Oct/9/git-scraping/).

# To use

1. [Create a repository](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template) from this template.

![Template button example](https://docs.github.com/assets/images/help/repository/use-this-template-button.png)

2. Edit [this line](.github/workflows/scrape.yml#L17) to include the correct URL that you want to archive. Maybe also change the output file from 'results.csv' if you want something else. You can also do things like pretty print the output here if JSON, as the inspiration project did.

3. To change the default daily 12pm schedule, edit [this line](.github/workflows/scrape.yml#L7), using cron notation. (If you edit in Github, it will helpfully interpret the cron notation on hover.)
