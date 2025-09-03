# Coding & AI Tutoring by Trevor Paul Anderson-Webb

Hi 👋, I’m Trevor Paul Anderson-Webb.  
I provide independent consulting and tutoring services in **coding** and **artificial intelligence**.  

## What I Do
- Personalized guidance in Python, JavaScript/TypeScript, and backend development  
- AI & machine learning basics explained with hands-on examples  
- Step-by-step tutorials, coding resources, and project support  

## Why I Do It
I believe learning technology should be accessible to everyone.  
That’s why I dedicate my time to creating resources, lessons, and tools that help people build real skills without barriers.  

---

*This repository serves as an overview of my consulting and tutoring services. All support allows me to continue dedicating time to teaching and creating accessible resources.*
# Machine Learning Algorithms

## Gradient Descent Implementation

This repository contains implementations of various machine learning algorithms, including a Jupyter notebook demonstrating gradient descent for linear regression.

### Prerequisites

Before running the notebooks, make sure you have the following installed:
- Python (3.8 or higher recommended)
- Git (for cloning the repository)
- A code editor (VS Code recommended)

### Detailed Setup Instructions

1. First, install Python from [python.org](https://python.org)
   - During installation, make sure to check "Add Python to PATH"
   - Verify installation by opening a terminal and typing:
     ```bash
     python --version
     ```

2. Install Git from [git-scm.com](https://git-scm.com)
   - Verify installation:
     ```bash
     git --version
     ```

3. Clone this repository:
   ```bash
   git clone https://github.com/TrevorPaull/machinelearning.git
   cd machinelearning
   ```

4. Create a virtual environment (recommended):
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

5. Install required packages:
   ```bash
   pip install numpy matplotlib jupyter pandas scikit-learn
   ```

6. Verify installations:
   ```bash
   python -c "import numpy; import matplotlib; import jupyter"
   ```

### Running the Notebooks

1. Open a terminal or command prompt
2. Navigate to the project directory:
```bash
cd path/to/machinelearning
```
3. Start Jupyter Notebook:
```bash
jupyter notebook
```
4. In the browser window that opens, click on `C1_W1_Lab04_Gradient_Descent_Soln.ipynb`

### Notebook Contents

The gradient descent notebook covers:
- Implementation of gradient descent for linear regression
- Visualization of the gradient descent process
- Effect of learning rate on convergence
- Practical example using house price prediction

### File Structure

- `C1_W1_Lab04_Gradient_Descent_Soln.ipynb`: Main Jupyter notebook containing the implementation
- `deeplearning.mplstyle`: Matplotlib style file for plots
- `lab_utils_uni.py`: Utility functions for plotting and visualization

