# Building Towards Computer Use with Anthropic

This repository contains learning materials and code examples from the "Building Towards Computer Use with Anthropic" course by DeepLearning.AI. The course focuses on understanding and implementing Anthropic's computer use capabilities through their API.

## Course Overview

- **Instructor**: Colt Steele (Head of Curriculum at Anthropic)
- **Duration**: 1 Hour 35 Minutes
- **Level**: Beginner
- **Prerequisites**: Basic Python knowledge

## Repository Structure

```
.
├── LICENSE                 # MIT License
└── notebooks/             # Course notebooks and materials
    ├── L2/               # Lesson 2 - Working with the API
    │   ├── helper.py
    │   ├── Lesson_2.ipynb
    │   └── requirements.txt
    ├── L3/               # Lesson 3 - Multimodal Requests
    │   ├── helper.py
    │   ├── Lesson_3.ipynb
    │   ├── requirements.txt
    │   └── images/
    │       ├── food.png
    │       ├── invoice.png
    │       ├── packages.png
    │       └── plant.png
    ├── L4/               # Lesson 4 - Real World Prompting
    │   ├── helper.py
    │   ├── Lesson_4.ipynb
    │   └── requirements.txt
    ├── L5/               # Lesson 5 - Prompt Caching
    │   ├── helper.py
    │   ├── Lesson_5.ipynb
    │   └── files/
    │       └── frankenstein.txt
    └── L6/               # Lesson 6 - Tool Use
        ├── helper.py
        ├── Lesson_6.ipynb
        └── requirements.txt
```

## Course Content

1. Introduction (3 mins)
2. Overview (5 mins)
3. Working with the API (15 mins)
   - Implementation in `notebooks/L2/`
4. Multimodal Requests (12 mins)
   - Implementation in `notebooks/L3/`
   - Includes example images for practice
5. Real World Prompting (17 mins)
   - Implementation in `notebooks/L4/`
6. Prompt Caching (12 mins)
   - Implementation in `notebooks/L5/`
   - Includes sample text files
7. Tool Use (17 mins)
   - Implementation in `notebooks/L6/`
8. Computer Use (10 mins)
9. Conclusion (1 min)

## Setup and Requirements

Each lesson folder contains its own:
- `requirements.txt` for Python dependencies
- `helper.py` for utility functions
- Jupyter notebook (`.ipynb`) with the lesson content

## What I Learned

- Anthropic's family of models and their approach to AI research
- Making API requests to Claude and optimizing parameterss
- Multi-modal prompting combining text and image content
- Effective prompting techniques and prompt caching
- Tool-use workflows and building AI assistants
- Computer Use applications with Anthropic's models

## Resources

- Course Platform: DeepLearning.AI
- [Anthropic API Documentation](https://docs.anthropic.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Notes

Each lesson folder contains complete materials needed for that section of the course. Make sure to install the required dependencies from each lesson's `requirements.txt` before running the notebooks.