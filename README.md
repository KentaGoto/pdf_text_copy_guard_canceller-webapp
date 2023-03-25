# PDF Text Copy Guard Canceller Web App

This repository contains the source code for a web application and a command-line tool that removes the PDF text copy guard from PDF files.

## Features

Web application that allows users to upload a ZIP file containing PDF files to remove the text copy guard.
A Go command-line tool that processes PDF files in a specified directory to remove the text copy guard.
Note that not all text copy guards can be guaranteed to be removed successfully.

## Web Application

The web application is implemented using PHP and JavaScript. It enables users to upload a ZIP file containing PDF files, processes the files to remove the text copy guard, and provides a download link to the resulting ZIP file containing the processed PDF files.

### Requirements
- PHP 7.0 or higher
- Web server (e.g., Apache, Nginx) with PHP support

### Usage
Copy the provided PHP code into a file named index.php and place it in a directory served by your web server.
Access the web application by navigating to the corresponding URL in your web browser.
Command-Line Tool

## The command-line tool is implemented in Go and removes the PDF text copy guard from all PDF files in a specified directory.

### Requirements
- Go 1.16 or higher
- Windows operating system
- qpdf
- 7zip

### Usage
Copy the provided Go code into a file named main.go.
Compile the Go code using the command go build -o pdf_text_copy_guard_canceller.exe main.go.
Run the compiled executable with the directory containing the PDF files as an argument: pdf_text_copy_guard_canceller.exe <DIRECTORY>.

### License
MIT

### Author
Kenta Goto
