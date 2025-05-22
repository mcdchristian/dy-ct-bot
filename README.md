# Daily Commit Bot

This repository contains a GitHub Action that automatically makes commits twice daily to maintain your GitHub contribution streak.

## How it works

1. The GitHub Action runs twice daily:
   - At 7:00 AM UTC
   - At 5:00 PM UTC
2. Each run creates a new entry in `activity.log` with a timestamp
3. The changes are automatically committed and pushed to your repository

## Setup

1. Fork this repository
2. Enable GitHub Actions in your repository settings
3. The action will automatically run on the schedule

## Manual Trigger

You can manually trigger the action by:
1. Going to the "Actions" tab in your repository
2. Selecting "Daily Commit" workflow
3. Clicking "Run workflow"

## Note

This bot is for maintaining your GitHub contribution streak. Please use it responsibly and in accordance with GitHub's terms of service. 