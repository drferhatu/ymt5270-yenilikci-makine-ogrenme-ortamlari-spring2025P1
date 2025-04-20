# Algorithms and Programming II - Semester Capstone Project

## Overview

Welcome to the Algorithms and Programming II course project at Fırat University, Technology Faculty, Software Engineering Department. This project involves developing interactive web applications to implement, visualize, and analyze algorithms using Python and Streamlit.

## Learning Objectives

This project is designed to help you:

- Implement complex algorithms in Python
- Create interactive visualizations that demonstrate algorithm behavior
- Analyze and understand the time and space complexity of algorithms
- Practice modern software development workflows using Git and GitHub
- Gain experience with web application development and deployment
- Improve technical documentation skills

## Technology Stack

- **Programming Language:** Python 3.8+
- **Web Framework:** Streamlit
- **Version Control:** Git and GitHub
- **Deployment:** Streamlit Cloud

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.8 or higher
- Git
- A GitHub account
- A text editor or IDE (e.g., VS Code, PyCharm)

### Setting Up Your Development Environment

1. **Accept the GitHub Classroom Assignment**
   - Click on the assignment link shared by your instructor
   - This will create a personal copy of the project template in your GitHub account

2. **Clone Your Repository**
   ```bash
   git clone https://github.com/firat-university-algorithms/your-project-repo.git
   cd your-project-repo
   ```

3. **Create a Virtual Environment**
   ```bash
   # On Windows
   python -m venv venv
   venv\Scripts\activate

   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

## Project Requirements

### Core Components

Each project must include:

1. **Algorithm Implementation**
   - Correctly implement your assigned algorithm
   - Handle edge cases and error conditions
   - Optimize for performance where possible

2. **Interactive Interface**
   - Create user controls to manipulate inputs and parameters
   - Allow users to adjust algorithm settings and see results in real-time
   - Provide clear instructions for users

3. **Visualization**
   - Create visual representations of how your algorithm works
   - Illustrate the algorithm's step-by-step execution
   - Use appropriate charts, graphs, or custom visualizations

4. **Step-by-Step Explanation**
   - Include an option to walk through the algorithm's execution
   - Explain each major step in the algorithm
   - Highlight key decisions and operations

5. **Complexity Analysis**
   - Document the time complexity (Big O notation)
   - Document the space complexity
   - Explain how the complexity changes with different inputs

6. **Test Cases**
   - Include various examples demonstrating algorithm behavior
   - Provide best-case, average-case, and worst-case scenarios
   - Allow users to input custom test cases

### Repository Structure

Your repository should contain:

```
project-repository/
├── app.py                     # Main Streamlit application
├── algorithm.py               # Implementation of your algorithm
├── utils.py                   # Helper functions
├── visualizer.py              # Visualization components
├── README.md                  # Project documentation
├── requirements.txt           # Python package dependencies
├── test_algorithm.py          # Unit tests
├── examples/                  # Example inputs and outputs
│   ├── example1.json
│   └── example2.json
├── data/                      # Sample data files (if applicable)
│   ├── sample1.csv
│   └── sample2.csv
└── docs/                      # Additional documentation
    ├── algorithm_description.md
    └── screenshots/
        ├── screenshot1.png
        └── screenshot2.png
```

## Documentation Requirements

Your README.md should include:

- Project title and description
- Algorithm explanation with mathematical notation when appropriate
- Installation and usage instructions
- Screenshots of the application
- Complexity analysis with explanations
- Examples of inputs and outputs
- Known limitations and future improvements
- References and resources used

## Deployment Instructions

### Deploying to Streamlit Cloud

1. Create a free account on [Streamlit Cloud](https://streamlit.io/cloud)
2. Connect your GitHub repository
3. Configure your app settings
4. Deploy your application
5. Add the deployment URL to your README.md

## Evaluation Criteria

Your project will be evaluated based on:

- Correctness of algorithm implementation (40%)
- Quality of visualization and user interface (20%)
- Documentation quality (15%)
- Code organization and clarity (15%)
- Creativity and additional features (10%)

## Submission Guidelines

1. Ensure your code is well-commented and follows Python best practices
2. Verify all required components are included
3. Test your application thoroughly
4. Update your README.md with all required information
5. Commit and push your final changes to GitHub
6. Deploy your application to Streamlit Cloud
7. Submit the final version by the deadline: **June 23, 2025, 23:59**

## Resources

### Streamlit Resources
- [Streamlit Documentation](https://docs.streamlit.io)
- [Streamlit Components](https://streamlit.io/components)
- [Streamlit Deployment](https://docs.streamlit.io/cloud)

### Algorithm Resources
- Introduction to Algorithms (CLRS) - 4th Edition
- Algorithm Design Manual - Steven Skiena
- [VisuAlgo](https://visualgo.net)
- [Algorithm Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

### GitHub Resources
- [Git & GitHub for Beginners](https://docs.github.com/en/get-started)
- [GitHub Classroom Guide](https://github.com/education/classroom)

## Frequently Asked Questions

**Q: Can I change my assigned algorithm?**  
A: Only in exceptional cases. Please contact your instructor with a valid reason if you need to request a change.

**Q: Can I use additional libraries beyond the core requirements?**  
A: Yes, but ensure they are properly documented in your requirements.txt file.

**Q: How detailed should the visualization be?**  
A: It should clearly illustrate each major step of the algorithm's execution. The visualization should help someone understand how the algorithm works.

**Q: Can I work in groups?**  
A: No, this is an individual project. Each student has a unique algorithm assignment.

**Q: What if I encounter technical difficulties with Streamlit deployment?**  
A: Document the issue in your README and we can explore alternative deployment options if necessary.

## Contact Information

For questions or assistance, please contact:

- **Instructor:** Assoc. Prof. Ferhat UÇAR
- **Office Hours:** 
  - Fridays: 10:30 - 12:00

- **Office Location:** Technology Faculty - A Section, 3rd floor.
