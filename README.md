# Image to PDF Converter Lightning Web Component

## Overview

The Image to PDF Converter Lightning Web Component is a Salesforce application component that facilitates the conversion of multiple image files (PNG or JPEG) into a single PDF document. This component is designed to streamline the process of uploading, processing, and linking files to records within the Salesforce platform.

## Key Features

- File Upload: Users can upload multiple image files using the file uploader input field.
- Image-to-PDF Conversion: Uploaded images are processed and converted into a PDF document.
- Cancel File: Users can cancel the upload of individual files by clicking the cancel button next to each selected file.
- Dynamic File Naming: The file name input field updates dynamically based on selected files, ensuring accurate naming even after file cancellation.
- File Size Limit: The component enforces a maximum limit to prevent uploads exceeding a specified threshold.
- Error Handling: Error messages are displayed using toast notifications in case of file size exceedance or other upload errors.
- API Integration: The component integrates with Salesforce Apex methods for saving files, handling chunks, and linking uploaded files to records.

## Installation
To use this Lightning web component in your Salesforce environment, follow these steps:

1. Clone or download the repository to your local machine.
2. Before deploying any code into a Salesforce org, it is recommended to create static resource files. 
3. Deploy the component to your Salesforce org using Salesforce CLI, Salesforce Extensions for Visual Studio Code, or Metadata API.
4. Add the Lightning web component to your Lightning pages, record pages, or app pages as per your requirements.
5. Ensure proper API access and permissions for file uploads and processing.

## Usage Scenario
The Image to PDF Converter Lightning Web Component is ideal for scenarios where users need to upload multiple images and convert them into a PDF file for documentation, presentation, or archival purposes. It enhances productivity and data management efficiency within Salesforce applications.

![Screenshot 2024-04-09 153933](https://github.com/vetriCR/PDFConvertor/assets/147226269/24c1ac52-30ad-4d6c-99b7-eaf9cabdd159)

- Click on the "Upload Files" button or drag and drop image files into the file uploader input field.
- You can select multiple images to be converted into a single PDF document.
- If you want to remove any selected file before conversion, click on the cancel button ('x' icon) next to that file.
- The file will be removed from the list, and the remaining files will automatically adjust their order.
- Once you have selected the desired files and configured the file name, click on the "Upload" button.

![Screenshot 2024-04-09 163740](https://github.com/vetriCR/PDFConvertor/assets/147226269/3ed05278-1b97-48f0-9bea-02d9c2b848aa)

- Once the conversion is finished, the component will display a success message indicating that the file upload was successful.
- You can now view or download the converted PDF document in the related notes and attachment section.
