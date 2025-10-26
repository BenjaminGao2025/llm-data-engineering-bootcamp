# 🚀 PySpark Fundamentals - Complete Tutorial

[![PySpark](https://img.shields.io/badge/PySpark-4.0.1-orange.svg)](https://spark.apache.org/docs/latest/api/python/)
[![Python](https://img.shields.io/badge/Python-3.14.0-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive, beginner-friendly PySpark tutorial with hands-on exercises and detailed explanations.

## 📚 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Structure](#notebook-structure)
- [Learning Outcomes](#learning-outcomes)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [Support](#support)

## 🎯 Overview

This interactive Jupyter Notebook provides a complete introduction to PySpark (Apache Spark's Python API) for beginners. Learn distributed data processing through practical examples, clear explanations, and hands-on exercises.

## ✨ Features

- ✅ **Complete Setup Guide** - Environment configuration for macOS
- ✅ **3 DataFrame Creation Methods** - Lists, Pandas, CSV
- ✅ **Comprehensive Operations** - Filtering, transformations, aggregations
- ✅ **Hands-on Exercises** - 12+ practice problems with solutions
- ✅ **Collapsible Sections** - Well-organized Markdown structure
- ✅ **Real-world Examples** - Practical use cases and scenarios
- ✅ **Bank Analogies** - Easy-to-understand comparisons
- ✅ **Google Colab Alternative** - No local setup required

## 📋 Prerequisites

### Local Environment (Recommended)
- macOS (M1/M2/M3/M4) or similar Unix-based system
- Python 3.10+
- Java OpenJDK 17
- Jupyter Notebook or VS Code with Jupyter extension

### Cloud Alternative (Easiest)
- Google Account (for Google Colab)
- No installation required!

## 🔧 Installation

### Option 1: Local Setup (macOS)

```bash
# 1. Install Homebrew (if not installed)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2. Install Java 17
brew install openjdk@17

# 3. Create Python virtual environment
python3 -m venv ~/.venvs/pyspark-latest
source ~/.venvs/pyspark-latest/bin/activate

# 4. Install PySpark and dependencies
pip install pyspark pandas jupyter

# 5. Clone this repository
git clone https://github.com/YOUR_USERNAME/pyspark-fundamentals.git
cd pyspark-fundamentals

# 6. Launch Jupyter Notebook
jupyter notebook PySpark_Fundamentals.ipynb
```

### Option 2: Google Colab (No Setup)

1. Visit [Google Colab](https://colab.research.google.com)
2. Upload `PySpark_Fundamentals.ipynb`
3. Run the setup cell to install PySpark
4. Start learning!

## 🚀 Usage

### Running the Notebook

1. **Select Kernel** (Local setup)
   - Click "Select Kernel" in top-right
   - Choose "Python (PySpark latest)" or your virtual environment

2. **Run Setup Cells**
   - Execute the `JAVA_HOME` configuration cell
   - Import required libraries

3. **Follow Along**
   - Read explanations
   - Run code cells in order
   - Complete exercises

4. **Experiment**
   - Modify code examples
   - Try different parameters
   - Create your own queries

## 📖 Notebook Structure

### 0. Getting Started
- System requirements
- Kernel selection
- Environment setup

### 1. Introduction to PySpark
- What is PySpark?
- SparkSession creation
- `getOrCreate()` behavior

### 2. Creating DataFrames
- From Python lists
- From Pandas DataFrames
- Reading CSV files

### 3. Basic DataFrame Operations
- Display operations: `show()`, `printSchema()`
- Filtering and selecting
- Column transformations

### 4. Class Activity
- 📊 Practice dataset (7 employees)
- 📝 12+ hands-on exercises
- ✅ Complete solutions with explanations

### 5. Summary
- Operations reference
- Key concepts
- Next steps

## 🎓 Learning Outcomes

After completing this notebook, you will be able to:

✅ Create and configure a SparkSession  
✅ Create DataFrames from multiple sources  
✅ Perform data filtering and selection  
✅ Transform data (add, rename, drop columns)  
✅ Execute aggregation operations  
✅ Use `groupBy()` for grouped aggregations  
✅ Combine filters with aggregations  
✅ Apply method chaining for complex queries  
✅ Understand DataFrame immutability  
✅ Use `.alias()` for readable column names  

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- Add more exercises
- Translate to other languages
- Create video tutorials
- Fix typos or improve explanations
- Add advanced topics (joins, window functions, UDFs)

## 🙏 Acknowledgments

**Original Source:** Professor Dr. Ali Safari  
**Modified by:** Benjamin Gao

Enhanced with:
- Detailed explanations and analogies
- Collapsible Markdown structure
- Hands-on exercises
- Real-world examples
- Complete solutions

## 💖 Support This Work

If you find this tutorial helpful, consider:

- ⭐ **Starring the repository**
- 🍴 **Forking and sharing**
- ☕ **Buying me a coffee**

### Donation Methods

**💳 Fiat Currency:**
- **Alipay/支付宝:** `g103200@gmail.com`
- **Wise:** `g103200@gmail.com`
- **PayPal:** [paypal.me/gbenjamin3](https://paypal.me/gbenjamin3)

**₿ Cryptocurrency:**
- **ETH (ERC20):** `0x05bd3070993c1ef72b1ca3a06999cbcc3f61ad8b`
- **USDT (ERC20):** `0x0a4649d6cbabf9bcf0419ac829f22a273136af51`
- **SOL (Solana):** `3bsEtgBPeNwMrHLzQBrxiQ7wX1nr3dSRrzVAHoa1nudQ`
- **BTC (Bitcoin):** `bc1ql0pafavp4l0l7j9m6dhgqajces3a80zqdj2kp8nua3aw4hqsm6vsnucv2m`

*Every contribution, no matter how small, is greatly appreciated!* ✨

## 📞 Contact

- **Email:** g103200@gmail.com
- **GitHub:** [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📚 Additional Resources

### Official Documentation
- [PySpark API Documentation](https://spark.apache.org/docs/latest/api/python/)
- [Spark SQL Programming Guide](https://spark.apache.org/docs/latest/sql-programming-guide.html)
- [Apache Spark Official Site](https://spark.apache.org/)

### Learning Resources
- [Databricks Learning Academy](https://www.databricks.com/learn/training/home)
- [Stack Overflow - PySpark](https://stackoverflow.com/questions/tagged/pyspark)
- [PySpark Cookbook](https://runawayhorse001.github.io/LearningApacheSpark/)

### Next Steps
1. **Advanced PySpark**
   - Window functions
   - User-defined functions (UDFs)
   - Join operations
   
2. **Performance Optimization**
   - Partitioning strategies
   - Caching and persistence
   - Broadcast variables

3. **Real Projects**
   - Log analysis
   - ETL pipelines
   - Machine learning with MLlib

---

**Made with ❤️ for the data science community**

**Happy Spark Learning! 🚀**
