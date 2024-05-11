# GetCodeAsPdf

x64 quick and easy way to compile code into PDF.

Put the *.exe in your path and (optionally) make it post-build 
in Visual Studio, and you have a quick and easy way 
to feed your code into a GPT
or any LLM with a large enough context window...
# GetCodeAsPdf

## Overview
`GetCodeAsPdf` is a C# console application that generates a PDF document containing the source code of a given project. The application scans the current directory for code files (including `.cs`, `.cshtml`, `.js`, `.css`, `.csproj`, `.json`, `.py`), and formats them into a structured PDF with a table of contents and organized sections.

## Features
- **Dynamic File Scanning**: Automatically detects and processes multiple file types within the project directory.
- **Content Filtering**: Excludes files from specified directories and checks content suitability for PDF conversion.
- **PDF Formatting**: Utilizes custom styles for PDF content, including font settings and section headings.

## Prerequisites
Ensure you have the following installed:
- .NET 7.0 SDK

## Installation
1. Clone the repository to your local machine.
2. Navigate to the project directory.

## Usage
To run the application, execute the following command from the root of the project directory:
```bash
dotnet run
