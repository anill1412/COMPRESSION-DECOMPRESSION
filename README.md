File Compression and Decompression App

Overview:

This application allows users to compress and decompress files using the zlib library in a user-friendly interface. It leverages the power of browser-based file handling to enable efficient data storage and retrieval without needing a backend server.

Features:

File Compression: Users can select a file from their local system, and the application will compress it using the zlib library. The compressed file is then available for download in .zlib format.
File Decompression: Users can also upload a previously compressed .zlib file to decompress it back to its original form. The decompressed file can be downloaded in its original format, typically .txt or other text formats.

Technical Details:

Technologies Used: The app is built using React for the frontend, and the browserify-zlib library is utilized for file compression and decompression.
File Handling: The application uses the FileReader API to read files from the user's system and the Blob API to create downloadable files.

How to Use:
Compress a File:

Click on the "Choose File" button under the compression section.
Select the file you want to compress.
After compression, a link to download the compressed file will appear.

Decompress a File:

Click on the "Choose File" button under the decompression section.
Select the previously compressed .zlib file.
After decompression, a link to download the decompressed file will appear.
Installation:
1.git clone <repository-url>
2.cd <project-directory>
3.npm install
before "npm start " install the following:
      npm install stream-browserify
      npm install @emotion/react @emotion/styled
4.npm start



