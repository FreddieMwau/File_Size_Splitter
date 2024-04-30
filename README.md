# 🤖 File Splitter Automation 📄✂️

## Overview

This UiPath automation solution splits large files (PDF, Excel, CSV) into smaller chunks based on specified criteria. It provides a flexible and efficient way to handle large datasets, and it can be converted into a reusable library for broader use cases.

## Features

- **Support for Multiple File Formats**: Split PDF, Excel, and CSV files effortlessly.
- **Flexible Splitting Criteria**: Specify the number of splits or maximum rows per split.
- **Automatic Handling of Remaining Rows**: Intelligently handle any remaining rows after splitting to ensure no data loss.
- **Efficient Resource Management**: Manage resources efficiently to handle large files without impacting system performance.
- **User-Friendly Interface**: Easily configure and execute the solution within UiPath Studio.

## Getting Started

### Prerequisites

- UiPath Studio installed on your machine.
- Access to the files you want to split.

### Installation

1. Clone or download the repository to your local machine.
2. Open the solution in UiPath Studio.

### Usage

1. Open the main workflow file in UiPath Studio.
2. Configure the splitting criteria (number of splits or rows per split) and file paths.
3. Run the workflow to split the files.
4. Review the output files in the specified output directory.

## Documentation

### Workflow Structure

The solution consists of the following main components:

- **Initialization**: Initialize variables and perform necessary setup steps.
- **Splitting Logic**: Split files based on specified criteria.
- **Handling Remaining Rows**: Process any remaining rows after splitting and add them to the last split file.
- **Finalization**: Release resources and finalize the workflow.

### Supported File Formats

- **PDF**: Split PDF files into smaller PDF files.
- **Excel**: Split Excel files into multiple Excel files.
- **CSV**: Split CSV files into multiple CSV files.

### Customization

Customize splitting criteria, output file naming, and other parameters by modifying workflow variables.

## Troubleshooting

Refer to UiPath Studio logs for any issues or errors during execution. Reach out to the development team for assistance if needed.

## Convert to Library

This sequence can be converted into a reusable library for broader use cases. Simply package it as a library and import it into other UiPath projects.
