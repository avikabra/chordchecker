# Update Log # 

### Jul 8 2021 - Mobile Functionality Update ###
ChordChecker now able to detect whether user is on a phone or computer, will be able to not only provide more user-friendly experience on mobile, but also will be able to add mobile-exlusive functionalities. </br>
Bugs fixed: 
1. Can now easily record on iPhone Safari browser by enabling Javascript in Settings
2. Learn page modified to be more user-friendly and aesthetically pleasing
3. Home page modified slightly for above reason

### Jul 9 2021 - Error Log ###
1. First run through the program works fine most of the time, after re-recording and re-checking though, server issues occur and the ChordChecker.py file seemingly returns multiple outputs. This needs to be fixed. 
2. Sometimes, call to chordchecker.com/api/file-upload fails and produces an error. ([Error] Failed to load resource: the server responded with a status of 500 (INTERNAL SERVER ERROR) (file-upload, line 0)) Occurs when there is an error within the code. 
Bugs Fixed: 
1. Grammar in output fixed
2. Quotation marks around notes that were not played removed