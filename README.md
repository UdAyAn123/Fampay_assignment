# Fampay_assignment
## Overview

This Django project fetches YouTube videos using the YouTube Data API and stores them in a database. It utilizes Django Cron Jobs to periodically call the API, ensuring that the video data is up-to-date.

## Method Used

The project uses Django Cron Jobs (`django_cron`) to fetch videos every 10 minutes using the YouTube Data API. The fetched video details are then saved to the database.

## Setup Guide

1. **Clone the project:**
   ```bash
   git clone https://github.com/yourusername/youtube_fetch_api.git
2.**Python Setup:**
  Ensure that your system has the required Python setup.
3. **Setup Crontab:**
  Set up the cron job to run the Django Cron Job.
4. python manage.py runserver
