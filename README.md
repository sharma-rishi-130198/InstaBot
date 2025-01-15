# InstaBot

## Overview

In this project, I developed an Instagram Automation Bot to perform various automated tasks on Instagram, demonstrating my proficiency in web automation, scripting, and Python programming. The bot interacts with Instagram’s web interface using browser automation tools, performing tasks such as searching for profiles, liking/unliking posts, following/unfollowing users, and extracting follower data.

## Features

### 1. **Search Automation**
- Logs into an Instagram account with provided credentials of a dummy account.
- Searches for the keyword "food" and retrieves a list of Instagram handles without printing hashtags.

### 2. **Profile Navigation**
- Opens specific Instagram profiles (e.g., "So Delhi") for further actions.

### 3. **Follow/Unfollow Automation**
- Follows a specific handle and prints a message if already following.
- Unfollows the handle and prints a message if already unfollowed.

### 4. **Post Interaction**
- Automates liking and unliking of the top 30 posts of a specified handle (e.g., "dilsefoodie"), ensuring no duplicate actions.

### 5. **Follower Data Extraction**
- Extracts usernames of the first 500 followers for specified handles (e.g., "foodtalkindia" and "sodelhi").
- Identifies mutual followers by cross-referencing the follower list.

### 6. **Story Interaction**
- Automates story checks for a handle and provides feedback for different scenarios:
  - If the story is already viewed.
  - If the user has no story.
  - If the story is available but not yet seen.

## Technologies Used
- **Python**: Core programming language for implementing the bot.
- **Selenium**: For browser automation and interacting with Instagram's web interface.
- **Pandas**: For efficient data handling and analysis of follower data.
- **Matplotlib**: For visualizing trends or statistics related to followers or posts.
- **Chrome WebDriver**: To control and automate browser interactions.

## Key Learnings
- Gained hands-on experience with web automation and browser control using Selenium.
- Implemented robust error handling for scenarios like already-followed accounts or non-existent stories.
- Enhanced skills in data extraction, validation, and processing by efficiently handling large follower datasets for analysis and comparison.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Update the script with your Instagram credentials.
4. Run the script using a Python IDE or terminal.

## Future Enhancements

- Add functionality to download posts or stories.
- Implement a GUI for easier interaction with the bot.
- Expand bot capabilities to include direct messaging.

## Applications
This project is relevant for use cases like:

- Automating redundant/daily tasks for social media account management.
- Extracting insights from Instagram profiles for analytics.
- Demonstrating automation skills for software engineering roles.