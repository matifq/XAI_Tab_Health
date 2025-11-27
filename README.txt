Datasets Used:

1- CSection; PDHS’17-18 and ’12-13 (C-section) & Household information, contraceptive knowledge and practice, post delivery, Children’s health care, Nutritional information, and migration patterns & Yes & Public & 13.8\%: 86.2\% & 875X15,409 & Binary & \cite{islam2022hgsorf} 
2- Diabetic retinopathy & Features extracted from the Messidor images & No & Public  & 53\%:47\% & 19X1151 & Binary & \cite{hatwell2020ada}; https://archive.ics.uci.edu/dataset/329/diabetic+retinopathy+debrecen
3- Breast Cancer; & Breast cancer & Characteristics of the cell nuclei present in the image & No & Public (UCI) & 63\%:37\% & 30X569 & Binary & \cite{hatwell2020ada}
4- Diabetic early detection; & ESDRPD & age, gender and other features collected from patients via questionnaires & No & Public & 38.5\%:61.5\% & 16X520 & Binary & \cite{joseph2022explainable} https://data.mendeley.com/datasets/7zcc8v6hvp/1/files/a124de1f-0b55-479c-8b92-b1ea7e24413b


Files Information:

1- To view the outputs only (i.e., graphs and rule), i.e., no XAI metrics involved, please see <datasetname>-OutputsOnly.pynb. This can run on Colab, as it is not CPU-intensive.
2- To run experiments with XAI metrics (such as Fideility, Simplicity, etc), run the following:
    a- <datasetname>-Main.ipynb; contains all XAI methods except Anchors. Anchors is CPU-intensive and take more RAM; therefore, they are separately recorded.
    b- <datasetname>_Anchors.ipynb; contains Anchors along with XAI metrics applicable to it. CPU and RAM-heavy.
    c- <datasetname>_RF_Imp.ipynb; RF traditional feature importance.
3- Among datasets, the lightest one to run is ESDRPD (as it has the least number of rows, i.e., 16X520), followed by Breast Cancer (30 X 569), Diabetic retinopathy (19 X 1,151), and CSection (875 X 15,409)

For complete description and results:
    - See Results.txt for complete information.

