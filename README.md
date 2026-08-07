## Testing google gemini api with flash 3.6 model inside google app script

#### Step 1<br>
goto <a href='https://script.google.com/home'>google app script home</a> to create a new project<br>
<br>
#### Step 2<br>
find the <a href='[https://raw.githubusercontent.com/WingsMaker/kimi-k3-demo/refs/heads/main/google_script.txt](https://raw.githubusercontent.com/WingsMaker/gemini_flash_demo/refs/heads/main/google_script.txt) '>google_script.txt</a> in this github<br>
copy-paste the content onto the google script project<br>
<br>

#### Step 3<br>
  goto <a href='https://aistudio.google.com/api-keys'>Google Ai Studio</a> to get  get a free api key<br>
  goto the google app script project setting, goto script properties section<br>
  add a property name as "GEMINI_API_KEY".<br>
<img width="376" height="853" alt="image" src="https://github.com/user-attachments/assets/6aa896c4-fc50-428b-95eb-ebc24602d8a2" />
<br>
  paste the api key value below screen<br>
<img width="650" height="80" alt="image" src="https://github.com/user-attachments/assets/52a1abe1-202a-43a0-b935-d0b37f91d807" />
<br>

<br>
### Step 4<br>
goto the bottom of the script where function testKimiK3 is, change the code:<br>
  const prompt = "...put in your own prompts";<br>
<br>
### Step 5<br>
at the top of the Apps Script editor, find the dropdown list between "Debug" and "Execution log".<br>
Select "test_gemini" and click the "Run" option to test run<br>
<br>
<img width="647" height="241" alt="image" src="https://github.com/user-attachments/assets/83f4faf1-09f5-4e68-b06b-a13badd9bf69" />
<br>
Click on the "Execution log", you will see the results of the test run<br>
<img width="1177" height="707" alt="image" src="https://github.com/user-attachments/assets/541a472c-9556-4d41-a373-e733f2d6087d" />
<br>
