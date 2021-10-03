# ECE444-F2021-Lab3
this repo is a clone of https://github.com/nelaturuk/education_pathways.

Activity 1: Docker Installation
![Screen Shot 2021-09-30 at 10 43 28 PM](https://user-images.githubusercontent.com/38872576/135767728-811b039b-980c-4ae2-961a-005dcc0a1d7d.png)

Activity 2: Clone education pathways repo
![Screen Shot 2021-10-03 at 3 01 59 PM](https://user-images.githubusercontent.com/38872576/135767772-af0a047f-d839-4214-8381-abc0ceeb910b.png)

Activity 3: Build docker image
![Screen Shot 2021-09-30 at 10 51 03 PM](https://user-images.githubusercontent.com/38872576/135767787-e1a2f2c7-8006-462f-a64c-3c26ccb9db68.png)
![Screen Shot 2021-09-30 at 10 59 11 PM](https://user-images.githubusercontent.com/38872576/135767801-dcee2cf2-e0f3-4bcf-bee2-0bbc44b0fbcd.png)

Activity 4: Run application

![Screen Shot 2021-09-30 at 10 59 42 PM](https://user-images.githubusercontent.com/38872576/135767822-1d44ea05-3aba-45a6-b4ef-7e93ff5ab9f9.png)

Activity 5:

One functional requirement I would like is the ability to "favourite" or save courses I'm interested in. Currently, the application only supports querying courses based on keywords, course year and campus. However, it displays all courses just as a static web page, and is purely informational in nature. As a user, I'd prefer not to keep looking for the same courses over and over again upon subsequent visits to this application. I want to keep track of all the courses I was interested in, and have the application do this for me. A potential way to implement this would be to add a new button to each row, like a heart icon, and another box that keeps track of the saved courses.

A non-functional requirement is the UX of page - specifically the responsiveness of the UI. The current page is not responsive at all to different screen dimensions, and information is actually cut off if my browser is too small. To make matters worse, there is no horizontal scroll bar to access this information as well, rendering the application unusable. To improve this, I would implement proper CSS and boundary checks to display the content to fit the user's browser dimensions. 
