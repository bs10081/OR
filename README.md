# Gurobi for Operations Research in Jupyter Notebook

[Mandarin(Taiwan)](README_zh-tw.md)

This repository contains Jupyter Notebook examples and teaching materials for solving linear programming problems using Gurobi. These Notebook examples come from different course chapters and are designed to help learners gain a deeper understanding of how to use Gurobi to solve various optimization problems, including linear programming (LP) and mixed-integer programming (MIP).

## Content Introduction

This repository currently includes the following chapter contents (all have a Mandarin (Taiwan) version):

### Chapter List

1. **Chap3 - Wyndor Glass Co. Using Gurobi for Linear Programming Problems**

- Notebook: `Chap3/wyndor_glass_co_uses_gurobi_for_linear_programming_problems.ipynb`

- Content: Introduces how to apply Gurobi to solve the classic Wyndor Glass Company linear programming problem.

2. **Chap3 - Radiation Therapy Optimization Problem**

- Notebook: `Chap3/Radiation Therapy Treatment Optimization using Gurobi.ipynb`

- Content: Simulates optimization problems in radiation therapy, aiming to minimize the impact on healthy tissues while ensuring sufficient radiation to the tumor site.

## How to Use

1. **Clone this repository**

```bash
git clone https://github.com/bs10081/OR.git
```

2. **Install necessary Python packages**

- Gurobi Solver: If Gurobi is not yet installed, please follow the instructions on the [official website](https://www.gurobi.com) for installation.

- Other dependency packages can be installed from the `requirements.txt` file listed dependencies:

```bash
pip install -r requirements.txt
```

3. **Run the Notebook**

Navigate to the Notebook directory in the command line and start Jupyter Notebook:

```bash
jupyter notebook
```

Then select the corresponding Notebook for learning and operation.

## Future Updates

This repository will periodically add more chapters and examples to cover a wider range of optimization problem applications. Each new chapter will have a corresponding Jupyter Notebook file, explaining its application context and implementation steps.

Potential future updates may include:

- More examples of linear programming and mixed-integer programming in practical applications

- Using Gurobi to solve large optimization problems

- Comparisons and applications of other optimization algorithms

## Contribution Guidelines

If you would like to contribute to this repository, feel free to submit a pull request. Please fork this project first and ensure that all Notebooks run correctly before submitting.

## Related Resources

- [Gurobi Official Documentation](https://www.gurobi.com/documentation/)

- [Jupyter Notebook Official Documentation](https://jupyter.org/documentation)

## License

The content of this repository follows the [MIT License](LICENSE).
