## Testing google gemini api with flash 3.6 model inside google app script

#### Step 1<br>
goto <a href='https://script.google.com/home'>google app script home</a> to create a new project<br>
<br>
#### Step 2<br>
find the <a href='[https://raw.githubusercontent.com/WingsMaker/kimi-k3-demo/refs/heads/main/google_script.txt](https://raw.githubusercontent.com/WingsMaker/gemini_flash_demo/refs/heads/main/google_script.txt) '>google_script.txt</a> in this github<br>
copy-paste the content onto the google script project<br>
<img width="376" height="853" alt="image" src="https://github.com/user-attachments/assets/6aa896c4-fc50-428b-95eb-ebc24602d8a2" />

<br>
#### Step 3
  goto <a href='https://aistudio.google.com/api-keys'>Google Ai Studio</a> to get  get a free api key<br>
  goto the google app script project setting, goto script properties section to add a property name as "GEMINI_API_KEY".
  paste the api key value below screen<br>

<br>
### Step 4<br>
goto the bottom of the script where function testKimiK3 is, change the code:<br>
  const prompt = "...put in your own prompts";<br>
<br>
### Step 5<br>
at the top of the Apps Script editor, find the dropdown list between "Debug" and "Execution log".<br>
Select "testKimiK3" and click the "Run" option to test run<br>
<br>
<img width="920" height="132" alt="image" src="https://github.com/user-attachments/assets/98032017-45bb-49b4-ad76-a0bc278492c9" />
<br>
Click on the "Execution log", you will see the results of the test run<br>
