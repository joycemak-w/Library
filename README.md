# Library System
![download](https://github.com/user-attachments/assets/aea72140-8bf5-4771-ab7a-66a9879181e0)
### A simple library management system built using Python and the Tkinter GUI library. This system allows users to perform the following operations:

## Database Structure
![Library System](https://github.com/user-attachments/assets/a045727e-4849-406c-922b-69aa7adaef34)

## Functions
- View list of members
  ```py
  def view_member_list():
    # get all members data from `Members` and no. of borrowed book per member from `Borrowing_Records` save as dataframe
    # show dataframe in textarea
  ```
- View list of books
  ```py
  def view_book_list():
    # get all book data from `Books` and if book is borrowed `is_returned` from `Borrowing_Records` save as dataframe
    # show dataframe in textarea
  ```
- Borrow a book
  ```py
  def borrow_book():
    #  get `member_id` and `book_id` by inputing in GUI
    #  Args: 1. With existing `member_id` and `book_id` in `Members` and `Books` respectively
    #        2. no. of borrow books of that member <= 2
      #  add borrow record to `Borrowing_Records` with `member_id`, `book_id`
  ```
- Return a book
- Add a new member
- Add a new book
- Delete a member
- Delete a book
- Save personal record as CSV

## Requirements
- Python 3.x
- sqlite
- Tkinter library (usually comes pre-installed with Python)

## Installation
- Clone the repository or download the source code.
- Navigate to the project directory in your terminal or command prompt.
- Run the following command to start the application:
```
python library_github_project.py
```
## Preview
<img alt="image" src="https://github.com/user-attachments/assets/ab996956-e3a2-43d5-b54c-ed5ba095ddac">
