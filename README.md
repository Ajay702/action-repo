# Action Repo – GitHub Webhook Source

## Overview
This repository is used to generate GitHub events (push, pull request, merge) which are sent via GitHub Webhooks to an external webhook receiver service.

## Purpose
This repo acts as the event source for testing and demonstrating GitHub webhook integrations.

## Events Triggered
- PUSH (commits pushed to branches)
- PULL_REQUEST (pull request opened)
- MERGE (pull request merged)

## How It Works
- GitHub webhooks are configured in this repository.
- Events are sent to a Flask-based webhook server.
- The webhook server stores and displays the events it receives.

## Related Repository
- webhook-repo: https://github.com/Ajay702/web-hook-repo

Short, professional, and designed to be readable in under one minute.