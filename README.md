# Datasets Used:

1. CSection; PDHS’17-18 and ’12-13 (C-section) & Household information, contraceptive knowledge and practice, post-delivery, Children’s health care, Nutrition and migration patterns & 26284X24
2. Diabetic retinopathy & Features extracted from the Messidor images & 1151X19 & Binary
3. Breast Cancer; & Breast cancer & Characteristics of the cell nuclei present in the image & 569X30 & Binary
4. Diabetic early detection; & ESDRPD & age, gender and other features collected from patients via questionnaires & 520X16


# File Information:

1. To view the outputs only (i.e., graphs and rule), i.e., no XAI metrics involved, please see
    a- \<datasetname\>-OutputsOnly.pynb , a quick XAI methods as in output only version. This can run on Colab (and is not CPU intensive).
2. To run experiments with XAI metrics (such as Fideility, Simplicity, etc), run the following:
    a- \<datasetname\>-Main.pynb , contains all XAI methods except Anchors. Anchors is CPU intensive and takes more RAM, therefore it is separately recorded.
    b- \<datasetname\>_Anchors.pynb , contains Anchors along with XAI metrics applicable to it. CPU and RAM heavy.
3. Among datasets, the lightest one to run, is ESDRPD (as it has least number of rows, i.e., 520 X 16), following Breast Cancer (569 X 30), Diabetic retinopathy (1,151 X 19) and CSection (26284 X 24)
