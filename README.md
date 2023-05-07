# CSV_Upload -
CSV_Upload is a web application that allows users to upload and parse CSV files. The application is built with Node.js and Express, and it provides a simple and user-friendly interface for managing CSV data.

## Hosting Link -
https://csv-upload-9e5r.onrender.com

## Installation -
To install CSV_Upload, please follow these steps:

Clone this repository using the following command:
```
$ git clone https://github.com/mdadnan07/CSV-Upload
```
Install the required dependencies using the following command:
```
$ npm install 
```
Start the application using the following command:
```
$ npm start 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:7000 
```

## Screenshots -
![home](https://user-images.githubusercontent.com/131695481/236691491-c3707299-447d-4392-97aa-1cf4e9cca94a.PNG)
![upload-files](https://user-images.githubusercontent.com/131695481/236691514-245d5f58-38d4-4835-8eee-31edd31bf65d.PNG)
![view-file](https://user-images.githubusercontent.com/131695481/236691532-228dad28-0809-4ba9-a9b0-f4d4cce8b0c9.PNG)
![search-name](https://user-images.githubusercontent.com/131695481/236691542-ddd67502-8f19-40b4-9803-f0db902b524a.PNG)


## Features -
* CSV file upload: Users can upload CSV files with a simple web form.
* CSV parsing: The application parses the CSV data and displays it in a table.
* Searching: Users can search data in the table.

## API Reference -
CSV_Upload provides a simple API for uploading and parsing CSV files. The API supports the following endpoints:

* POST /upload: Uploads a CSV file and parses the data.
* GET /data: Returns the parsed CSV data as JSON.

## Folder Structure -
```
CSV_Upload/
|── |assets/
│   |      ├── css/
│   │      |     ├── styles.css
│   |      ├── js/
│   |            ├── script.js
│   ├── uploads/
│   ├── index.html
|   |
├── routes/
│   ├── csvRoutes.js
|   |
├── controllers/
│   ├── csvController.js
|   |
├── models/
│   ├── csvModel.js
|   |
├── .gitignore
├── package.json
├── README.md

```

