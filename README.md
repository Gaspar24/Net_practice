# Net Practice

## Overview

The **Net Practice** project focuses on configuring small-scale networks and solving networking problems to make them functional. It is an excellent introduction to understanding TCP/IP addressing and network troubleshooting.

### Key Concepts:
- **TCP/IP Addressing**: Learn how devices communicate within a network and configure IP addresses, subnet masks, and gateways.
- **Network Simulation**: Work with non-functional network diagrams to achieve specific goals.
- **Practical Application**: Modify and test configurations until the network operates correctly.

## How It Works

1. **Interface Setup**:
   - Download the project files from the project page.
   - Extract the files into your preferred directory.
   - Open the `index.html` file in your web browser to access the training interface.

2. **User Options**:
   - Input your login to practice.
   - Leave the login field empty to access the correction version.

3. **Levels**:
   - There are 10 levels, each presenting a non-functioning network diagram.
   - Each level includes a goal to achieve and allows you to verify your configuration with the "Check again" button.
   - Export your configuration using the "Get my config" button before proceeding to the next level.

## Mandatory Rules

### Steps to Solve Each Level:
1. **Understand the Goal**: Read the problem statement and determine the necessary configuration changes.
2. **Modify Configuration**: Adjust the unshaded fields in the network diagram.
3. **Verify Configuration**: Use the "Check again" button to test your solution.
4. **Export Configuration**: Save your configuration using the "Get my config" button.

### Additional Information:
- Logs are available at the bottom of the interface to diagnose errors.
- Progress through the levels by solving each network issue.

### JSON Visualization

To view exported JSON files (e.g., `level1.json`) in a browser, follow these steps:

1. Open a terminal.
2. Navigate to the directory containing the JSON file.
3. Start a simple HTTP server using Python:

   For Python 3:
   ```sh
   python3 -m http.server
   ```

   For Python 2:
   ```sh
   python -m SimpleHTTPServer
   ```

4. Open your browser and go to:
   ```
http://localhost:8000/level1.json
   ```
   This will display the JSON content in your browser.

---

## Key Learnings

Through this project, you will:
- Gain hands-on experience in network configuration and troubleshooting.
- Develop a solid understanding of IP addressing, subnetting, and gateway configurations.
- Learn to analyze and resolve network issues using a systematic approach.

## Submission Guidelines

- Ensure that all 10 levels are completed.
- Save and commit your exported configurations to your Git repository.
- Include a `README.md` file explaining the project and your learnings.

---

Feel free to reach out if you have any questions or need further clarifications.
