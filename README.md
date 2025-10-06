# Scientific Computing Course

Welcome to the Scientific Computing course! This repository contains everything you need to get started with Python-based scientific computing using industry-standard tools and libraries.

## 🚀 Quick Start

**New to this?** Start here:
1. Read [STUDENT_SETUP.md](STUDENT_SETUP.md) for detailed setup instructions
2. Choose your preferred method:
   - **Method 1 (Recommended)**: VS Code Dev Containers - seamless integration
   - **Method 2**: Jupyter Server - traditional notebook interface
3. Open `00_getting_started.ipynb` to verify your setup

## 📦 What's Included

This course environment provides:
- **Python 3.12** - Latest stable Python
- **NumPy** - Numerical computing with arrays
- **Pandas** - Data analysis and manipulation
- **Matplotlib** - Data visualization
- **SciPy** - Scientific computing tools
- **Scikit-learn** - Machine learning library
- **JupyterLab** - Interactive notebook interface

## 📁 Repository Structure

```
.
├── README.md                  # This file
├── STUDENT_SETUP.md          # Detailed setup instructions
├── .devcontainer/            # VS Code Dev Container configuration
├── start-jupyter.sh          # Mac/Linux helper script
├── start-jupyter.bat         # Windows helper script
├── 00_getting_started.ipynb  # Getting started notebook
└── [your notebooks here]     # Your coursework goes here
```

## 🛠️ Prerequisites

You need to install:
1. **Docker Desktop** - [Download here](https://www.docker.com/products/docker-desktop/)
2. **VS Code** - [Download here](https://code.visualstudio.com/)

That's it! Everything else runs inside the Docker container.

## 📚 Getting Help

### Setup Issues
See [STUDENT_SETUP.md](STUDENT_SETUP.md) for detailed troubleshooting.

### Course Content
Contact your instructor or TA with questions about assignments and course material.

### Technical Problems
When reporting issues, include:
1. Your OS (Windows/Mac/Linux)
2. Docker version: `docker --version`
3. The exact error message
4. What you were trying to do

## 💡 Tips for Success

- **Save your work**: Files are saved to your local machine, but commit to Git regularly
- **Keep Docker running**: Don't quit Docker Desktop while working
- **Update the image**: Run `docker pull ghcr.io/paulgribble/scicomp:2025` periodically for updates
- **Restart kernels**: If notebook output looks strange, restart the kernel
- **Use keyboard shortcuts**:
  - `Shift+Enter` - Run cell and move to next
  - `Ctrl+Enter` - Run cell and stay
  - `Esc` then `A` - Insert cell above
  - `Esc` then `B` - Insert cell below

## 🔄 Daily Workflow

### Using Dev Containers
1. Open VS Code
2. Open this folder
3. Click "Reopen in Container" if needed
4. Start working!

### Using Jupyter Server
1. Open terminal in this folder
2. Run `./start-jupyter.sh` (Mac/Linux) or `.\start-jupyter.bat` (Windows)
3. Copy the URL with token
4. Connect VS Code to the Jupyter server
5. Start working!
6. Press `Ctrl+C` in terminal when done

## 📖 Learning Resources

### Official Documentation
- [NumPy](https://numpy.org/doc/stable/)
- [Pandas](https://pandas.pydata.org/docs/)
- [Matplotlib](https://matplotlib.org/stable/contents.html)
- [SciPy](https://docs.scipy.org/doc/scipy/)
- [Scikit-learn](https://scikit-learn.org/stable/documentation.html)

### Jupyter Tips
- [JupyterLab Documentation](https://jupyterlab.readthedocs.io/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/) for notebook cells

## ⚖️ Academic Integrity

- Your work should be your own
- Cite sources and collaborations appropriately
- Follow your institution's academic integrity policies

## 📝 License

Course materials are provided for educational purposes. Check with your instructor regarding usage rights.

---

**Ready to start?** Open `00_getting_started.ipynb` and run through the examples!

Questions? Check [STUDENT_SETUP.md](STUDENT_SETUP.md) or contact your instructor.
