

# Django based  Library Management by Tania

#### Tania Library Management is a web application built with Django, Razorpay, and Tailwind CSS that provides an online platform for managing libraries.
> 

## Features of this project:

##### Anyone can

1. see all the books in homepage
2. search books based on author or name of the book or category of the book
3. sort books or author alphabetically

##### Student can

1.  login / signup ,
2.  can request book
3.  see their own issues and filter them based on :

    - requested issues ,
    - issued books or
    - all of them together

4.  check their own fines
5.  can see

    - the days remaining to return a particular book
      **or**
    - the number of days passed the return date of a particular book in the my fines page

6.  Pay their fines online (powered by RazorPay)

##### Admin can

1.  login to admin dashboard
2.  check all issues :

    - see issues ,
    - delete issues ,
    - search issues by studentid
    - filter issues based on :

      - issued or not,
      - returned or not ,

3.  accept a issue :

    - from the dashboard where admin has to manually select return date
      **or**
    - from the Issue requests page where return date is automatically calculated

4.  add , delete search books and filter books based on author
5.  add , delete , search author
6.  calculate fine by clicking a button ,
7.  create, delete fine ,search fines for studentid
8.  toggle fine paid status (if paid in cash)
9.  search ,modify,add,delete students , filter them based on department and check all fines and issues of that student
10. can see the last-login , date joined & the student associated to a particular user
11. can change password for any user

## Installation 📦
### To install Tania Library Management, follow these steps:
## 1. Clone this repository:
>'https://github.com/BurhanMohammad/Django-librarymanagement.git'
## 2. Navigate to the project directory:

```bash
  cd Tania-librarymanagement
```
## 3 . Create a virtual environment:
```bash
  python3 -m venv env
```
## 4. Activate the virtual environment:
```bash
  source env/bin/activate
```
## 5. Install the project dependencies:
```bash
  pip install -r requirements.txt
```
## 6 . Run the server
```bash
  python manage.py runserver
```
## 7 . Go to localhost:8000
---


>'http://localhost:8000/'

## 2. Open your web browser and go to:

## 3 . Sign up for a new account or log in with an existing one.

## 4. Add some books to the library.

## 5. Borrow and return books as needed.

## 6 . Make online payment using Razorpay payment gateway.

##### More ...


1. while signing up if studentID is already associated to a user in this platform then it will show a error without reloading the page and as soon as correct id is given then the error will go away
2. Books in homepage will show status of `issued` , `issue requested` or `request issue` based on whether the book is issued or requested for a issue or is not requested for logged-in students only


## Contributing 💡

#### If you'd like to contribute to Django Library Management, feel free to fork this repository and submit a pull request. For more information on contributing to the project, please check out my repository.

#### Django Library Management was created by Thiam Franck with Tania contribution


## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
