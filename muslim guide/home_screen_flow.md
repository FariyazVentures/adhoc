Home Screen prompts: 
This is Flutter app
Review code after each step, only when allowed then move forward
Code should be implemented for browser, Android and ios
Take references from below files:
Flutter best practices.md
UX best practices.md
Package structure.md

Step 1:
Splash screen feature -
Display Splash screen for 3 sec with name of App

Step 2:
Login screen feature - 
I want to create Login functionality, storing data in Firestore. It should have different methods like 1. normal username, password, 2. Login with google , 3. Login with mobile number and otp
If a user logs in for the first time then the ‘Sign Up’ option should be provided, asking for minimum details.
On mobile ask to re login only if user has not logged in for 1 week (7 days)
If login is successful then go to ‘Home Page’.
If login is not successful then display errors in ‘red’ color. 
Google Firestore:
Unique Identifier - muslim-guide-7aa4a

Step 3:
Home screen feature - 
Home screen must have 3 tabs displayed at bottom
Tab1 should have home icon and title as ‘Home’
Tab2 should have book icon and title as ‘Education’
Tab3 should have settings icon and title as ‘Settings’

At top left corner, text should be displayed as Assalam user first name 
At top center, show today’s date
At top left corner show the current location of user

At top second row center, show title as, ‘Hijri Date’: actual hijri date 
Below Hijri date, add ‘Next Prayer’ widget
Just below the widget, Farz prayers display must be there.
Below it, Icons should be displayed
Add elevated slider for Dua of the day and Hadith of the day

Step 4:
Next Prayer Widget (feature - Prayer Times) - 
It should be little elevated container
On right side of container display image of mosque
On left side:
Alert icon color matching with theme
Next line, Text: ‘Next Prayer:’
Next line, next prayer name
Next line, actual time of prayer
Next line, time remaining for prayer
Step 5:
Farz prayers display (feature - Prayer Times) - 
Display : Fajr, Dhuhr, Asr, Maghrib, Isha
For each prayer on top timer icon, next line name of prayer and next line it’s actual time for today
Only next prayer should be highlighted and all others should look disabled

Step 6:
Icons display (feature - Icons)
Display 8 icons as it looks aesthetically good and matches the color theme.
Both symbol and text should be displayed
Here is the list:
Quran
Hadith
Zakat
Dua
Hijri
Tasbeeh
Mosque
Qibla

