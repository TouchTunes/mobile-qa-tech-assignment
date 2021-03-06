# mobile-qa-tech-assignment

This is the home assignment to assess your coding skills and **test design** skills. Please use Appium with any Appium client and push your code to a public git repository, alongside with clear instruction to set up environment and to run your code. Follow the Page Object model or any design pattern of your choice. If you choose not to use Page Object model, please explain why. Readability of the code and your QA sense is most important for us. 

**Please do not make a pull request. Give us a link to your repository instead.**

Good Luck!

# Notes:

1. The APK file of application under test is here: https://apkpure.com/touchtunes/com.touchtunes.android 

2. The instructions on how to setup Appium can be found here: https://www.swtestacademy.com/how-to-install-appium-on-mac/

3. When users first opens the application, there is an onboarding flow that they can do. You can either test the flow or simply skip it.

![Skip onboarding](assets/skip_onboarding.png)

4. You can use any jukebox that you want. Please provide GPS coordinates so that we can use the same location.

![Coordinates](assets/coordinates.png) 

# Question:

Choose any jukebox location. Open “Hot at \<jukebox name\>” menu on the home page, than open “Hot Artists” menu. 

![Navigation](assets/navigation1.png)    ![Navigation](assets/navigation2.png)


Verify that the artists displayed on this page are aligned with the artists displayed at “HOT AT \<jukebox name\>” vertical list of the home page.

![Horizontal](assets/artist_horizontal_list.png)    ![Vertical](assets/artist_vertical_list.png)

