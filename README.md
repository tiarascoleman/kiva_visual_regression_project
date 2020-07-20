# kiva_visual_regression_project
Known as PRO-2112, this project's purpose is to write a script in Backstop that can compare two images for differences then make it extensible so that it can compare multiple image-pairs in a loop.
Lastly the screenshot diff engine should allow a human to visually inspect the two images compared for verification. 
These tests were created and inspired from the Udemy course, "Visual Regression Testing with BackstopJS" by Walmyr Lima e Silva Filho.

Additionally, this project performs four scenarios in which three will pass and one will fail. I kept the one that fails to showcase how dynamic data alters the engine while also to showcase how the engine works when there is a difference. Two scenarios also focuses on specific components of the webpage.

In order to run the program, in the terminal window type: 
"npm test" which will create the reference images (make sure all of the images are displayed) then type in the window:
"npm run visual:approve" thus this will compare the two images (the reference image and the screenshot)
