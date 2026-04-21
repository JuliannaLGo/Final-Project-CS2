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
START

LOAD JSON file (ALE)

REPEAT
    DISPLAY "Menu:"
    DISPLAY "1) Show books not returned yet"
    DISPLAY "2) Show total number of books borrowed (per student)"
    DISPLAY "3) Show currently borrowed books (per student)"
    DISPLAY "4) Show books by author"
    DISPLAY "5) Search book by name"
    DISPLAY "6) Exit Program"

    INPUT choice

    IF choice == 1 THEN
        FOR each book in data
            IF book is not returned
                DISPLAY book details
            ENDIF
        ENDFOR

    ELSE IF choice == 2 THEN
        FOR each student
            COUNT books borrowed
            DISPLAY student name + total books borrowed
        ENDFOR

    ELSE IF choice == 3 THEN
        FOR each student
            DISPLAY student name
            FOR each borrowed book
                IF book is not returned
                    DISPLAY book details
                ENDIF
            ENDFOR
        ENDFOR

    ELSE IF choice == 4 THEN
        INPUT author name
        FOR each book
            IF book author matches input
                DISPLAY book details
            ENDIF
        ENDFOR

    ELSE IF choice == 5 THEN
        INPUT book name
        FOR each book
            IF book name matches input
                DISPLAY book details
            ENDIF
        ENDFOR

    ELSE IF choice == 6 THEN
        DISPLAY "Exiting program..."
        EXIT LOOP

    ELSE
        DISPLAY "Invalid choice. Try again."
    ENDIF

UNTIL choice == 6

END

### Option 2: Flowchart  
<img width="372" height="532" alt="Screenshot 2026-04-22 at 12 06 06 AM" src="https://github.com/user-attachments/assets/367e7d64-a1f1-4e05-aacd-f1856d7bfc76" />
  
---

## 📂 GitHub Repository Link
https://github.com/JuliannaLGo/Final-Project-CS2

---
