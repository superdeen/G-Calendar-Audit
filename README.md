# G-Calendar-Audit
Simple lazy script to check for public Google Calendar. 

Reference: 
1. https://medium.com/@logicbomb_1/ok-google-please-reveal-everyones-public-calendar-27523206f9ac
2. https://sites.google.com/securifyinc.com/secblogs/exploitingcalendars

# Usage
1. git clone git@github.com:tutorgeeks/G-Calendar-Audit && cd G-Calendar-Audit.git
2. pip install -r requirements.txt
3. Configure your chromedriver path.
   webdriver.Chrome('Path to your ChromeDriver installation')
4. Enter the list of emails that you wanted to test in "emails.txt" file.
	
	-	abc@gmail.com
	-	xyz@gmail.com
   
 # Output

- Make available to public: abc@gmail.com
- Access Restricted: xyz@gmail.com
   
   
  