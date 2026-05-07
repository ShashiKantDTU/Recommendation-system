# Recommendation System

Build and evaluate a recommendation system for the IBM Watson Studio article interactions dataset. The notebook covers exploratory analysis, rank-based recommendations, user-user collaborative filtering, content-based recommendations, and matrix factorization.

## Getting Started

Clone or download the repository and open the notebook in Jupyter or VS Code.

### Dependencies

- Python 3.10+
- Jupyter
- pandas
- numpy
- scikit-learn
- matplotlib
- nbconvert

### Installation

Create and activate a virtual environment, then install dependencies:

```
python -m venv .venv
.venv\Scripts\activate
python -m pip install -U pip
python -m pip install pandas numpy scikit-learn matplotlib jupyter nbconvert
```

## Running the Notebook

Open and run the notebook:

```
starter/Recommendations_with_IBM.ipynb
```

Run all cells from top to bottom so that all outputs and tests are captured.

## Testing

Tests are embedded in the notebook. Run the cells that call:

- `t.sol_1_test(sol_1_dict)`
- `t.sol_2_test(get_top_articles)`
- `t.sol_5_test(sol_5_dict)`
- Additional `assert` cells in Parts III–V

## Export to HTML

From the project root:

```
python -m nbconvert starter/Recommendations_with_IBM.ipynb --to html
```

The HTML file will be created at `starter/Recommendations_with_IBM.html`.

## Project Deliverables

- Completed notebook with all outputs visible
- HTML export of the notebook

## Built With

- Python
- Jupyter
- pandas
- numpy
- scikit-learn
- matplotlib

## License

[License](LICENSE.txt)
