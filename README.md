# Machine-Learning-Faces

## Project:
This project was created in order to tell the difference between a photo of a real person and a photo of a computer generated person. This version is limited to only telling the difference between a photo created by thispersondoesnotexist.com. The guidelines were to use machine learning to produce an application that could be displayed. This project could be further developed and used in marketing campaigns. 

## Marketing Use:
This project could be used to group photos of people into categories for marketing purposes. If one were to use this to determine the age or gender of a user based on a profile photo, the marketing could be tailored to that person without having to rely on self reported data. 

## Real World Use Case:
A condom company has used this technology to scan for photos of babies on Facebook and block them from sight. Based on the idea that a baby may cause the customer base to want a family and therefore not have a need for the project, this tool would be useful to keep babies out of the thought. (https://us933fm.com/news/a-condom-brand-has-an-app-that-blocks-baby-photos-on-facebook/)

## How it's done:
A scrape of thispersondoesnotexisit using selenium. A screenshot of each page was taken and cropped to only show the photo.
Machine learning, Keras, was used to teach the modle the difference between the real and fake faces. Once completed, this was saved as a pickle for the app.
A Flask app was created that used werkzeug to allow a user to upload a photo to test. The photo was saved, converted to a string, and tested, before returning the final answer to the user.
The UI was created using bootstrap to allow users the ability to use this on any sized device.

## Other People Who Worked On This Project:
Roman Collins https://github.com/romancollins30
Katherine Huynh https://github.com/ktaliah
