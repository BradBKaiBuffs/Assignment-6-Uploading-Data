# Assignment 6: Uploading Data

## Tasks completed:
- Create a form that takes a file upload where that upload can be used to import data into the database
- Create a Django admin customization that takes a file upload where that upload can be used to import data into the database

## Details:
### How the upload process is set up
- User uploads a csv file and submits
- File will be saved in the upload directory folder for the project
- File will be read and imports information into database. The code is set up to import information for the Course table.

### Site admin upload page
- Site url is 127.0.0.1:8000/admin/admin_upload
- Admin username is "admin" and the password is "Checklist1!".

### User view upload page
- Site url is 127.0.0.1:8000/upload/
