# Project Estimator

## Getting Started

FlutterFlow projects are built to run on the Flutter _stable_ release.

## Overview

This application is designed to automate the process of creating and estimating backlogs for software development projects. Leveraging advanced AI and machine learning techniques, it significantly reduces the time and effort required for backlog creation while improving accuracy.

## Tech Stack

- **Frontend**: Flutterflow (for rapid mobile app development)
- **Backend**: Python (for data processing and model serving)
- **AI/ML**: BERT (for natural language understanding), Custom Machine Learning Model (for estimation), Gemini Model (for generating multiple backlog options)

## Methodology

1. **User Story Input**: Users provide a user story as input.
2. **Gemini Processing**:
   - **Multiple Backlog Generation**: Gemini is invoked to generate several potential backlogs based on the user story.
   - **Detail Extraction**: Each generated backlog is analyzed to extract specific details.
   - **Narrative Creation**: The extracted details are combined into a coherent narrative for each backlog.
3. **BERT Tokenization**: The narrative of each backlog is tokenized using BERT to prepare it for the machine learning model.
4. **Estimation**: The tokenized backlog is fed into a pre-trained machine learning model, which predicts the effort required to complete the backlog.
5. **Output**: The application presents the user with multiple backlog options, along with estimated effort for each.

## Screenshots

![Home Page](https://github.com/Doko27/project-estimator-ff-gemini/blob/main/homepage.png)

![Estimate Page](https://github.com/Doko27/project-estimator-ff-gemini/blob/main/estimatepage.png))

## Key Features

- **Automated Backlog Creation**: Quickly generate detailed backlogs from user stories.
- **Accurate Estimations**: Leverage machine learning to provide reliable effort estimates.
- **Multiple Backlog Options**: Explore various possibilities based on the user story.
- **User-Friendly Interface**: Intuitive interface for easy interaction.

## How to Use

1. **Input**: Enter a user story into the application.
2. **Generate**: Click the "Estimate Now" button.
3. **Review**: Review the generated backlogs and their associated estimates.

## Future Enhancements

- **Integration with project management tools**: Seamlessly integrate with popular tools like Jira and Trello.
- **Continuous learning**: Improve estimation accuracy over time by incorporating feedback from users.
- **Natural language interface**: Allow users to interact with the system using natural language.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.
