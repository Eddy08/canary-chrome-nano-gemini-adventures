# TLD: https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/edit
# I got the above doc link from chromeai.pro document section : ![image](https://github.com/user-attachments/assets/33b5e584-e301-4216-a453-3d3576c8d2c6)

# canary-chrome-nano-gemini-adventures which I took
as of 2-10-2024:
If you are still unable to use chrome nano gemini and which options users are must have to make it work.
1. Download Chrome Canary
2. You need to login to chrome with your google credentials
3. go to chrome flags And Search for Nano and select all the API for Gemini Nano
4. again search for enables optimization guide on device and first click on enable if the Enable 
ByPassPerfRequirment is not still visible.
5. go to chrome components and update all the componenets.
6. For me the Enable ByPassPerfRequirement was not visible until I go to settings and enabled console errors ai bulb : a. Bulb: ![image](https://github.com/user-attachments/assets/fa7bc354-09e1-4d0e-bcd5-d817fb2f959c)
b. After Hovering over the Bulb: ![image](https://github.com/user-attachments/assets/a9f3764e-e23b-4a6c-8f2d-08b8f18c3918)
c. Click on the Update Settings: ![image](https://github.com/user-attachments/assets/730d24dd-2714-4cfe-8d30-ed5dd27a31ba)
d. Enabled Console Insights: ![image](https://github.com/user-attachments/assets/519e2e96-1324-4f9a-a9ac-3006c74faac0)

 and then ![image](https://github.com/user-attachments/assets/c9d9d9de-48a0-4379-a48d-4c61b9b42bdf)

7. go to chrome components: And you must have Optimization Guide On Device Model Option Downloaded :![image](https://github.com/user-attachments/assets/80648412-7b45-49b3-afac-43fe171b6756)
8. Finally It looks like this: ![image](https://github.com/user-attachments/assets/0e0aa94c-cef4-4b28-b18f-665cd82d9264)
9. Still It was not working then I followed the steps described in docs:https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/edit and gone till their failure steps i.e create() // for creating the assistant and then relaunching the chrome and then go the components and then update and then finally the ready came up.
10. Other repos / medium articles that I have looked and they were are takling about the below chrome component that must be present:
11. After following all the steps in this it worked : Super useful ![image](https://github.com/user-attachments/assets/7ff7f795-d54b-4a26-a316-b04dee8f27e9)
https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/edit
  - a. https://chromeai.pro/#faq-setup
  - b. https://github.com/lightning-joyce/chromeai?tab=readme-ov-file#how-to-set-up-built-in-gemini-nano-in-chrome
  - c. https://github.com/ontaptom/gemini-nano-chrome#getting-started
  - d. https://medium.com/@mindplay/doesnt-work-8a7bded8ff0c
  - e. reddit: https://www.reddit.com/r/LocalLLaMA/comments/1d9v9kb/gemini_nano_with_chrome_in_your_browser/?rdt=46018
12. Using the below playground for testing:https://chrome.dev/web-ai-demos/prompt-api-playground/
    ![image](https://github.com/user-attachments/assets/88dca4a9-a8bb-45a8-aea1-f315cf90db74)
13. ** And Yes it works offline as well **:
    ![image](https://github.com/user-attachments/assets/2f0c782d-b0c8-470a-bde4-405c4a777604)
