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
2. Deploy the component to your Salesforce org using Salesforce CLI, Salesforce Extensions for Visual Studio Code, or Metadata API.
3. Add the Lightning web component to your Lightning pages, record pages, or app pages as per your requirements.
4. Ensure proper API access and permissions for file uploads and processing.

## Usage Scenario
The Image to PDF Converter Lightning Web Component is ideal for scenarios where users need to upload multiple images and convert them into a PDF file for documentation, presentation, or archival purposes. It enhances productivity and data management efficiency within Salesforce applications.


# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
