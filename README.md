# Library Management System
It is a simple Library Management System that provides members with a window to issue a book or return an issued book.
On login, member is directed to main window which has 2 options:
1. Book Issue
2. Book Return

Issue Window has 2 sub-windows:
1. one window has a list of all available books.
2. On selecting a book, another window on the right side opens. This window shows member and book details.
   Members are of  2 types: Student and Faculty
   Students can have up to 3 books issued to them at any point of time.
  Faculty can have up to 25 books issued to them at any point of time.
  Also, some books are not issueable.
  The date of issue will default to today.
  The window also displays the due date of the return.
  	for Students, the due date is the issue date + 10 days
  	For Faculty, the due date is the issue date + 90 days

Return Window:
On the return window, to fetch book details, member has to insert Issue code or Book code.
Based on input, the system displays the details.
Enter the actual return data and press submit.
On submission, Book status will change to available, and
decrease the number of books issued count for that member.
