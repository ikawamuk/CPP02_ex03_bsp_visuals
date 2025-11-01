# CPP03/ex03

## install
Execute following command.
```
git clone https://github.com/ikawamuk/CPP02_ex03_bsp_visuals.git CPP02_ex03_bsp_visuals && cd CPP02_ex03_bsp_visuals
mkdir -p .vscode
echo "{ \"python.defaultInterpreterPath\": \"$(pwd)/.venv/bin/python\" }" > .vscode/settings.json
python -m venv myenv && source myenv/bin/activate
pip install uv
~/.local/bin/uv pip install jupyterlab jupyter ipykernel notebook numpy pandas matplotlib ipywidgets
```

## How to use test code
You have output_bsp_test_csv.cpp file and test.ipynb file.
Pass the Point-type vertices of triangle ABC and the output CSV file’s ofstream to output_bsp_test_csv() in your main functioin.
And then, assign the path of the generated CSV file to the path variable in Jupyter Notebook.
Points determined to be inside the triangle will be plotted in blue, otherwise in red, on the scatter plot.
Feel free to modify the local variable N in output_bsp_test_csv() or edit the Jupyter Notebook as needed.
