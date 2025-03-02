<h2>Overview</h2>
<p>This project automates receipt processing using AWS Textract and Step Functions, with a focus on comparing different machine learning models for data extraction. The repository includes Jupyter notebooks demonstrating:</p>
<ul>
    <li>Uploading receipts and processing them using AWS Textract</li>
    <li>Implementing AWS Step Functions to orchestrate the workflow</li>
    <li>Comparing multiple machine learning models for improved accuracy</li>
</ul>

<h2>Repository Contents</h2>

<h3>1. UploadReceiptsSaveTextract.ipynb</h3>
<p>This notebook handles:</p>
<ul>
    <li>Uploading receipt images to an S3 bucket</li>
    <li>Extracting text from receipts using AWS Textract</li>
    <li>Saving the extracted data in a structured format for further processing</li>
</ul>

<h3>2. ModelComparison.ipynb</h3>
<p>This notebook focuses on:</p>
<ul>
    <li>Comparing different machine learning models for receipt data classification</li>
    <li>Evaluating model performance using accuracy metrics</li>
    <li>Visualizing model results</li>
</ul>

<h3>3. StepFunctionDescription.ipynb</h3>
<p>This notebook explains:</p>
<ul>
    <li>The design and implementation of AWS Step Functions as a pipeline to process data</li>
    <li>The state transitions involved in processing receipts</li>
    <li>How extracted data is stored and analyzed</li>
</ul>

<h2>Key Highlights</h2>
<ul>
    <li>Integration of AWS Textract for automated text extraction from receipts</li>
    <li>Use of AWS Step Functions to manage and orchestrate workflows</li>
    <li>Application of machine learning techniques to classify and analyze extracted data</li>
    <li>Python-driven implementation with structured, reusable Jupyter Notebook workflows</li>
    <li>Data visualization techniques to compare and evaluate model performance</li>
</ul>
