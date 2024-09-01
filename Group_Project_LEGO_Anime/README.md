
# LEGO - Anime

## Project Description

This project aims to create a data visualization tool that suggests the creation of LEGO sets inspired by Japanese anime stories and characters. The goal is to combine Big Data Analytics and Data Visualization to identify trends and creative ideas that can be used to design new themed LEGO sets.

## Group members
- [Simone Caglio](mailto:s.caglio1@campus.unimib.it)
- [Marco Manduca](mailto:m.manduca@campus.unimib.it)
- [Corona Rosas Torres](mailto:c.rosastorres@campus.unimib.it)

## Project Structure
- Notebook: folder with Jupyter notebooks used for the ETL phase
- PDF: folder with project related documents
  - [Laboratory requirements](./PDF)
  - [Project proposal](./PDF/Proposal_Caglio_Manduca_Rosas.pdf)
  - [Keynote project presentation](./PDF)

## Tech Spec
### Language
-  [Python 3.11.5](https://www.python.org/downloads/release/python-3115/)
### Frameworks and Libraries
-  This project uses several libraries for data analysis, visualization, and database management, such as `numpy`, `pandas`, `matplotlib`, `seaborn`, `pymongo`, and more. (See [requirements.txt](./requirements.txt) for the full list of dependencies.)
### Prerequisites
-  **Python:** Make sure you have Python 3.11.5 or a compatible version installed.
-  **Package Manager:** You will need `pip` or `conda` to install the dependencies.
### Installation Steps
1.  **Clone the repository:**

```bash
git  clone  https://github.com/your-username/lego-anime.git
cd  lego-anime
```
2.  **Create a virtual environment (optional but recommended):**
- Using venv:
```bash
python3  -m  venv  venv
source  venv/bin/activate  # On Windows: venv\Scripts\activate
```
- Using conda:
```bash
conda  create  --name  lego-anime  python=3.11.5
conda  activate  lego-anime
```
3.  **Install the dependencies:**
- With pip:
```bash
pip  install  -r  requirements.txt
```
- With conda:
```bash
conda  install  --file  requirements.txt
```

## Usage
Once all dependencies are installed, you can start exploring and visualizing data. Open the project in a Jupyter notebook by running:
```bash
jupyter  notebook
```
## Analyse Data
Explore the provided examples and datasets to begin creating interactive visualizations. The main goal is to discover trends and generate suggestions for new LEGO sets inspired by popular Japanese anime.
You can find the output Dashboard on Marco's [Tableau Public](https://public.tableau.com/app/profile/marco.manduca/viz/LEGO-Anime), enjoy.
## License
This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more details.
