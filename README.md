# Newswatch

This project is a bash script that reads through given stock market news articles for big tech keywords in order to create a prediction for upcoming stock movements
## The Problem

As big tech expands, it is difficult for the average person to keep up with technology. There are new models and new technology being published every day and it leaves the average person behind in a field that requires a lot of knowledge. 

## How It Works



<img width="673" height="1662" alt="Flowchart drawio" src="https://github.com/user-attachments/assets/faea0562-44f6-452d-b29c-b486c373ba9b" />


## Tech Stack

- **Language:** Bash, Python
- **Libraries:** jq
- **External tools:** curl, grep, cron

## Setup

```bash
git clone https://github.com/your-username/cs193-final-project
cd Newswatch
chmod +x newswatch.sh
cp .env.example .env
```
Open your environment then run
```bash
NEWS_USERNAME="your-news-login"
NEWS_PASSWORD="your-news-password"
LLM_API_KEY="your-api-key"
NOTIFY_TARGET="your-email-or-topic"
```
## Usage


```bash
./newswatch.sh
open output/index.html

```

## Roadmap
- [ ] Notifications when found description
- [ ] Track accuracy each day based on previous testing iterations
- [ ] auto update companies based off of performance and relevancy.

## Author

Hari Sagar, https://github.com/Hari-Sagar.
