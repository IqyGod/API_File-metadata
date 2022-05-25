# API_File-metadata
File metadata is not the actual file, the document or photo itself, it’s information _about_ it — like the file’s name, file size, or creation date.

## 01 - .multer() : 
<br>Use multer npm package to handle file uploading
<br>Multer is a node.js middleware for handling 'multipart/form-data', which is primarily used for uploading files.

## 02 - multer().single('upfile') : 
<br>.single() = > Accept a single file with the name fieldname. The single file will be stored in req.file.
<br>'upfile' comes from index.html => the form file input field has the name attribute set to **upfile**

## 03 - In order to make sure response has correct name elements, a console.log() can simply help to avoid this.
![image](https://user-images.githubusercontent.com/99662300/170236408-ef6524da-ef7f-4286-b2b1-61cce893fc1a.png)
<br>![image](https://user-images.githubusercontent.com/99662300/170236783-edf5a366-49d4-4936-8f9d-d6d033d5ae72.png)
<br>Pick required elements and when user submits a file, the file name/ type/ size in bytes within the JSON response will be received.


## User interface
Live link : https://project-filemetadata.godherea.repl.co
![image](https://user-images.githubusercontent.com/99662300/170234464-e37ba240-42a2-4939-967b-a0cb6a3804b5.png)
