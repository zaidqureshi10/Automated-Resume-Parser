# Automated-Resume-Parser
#Last Updated: 04 Dec 2021. Make sure you are using the updated version. 

Parse multiple resumes at once with ease. Also store the data in the database. Run the ARP.ipynb file.

This project will go through the resumes that are in pdf format, and convert them to individual text files first using the pdfminer library and store in a folder. Then it will extract only the info that we need using the Named Entity Recognition feature of Natural Language Processing offered by spaCy library and Pattern Matching using the (re) Regular Expression library to extract phone numbers and skillsets. Once the parsing is done only relevant information is left in a structured format, and with the help of pandas DataFrame, that can be saved in csv file type and also stored in a database. This final resulting file will contain all the extracted info in one place that can be easily accessed. After a successful run, an Excel file will open automatically.

#Install spaCy, its English Language Model and Pandas for this to work. Other libraries are built-in with python.

#You have to mention the particular skills you want to extract.

#Demo and code explanation video coming soon along with GUI, and executable file.
