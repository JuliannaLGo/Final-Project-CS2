📌 Project Proposal (Draft)

## 📝 Project Title  
Library Borrowing Records  

---

## 🔍 Problem Statement  
Problem: Digital world overtakes the world of reading 
- This problem is relevant and worth solving because nowadays, people are glued to their gadgets unlike the old days when all we had were books. Although you can learn something from the internet, too much exposure may damage your eyes, unlike books.
- This problem can relate to our data set, which is from a library, because we can track how many people are still reading books and possibly promote reading to others. 


---

## 🎯 Project Objectives  
Objective 1: To identify key patterns and trends within the given data, such as averages, correlations, etc, that will provide valuable insights to users and easy analysis.

Objective 2: To create an interactive tool that allows users to visualize the data in meaningful ways to facilitate decision-making, and to easily find what they need or what they're looking for.

Objective 3: To integrate user-friendly features such as search filters and custom queries, making it easier for users to extract specific insights based on their needs, as well as the data that matches their requirements.

---

## ⚙️ Planned Features  
1.) Show which books are still borrowed (not yet returned)
- Displays all books where return_date is null.

2.) Count how many books each borrower has checked out
- Counts total books borrowed (returned or not) per student.

3.) Show currently borrowed books per student
- Displays a student’s name and only the books they haven’t returned.

4.) Displays a student's full borrow history
- Shows the entire borrow history (including current borrows) of a student by inputting their borrower_id.

5.) Lists books by author
- Shows all books by a certain inputted author name. 

6.) Searches book by name




---

## ⌨️ Planned Inputs and Outputs  

- **Inputs**
  - student ID number
  - author name
  - book/product name

- **Outputs**  
  - borrow history
  - current books not returned
  - books written by specific author
  - book/product

---

## 🧠 Logic Plan  
Choose **ONE** way to describe your program’s logic:  

### Option 1: Pseudocode  
Start
Load JSON file containing library borrow history

Display menu of features:
1.) Show books not returned yet
2.) Show total number of books borrowed (per student)
3.) Show currently borrowed books (per student)
4.) Show books by author
5.) Search book by name
6.) Exit program

Ask user to choose a feature

IF user chooses 1:
    Display all books where return_date is "null"

ELSE IF user chooses 2:
   Ask user to enter borrower_id
   List all books borrowed by the student
   
ELSE IF user chooses 3:
    Ask user to enter borrower_id
    List all books where return_date is "null" under that       student, otherwise show "You have no currently borrowed books."
    
ELSE IF user chooses 4:
    Ask user to enter author
    List all books written by that author, otherwise display "Items not found."

ELSE IF user chooses 5:
    Ask user to enter book_title
    Search JSON data for matching item
    Display item details if found, otherwise display "Item not found."

ELSE IF user chooses 6:
    End program

Repeat menu until user chooses to exit
End Program


### Option 2: Flowchart  
  
 ![a7665bc9-37c2-412f-8525-4619697e12e4](https://github.com/user-attachments/assets/d87f3837-9d51-4b34-9025-ea3b39b3d1ac)
---

## 📂 GitHub Repository Link
https://github.com/JuliannaLGo/Final-Project-CS2

---
