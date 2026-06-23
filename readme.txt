==========================================
  HR CHATBOT (FREE VERSION) — SETUP GUIDE
==========================================

WHAT YOU HAVE:
  index.html   → The employee chat page
  policies.js  → Your HR policy text (you edit this)
  README.txt   → This guide

TOTAL COST: ₹0 / $0 — completely free forever.

==========================================
STEP 1: GET YOUR FREE GOOGLE GEMINI API KEY
==========================================

1. Go to:  https://aistudio.google.com
2. Sign in with your Google account (Gmail)
3. Click "Get API Key" (top left or in menu)
4. Click "Create API Key"
5. Copy the key — it looks like: AIzaSy...
   Save it somewhere safe.

FREE LIMITS (more than enough for a company):
  - 1,500 requests per day
  - 1 million characters per request
  - No credit card required

==========================================
STEP 2: ADD YOUR API KEY TO index.html
==========================================

1. Right-click index.html → "Open with" → Notepad
2. Find this line (near the bottom, in the SCRIPT section):

   const GEMINI_KEY = 'YOUR_GEMINI_API_KEY';

3. Replace YOUR_GEMINI_API_KEY with your real key. Example:

   const GEMINI_KEY = 'AIzaSyAbCdEfGhIjKlMnOpQrStUvWx';

4. Save the file (Ctrl+S)

==========================================
STEP 3: ADD YOUR OWN HR POLICIES
==========================================

1. Open policies.js in Notepad
2. You will see sample HR policies already there
3. Replace the sample text with your real company policies
4. Keep the same format — each policy section starts with:
     === SECTION NAME ===
   Then the policy text below it.
5. Save the file.

TIP: To convert a Word document to plain text:
  - Open in Word → File → Save As → choose "Plain Text (.txt)"
  - Then copy the text from the .txt file into policies.js

==========================================
STEP 4: TEST IT ON YOUR COMPUTER
==========================================

Before putting it online, test it locally:
1. Open the folder where your files are saved
2. Double-click index.html — it will open in your browser
3. Type a question and check if it answers correctly

NOTE: The file loading (policies.js) may not work when 
opening directly from your desktop in some browsers. 
If you see "HR policies not loaded", skip to Step 5 
(uploading to GitHub) and test from the live URL.

==========================================
STEP 5: PUT IT ONLINE WITH GITHUB (FREE)
==========================================

A) CREATE A GITHUB ACCOUNT (if you don't have one):
   1. Go to https://github.com
   2. Click "Sign up" — use your email, it's free

B) CREATE A REPOSITORY (this is your website folder):
   1. After logging in, click the "+" button (top right)
   2. Click "New repository"
   3. Repository name: hr-chatbot
   4. Set it to PUBLIC (required for free hosting)
      NOTE: Anyone with the link can see your HTML code.
            Your policies text will also be visible in the source.
            If this is a concern, see the "SECURITY NOTE" below.
   5. Check "Add a README file"
   6. Click "Create repository"

C) UPLOAD YOUR FILES:
   1. In your new repository, click "Add file" → "Upload files"
   2. Drag and drop BOTH files: index.html AND policies.js
   3. Click "Commit changes"

D) TURN ON GITHUB PAGES (free hosting):
   1. In your repository, click "Settings" (tab at the top)
   2. In the left menu, click "Pages"
   3. Under "Branch", select "main" from the dropdown
   4. Click "Save"
   5. Wait 1-2 minutes
   6. Refresh the page — you will see your website URL!
      It will look like: https://YOUR-USERNAME.github.io/hr-chatbot/

YOUR CHAT PAGE IS LIVE AT:
  https://YOUR-USERNAME.github.io/hr-chatbot/

Share this link with your employees!

==========================================
HOW TO UPDATE POLICIES IN THE FUTURE
==========================================

1. Go to your GitHub repository
2. Click on "policies.js"
3. Click the pencil icon (Edit this file)
4. Make your changes directly in the browser
5. Click "Commit changes"
6. The live website updates automatically in 1-2 minutes!

==========================================
SECURITY NOTE
==========================================

Because GitHub Pages is a public free service, your files
(including policies.js) are technically readable by anyone
who knows the URL or looks at your GitHub repository.

For most companies, this is acceptable because:
- HR policies are usually shared with all employees anyway
- The URL is not publicly advertised

If you want to keep policies private, the options are:
- Use a private repository on GitHub (requires GitHub Pro ~$4/month)
- Or ask an IT person to set up a simple backend

For a starter solution with no cost, this version is ideal.

==========================================
TROUBLESHOOTING
==========================================

"HR policies not loaded":
  → Make sure policies.js is uploaded to GitHub alongside index.html
  → Make sure the filename is exactly: policies.js (lowercase)

"Error: API key not valid":
  → Double-check your Gemini API key in index.html
  → Make sure there are no extra spaces around the key

"I couldn't find information about that":
  → Your question may be about something not in policies.js
  → Add more policy sections to policies.js

Chat doesn't load at all:
  → Check your internet connection
  → Try a different browser (Chrome works best)

==========================================
NEED HELP?
==========================================
Go to claude.ai and paste your error message.
Say: "I am setting up a free HR chatbot and I see this error: [paste error]"
==========================================
