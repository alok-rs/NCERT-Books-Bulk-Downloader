# NCERT Books Bulk Downloader

A bash script to download all NCERT books in bulk. 

## Features

- Generate direct URLs to NCERT Books.
- Edit sources of NCERT Books.
- Bulk download all text books for all classes on official NCERT website.

## Usage

### On Windows
First, you will need to install Git Bash and then place the 'wget' executable in the 'bin' folder of 'mingw64'.

- Install Git from Scoop or download from the official site - https://gitforwindows.org/
- Download the 'wget' executable from here - https://eternallybored.org/misc/wget/ (Make sure you download the 'EXE' file for your platform (eg: x64).
- Copy the downloaded wget executable (wget.exe) to "C:\Users\<username>\scoop\apps\git\current\mingw64\bin" if Git was downloaded through Scoop or "C:\Program Files\Git\mingw64\bin" in case you downloaded from the official site.
- Download and Extract this repository from here (i.e., green color "< > Code" button above and then "Download ZIP".
- Run the newly installed software "Git Bash" and go to the folder where your new downloaded and extracted file "downloadBooks.sh" is placed.
- Run the following command:
```sh
./downloadBooks.sh
```
The downloads will be processed in order of the sources and the bandwidth allotted by the official server.

### On GNU/Linux

- Open terminal
- git clone https://github.com/alok-rs/NCERT-Books-Bulk-Downloader.git
- cd NCERTBooks-Books-Bulk-Downloader
- chmod +x downloadBooks.sh
- Run the following command:
```sh
./downloadBooks.sh
```

## Frequently Asked Questions

- **Some books are missing**

  The sources were updated on June 2024. For regenerating a new source file, you will need to edit the "source.js" pointing to the latest categories of each textbooks for each class listed within this file.
  
- **Is it allowed?**

  Yes. The download of books are being processed through official NCERT sources only. However, you are restricted from hosting these books yourself and redistributing them in any form whatsoever as per NCERT.nic.in
  
- **Why should I download in bulk?**

  You are free to edit the sources file ("source.js") or simply delete the categories you do not want from "urls.txt", and re-run the bash file as demonstrated above.
  
- **What can I do with these books?**

  As per NCERT, you are free to help these textbooks reach to children, teachers and schools. Please be advised that these textbooks are copyrighted and any form of infringement or violation of copyright is strictly prohibited.
  
- **How do I combine all chapters for each textbooks**

  NCERT has published chapter-wise ".pdf" files for each textbook, there are python scripts and software that exist which can help you combine them for ease of use.
  
### Credit

This Git is recent fork of the repository created by 'mayankbhagya' - https://github.com/mayankbhagya/NCERTBooks


