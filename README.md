# schedule_scanner

This program is for the nurses having the printed schedule. The nurses at SUS Lund get their monthly schedule as a printed paper, and it is troublesome to add their schedule to iCalender manually.
This program changes the images to text, extract the dates and times, and create ics file so that the user can easily add events to their iCalendars.

# Progress

## 2022/12/01
- Started planning the project
- Checked icalendar library and tested

## 2022/12/02
- Installed pytesseract and tested
- Trying to solve problem that pytesseract.image_to_data doesn't create correct table

## 2022/12/08
- Used opencv to change the image to black-white image. After that, pytesseract extracts the text better.
- Tested using RegEx to extract and format the actual events.
