# schedule_scanner

This program is for nurses who have a printed schedule. Nurses receive their monthly schedule as a printed paper, and it can be tedious to manually add the schedule to iCalendar. This program converts the images to text, extracts the dates and times, and creates an .ics file so that the user can easily add events to their iCalendar.

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

## 2022/12/16

- Conducted some experiments with cropped images.
