This README will hold any info on specifics you should take note of.

This script uses:
- Python 2
- BeautifulSoup
- Selenium Webdriver(Using Firefox) 
- Openpyxl

Inputs Files:
- Every line = 1 input

Note On Date Inputs:
- Must be written as "mm/dd/yyyy". Ex. 07/30/2016 Ex.2. 08/03/2016

Note On Time Inputs:
- You must write "Noon" and "Midnight" instead of their corresponding numerical time
- If the hour is not double digit, do not put a "0" in front. Ex. 2:30am is good. 02:30am is not good.
- "AM" or "PM" must be attached to the time. Ex. 5:30am is good. 2:00 PM is not good. (capitalization does not matter)

Note On Location Inputs:
- Alamo's location search seems to be not very well made. If you search their exact names for places most of the time it does not recognize the name for whatever weird reason.
- For airports use the airport code and it will be recognized 100% of the time.
- Otherwise you'll have to use the designated key codes for each location. Key codes apparantly seem different as some locations from the previous site don't work on this one.

