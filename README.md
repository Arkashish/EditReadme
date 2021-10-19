# EditReadme
## Convert the OS based program into a menu driven program using Python Code which will execute the required user query when user will give the input as a text
import pyttsx3
import os

pyttsx3.speak("Welcome to my Voice Assistant")</br>
while(True):</br>
	print("Enter your Query: ")</br>
	print("      1. to open Chrome browser ")</br>
	print("      2. to open Notepad ")</br>
	print("      3. to open Windows Media Player ")</br>
	print("      4. to open VS Code")</br>
	print("      5. to open utorrent")</br>
	print("      6. to open Internet Explorer")</br>
	print("      7. to open Paint ")</br>
	print()</br>
	print("Enter your choice: ",end = ' ')</br>
	p = input()</br>
	print(p)</br>
	if( ( ((("run" in p) or ("execute" in p) or ("open" in p)) and (("chrome" in p) or ("browser" in p))) and ("don't" not in p ))):</br>
      		print("chrome")</br>
      		os.system("chrome")  </br>   
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("notepad" in p) or ("editor" in p)) ) and ("don't" not in p )):</br>
     		print("notepad")</br>
     		os.system("notepad")</br>
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("media player" in p) or ("wmplayer" in p)))  and ("don't" not in p )):</br>
     		print("Windows Media Player")</br>
     		os.system("wmplayer")</br>
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("Visual Studio Code" in p) or ("Program app" in p))) and ("don't" not in p )):</br>
     		print("Visual Studio Code")</br>
     		os.system("vscode")</br>
	elif ( ( (("run" in p) or ("execute" in p) or ("open" in p)) and (("torrent" in p) or ("utorrent" in p))) and ("don't" not in p )):</br>
     		print("uTorrent")</br>
     		os.system("uTorrent")</br>
	elif (( (("run" in p) or ("execute" in p) or ("open" in p)) and (("internet explorer" in p) or ("web browser " in p) or ("internet browser" in p))) and ("don't" not in p)):</br>
     		print("Internet Explorer")</br>
     		os.system("iexplore")</br>
	elif (( (("run" in p) or ("execute" in p) or ("open" in p)) and (("Microsoft paint" in p) or ("paint" in p))) and ("don't" not in p )):</br>
     		print("Microsoft Paint")</br>
     		os.system("mspaint")</br>
	elif  ("exit" in p) or  ("quit" in p):</br>
		break</br>
	else:</br>
      		print("Sorry try something else")</br>



