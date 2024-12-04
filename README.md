STEP 1: INSTALL THE REQUIRED DEPENDENCIES 
Before running the project, ensure all the necessary libraries are 
installed. 
Core Libraries 
 os: For directory and file management. 
 time: For time-based operations and introducing delays. 
 pickle: For saving/loading trained models. 
 sqlite3: For database management (if required for advanced 
storage). 
Machine Learning and Natural Language Processing 
 transformers: For the sentiment analysis model pipeline. 
 torch: For GPU-accelerated computations (PyTorch backend). 
 scikit-learn: For potential preprocessing or additional ML tasks. 
Data Handling and Visualization 
 pandas: For handling and processing datasets. 
 numpy: For numerical computations. 
 tqdm: For progress bars during long-running tasks. 
STEP 2: CHECK SYSTEM REQUIREMENTS 
 Hardware: 
A modern computer with sufficient RAM and CPU/GPU for 
running the sentiment analysis pipeline. 
 Operation System: 
Windows, macOS, or Linux. 
 Additional Tools: 
 An IDE or code editor (e.g., VS Code, PyCharm). 
 A terminal or command prompt to run Python script 
 A web browser for accessing processed results  
STEP 3: CONFIGURE THE PROJECT 
1. Dataset Directory: 
 Place the review dataset (e.g., Reviews.csv) in the data 
folder of the project. 
 Ensure the dataset has at least two columns: Id (unique 
identifier) and Text (review content). 
2. Output Directory: 
 Ensure a directory named output exists for storing the 
processed results (e.g., processed_reviews.csv). 
3. Model Configuration: 
 The script will use the pre-trained Hugging Face model: 
distilbert-base-uncased-finetuned-sst-2-english.No 
additional setup is required for the model. 
STEP 4: RUN THE APPLICATION 
1. Open a terminal and navigate to the project folder: 
cd path/to/project-folder 
2. Execute the sentiment processor script: 
python SentimentProcessor.py 
3. The script will process the dataset and save the results (including 
sentiment labels and confidence scores) to output/processed_reviews.csv. 
STEP 5: USE THE APPLICATION 
Dataset Sentiment Analysis 
1. Ensure the Reviews.csv dataset is correctly placed in the data folder. 
2. Run the script to analyse sentiments. 
3. Access the output in output/processed_reviews.csv, which will include: 
o Original review text. 
o Predicted sentiment (positive/negative). 
o Confidence score for each prediction.
