# Zock

## Overview

Zock is a web application, runs in Google Chrome. It’s basically a CRM for HR managers. 
Main goal is to provide an easy way to manage recruitment, employment, payroll and performance.

Also, goal number two is to provide a way for employee to use Zock for interacting with 
HR's bureaucracy (e.g. uploading document scans, requesting vacations, etc).

## Features

Let’s divide all features in 6 categories:
1. General features
1. Recruitment management
1. Employee management
1. Payroll management
1. Performance management
1. Project administration

Also, let's define our priorities:
- _0_. The highest priority. Without this features the project will make no sense.
- _1_. Important features. Without them project can still be used, but will be sad.
- _2_. Not so important
- _3_. Would be nice to have these features.

### General features

Features, that will be used across all application.

| Priority | Name | Description            |
| :------: | ---- | ---------------------- |
|     0    | Auth | You know why :) |
|     1    | User roles | Defines whether user is an admin, a HR manager or an employee |
|     1    | Email notifactions | Notify user about something happens in the app |
|     2    | User settings | Make possible customize web app (e.g. dark theme, notifications settings, etc.) |
|     3    | Dark theme | Yep. |
|     3    | Two factor auth | Security. |

### Recruitment management

Allows to manage candidates: kipping a list and tracking the progress of each candidate recruitment.

| Priority | Name | Description            |
| :------: | ---- | ---------------------- |
|     0    | Candidates crud | A list of candidates with CRUD functionality |
|     1    | Candidate progress | A page with recruitment progress of candidate and recruitment history |
|     2    | Candidate crawler | A crawler that searches the internet for new candidates and adds them to the list |

_todo:_ Specify candidate page.

### Employee management

_todo_

### Payroll management

_todo_

### Performance management

_todo_ 

### Project administration

_todo_

## Tech overview

- Docker or K8s
- PHP/Symfony
- MySQL
- Vue/nuxt/ts + bootstrap 5
