# Quillo Beta v1.0-B1

## Overview
Welcome to Quillo v1.0-1B, the first Beta for the versatile command-line web browser designed to enhance your browsing experience.

## Getting Started
Launch Quillo effortlessly with the following command:
```bash
quillo
```
This command opens a Quillo window, setting the stage for your exploration.

## Navigating Websites
Explore websites seamlessly using the following commands:
- Open in a new tab:
  ```bash
  quillo -f -o "Website URL"
  ```
- Open in the current tab:
  ```bash
  quillo -f -g "Website URL"
  ```

## Google Search
Effortlessly perform Google searches:
```bash
quillo -s "Query"
```

## Links and Navigation
Navigate through webpage links with ease:
- Open in a new tab:
  ```bash
  quillo -f -o LINKNUMBER
  ```
- Open in the current tab:
  ```bash
  quillo -f -g LINKNUMBER
  ```
All links on the webpage follow the format:
```
linkText [LINKNUMBER]
```

## Tab Management
Switch between tabs effortlessly:
```bash
quillo -t TABNUMBER
```

## New Tab
Open a new tab with a simple command:
```bash
quillo -n
```

## Settings
Explore and customize settings using the following commands:
- View settings help:
  ```bash
  quillo -a help
  ```
- Modify settings:
  ```bash
  quillo -a SETTING=VALUE
  ```

Enjoy a smooth browsing experience with Quillo!