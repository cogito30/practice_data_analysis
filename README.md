# Practice DataAnalysis

## Concept
- data preprocessing
- data visualization
- statistic

## Environment
- miniconda
- python 3.12
- pandas
- matplotlib + seaborn + plotly

## How to Setting Environment
- install miniconda && check version
```bash
brew install miniconda
conda --version
```
- updata conda
```bash
conda update --all
```
- check virtual env list
```bash
conda info --envs
conda env list
```
- check available python list
```bash
conda search python
```
- create virtual environment
```bash
conda create -n "virtual_name" python=[version]
conda create --name "new_virtual_name" --clone "virtual_name"
```
- remove virtual environment
```bash
conda remove --name "virtual_name" --all
conda env remove -n "virtual_name"
```
- check env info && install package
```bash
conda info
conda list
```
- active/deactive virtual environment
```bash
conda active "virtual_name"
conda deactive
```
- install/uninstall package
```bash
conda install [package]
conda uninstall [package]
```

- install/uninstall python package
```bash
pip install [package] --force-reinstall
pip install [package] --upgrade
pip install -r [requirements.txt]
pip uninstall [package]
```

## Reference
#### GUI
- [Tkinter](https://docs.python.org/3/library/tkinter.html)
- [PyQt6](https://www.riverbankcomputing.com/software/pyqt/)
- [Jupyter](https://jupyter.org/)
#### Data Processing && Visualization
- [Data Science School](https://datascienceschool.net/intro.html)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [scikit-learn](https://scikit-learn.org/stable/)
#### Data Source
- [Kaggle](https://www.kaggle.com/competitions)
- [DACON](https://dacon.io/)
- [AI-Hub](https://aihub.or.kr/)
- [공공데이터포털](https://www.data.go.kr/)
- [KOSIS 국가통계포털](https://kosis.kr/index/index.do)
- [SDC 통계데이터센트](https://data.kostat.go.kr/sbchome/intro.do)
- [K-ICT 빅데이터센터](https://kbig.kr/portal/kbig/datacube/info.page)
- [공공데이터포털 & 데이터 사이트](https://www.finereport.com/kr/%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%B6%84%EC%84%9D%EC%97%90-%ED%95%84%EC%9A%94%ED%95%9C-%EC%98%A4%ED%94%88-%EA%B3%B5%EA%B3%B5%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%86%8C%EC%8A%A4-%ED%8F%AC%ED%84%B8-20%EA%B0%80/)