Problem Statement

 

The goal of this assignment is to leverage the capabilities of Large Language Models (LLMs) to develop data structurizer tool which is capable of extracting specific, relevant information from a variety of unstructured documents, including invoices, receipts, bills, medical prescriptions, and general documents.

 

The extracted data should be organized into a structured DataFrame format, providing a clean and usable dataset for further analysis or applications.

 

Attached is the sample input pdfs and img files

 

Expected Output

Working Notebook in any of the platform using python
The final output should be a well-structured DataFrame containing the extracted data.
Each DataFrame should represent a single document, and each column should correspond to a specific data element (e.g., invoice number, date, total amount, item descriptions).
 

Additional Considerations

Document Format: Consider the variety of document formats you'll be dealing with (e.g., PDF, Word, images) and choose appropriate tools or techniques for each.
Prompt Engineering: Craft effective prompts to guide the LLM in extracting the desired information.
Model Selection: Choose an LLM that is suitable for the task and the available resources.
 

Evaluation Criteria:

Data Quality and Accuracy:
Completeness: Were all relevant data elements extracted from the documents?
Accuracy: Is the extracted data correct and consistent with the original documents?
Consistency: Are there any inconsistencies or contradictions within the extracted data?
Data Structurization:
Data Organization: Is the data organized in a clear and understandable manner within the DataFrame?
Data Quality: Are there any missing values, inconsistencies, or errors in the structured data?
LLM Usage:
Prompt Engineering: Were the prompts used to guide the LLM effective in extracting the desired information?
Model Selection: Was the chosen LLM appropriate for the task?
Fine-Tuning: Was the LLM effectively fine-tuned on a relevant dataset?
Code Quality:
Readability: Is the code well-structured, commented, and easy to understand?
Efficiency: Is the code efficient in terms of computational resources and execution time?
