# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|Lê Hồng Cát|21110249|
    |2|Phạm Ngô Ngọc Diệp|21110058|
    |3|Nguyễn Minh Hùng|21110301|
    |4|Trương Quốc Trung|21110427|

- The submission deadline is strict: **11:59 PM** on **June 22nd, 2024**. Commits pushed after this deadline will not be considered.

## 📦 Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## ⚙️ Usage

This project is designed to be completed in the following steps:

1. **Fork the Project**: Click on the ```Fork``` button on the top right corner of this repository, this will create a copy of the repository in your own GitHub account. Complete the table at the top by entering your team member names.

2. **Download the Dataset**: Download the facial expression dataset from the following [link](https://mega.nz/file/foM2wDaa#GPGyspdUB2WV-fATL-ZvYj3i4FqgbVKyct413gxg3rE) and place it in the **/data** directory:

3. **Complete the Tasks**: Open the ```notebooks/EDA.ipynb``` notebook in your Jupyter Notebook environment. The notebook is designed to guide you through various tasks, including:
    
    1. Prerequisite
    2. Principle Component Analysis
    3. Image Classification
    4. Evaluating Classification Performance 

    Make sure to run all the code cells in the ```EDA.ipynb``` notebook and ensure they produce output before committing and pushing your changes.

5. **Commit and Push Your Changes**: Once you've completed the tasks outlined in the notebook, commit your changes to your local repository and push them to your forked repository on GitHub.

Feel free to modify and extend the notebook to explore further aspects of the data and experiment with different algorithms. Good luck.

## Project Answer

Ở Project này, vì hạn chế trong việc chạy GridSearchCV, training Model trực tiếp trên máy cá nhân và giới hạn thời gian của GoogleColab cũng như các ứng dụng có thể sử dụng Notebook khác; nhóm em sẽ thực hiện từng bước một cho từng Model (SVM - RandomForest - KNN - MLP) ở trên từng file Notebook khác nhau với tên file là tên Model tương ứng.

Sau đó, các kết quả thu được ở các file này sẽ được nhóm em Merge (bằng thư viện nbmerge của Python lại với nhau với file EDA.ipynb để trả lời các question trong EDA.ipynb. Do đó, file EDA.ipynb nhóm em sẽ là file tổng hợp các kết quả ở từng question. Nếu yêu cầu sự chi tiết về từng Model sẽ có file .ipynb tương ứng của Model đó về việc nhóm em đã triển khai Model đó như thế nào để có được các Hyperparameter cũng như là các kết quả khác theo yêu cầu của question.

Cuối cùng, sau khi thực hiện Mini Project này nhóm em kết luận như sau: Mô hình SVM là mô hình tốt nhất trong số các mô hình được xem xét. Nó cung cấp hiệu suất cao nhất trong các chỉ số quan trọng như precision, precision, recall và F1 - Score. Do đó, nếu phải lựa chọn một mô hình để triển khai, SVM sẽ là lựa chọn ưu tiên.

