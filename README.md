# UTS Deep Learning

## Identity

Name: Austin Kane\
NIM: 2702229232

## Task

1. Artificial Neural Network for Scoring Team Productivity on a Garment Producer
2. Convolutional Neural Network for Osteoarthritis Classification
3. Deep Learning Model Comprehension
   1. YOLO vs RCNN
   2. EfficientNet Method

## Final Video

1. [Video1_ANN]()
2. [Video2_CNN]()
3. [Video3_DLModel]()

## Download Guidelines

1. Terminal
   - git clone https://github.com/Tinnne/UTSDeepLearning
2. Anaconda Prompt
   - conda create -n <env_name> python=3.12
   - conda activate <env_name>
   - conda install pip
   - pip install -r requirements.txt

\*make sure that anaconda prompt is opened on the same folder where requirements.txt existed.\
\*another alternative is to copy requirements.txt to the folder where anaconda prompt is being opened

3. File Manager

   - Download the **dataset b** from Dataset: [Dataset B](https://drive.google.com/drive/folders/1pThuel6dU23CLRseKzymT4oNDUECq_c6)
   - Unzip the data
   - Copy the data into your folder according to the file structure below

4. Python Notebook
   - Select the conda environment you have created
   - Run the code

## File Structure

- Data
  - 01
    - dataset_1B.parquet
  - 02
    - test
      - Doubtful
      - Mild
      - Moderate
      - Normal
      - Severe
    - train
      - Doubtful
      - Mild
      - Moderate
      - Normal
      - Severe
- tuning
  - func_tuning
  - seq_tuning
- .gitignore
- Number1_ProductivityPrediction.ipynb
- Number2_OsteoarthritisClassification.ipynb
- Number3.ipynb
- Questions.pdf
- README.md
- requirements.txt
