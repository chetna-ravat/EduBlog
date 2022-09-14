# Blog_Website

## Description

Blog_website is a full featured web application build using django framework and python. It is beautified using HTML, CSS and bootstrap 4.

## Features

- Allows user to create an account.
- Allows user to create/ update/ delete a post.
- Allows user to filer posts based on an author.
- Pagination: Displaying 5 posts per page for better user experience.


## Dependencies

All the dependencies required to run this project are available in the [requirements.txt](https://github.com/chetna-ravat/Blog_Website/blob/main/requirements.txt) file.

## How to run the project

#### 1. Create virtual environment
```shell
python3.7 -m venv env
```

#### 2. Activate virtual environment
```shell
source env/bin/activate
```

#### 3. Install required python dependencies from requirements file
```shell
pip install -r requirements.txt
```

#### 4. Run the project
```shell
python3 manage.py runserver
```
#### 5. The project would run on loaclhost on the web browser
http://localhost:8000