# extract-data_from_form
Extracting data from a form in Azure AI, specifically using Microsoft's Azure Form Recognizer, involves these key steps:

Form Recognizer Overview: Azure Form Recognizer is an AI service designed to analyze documents like forms, invoices, and receipts. It automatically extracts key-value pairs, tables, and other information from the submitted forms. It can handle structured, semi-structured, and unstructured documents.

Models for Extraction: There are two main types of models you can use:

Prebuilt models: For common document types (e.g., invoices, receipts, identity documents).

Custom models: You can train a custom model specific to the layout and structure of your form if it's unique.

Submitting Forms: You submit the form (in formats like PDF, JPG, or PNG) to the Form Recognizer API. The API processes the document and returns the extracted data.

Extracted Data: The API outputs the form data in a structured format like JSON, which includes:

Key-value pairs (e.g., labels and corresponding inputs)
Tables and line items
Checkboxes and selections
Signature fields, dates, and other specific information
Using the Data: Once the data is extracted, you can use it for further processing, like populating a database, integrating into business workflows, or performing analytics on the captured information.

Azure Form Recognizer is a powerful tool if you're dealing with large volumes of forms, making the data extraction process automated and scalable.
