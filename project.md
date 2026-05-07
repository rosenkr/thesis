Goal: Make it easier as a student to share your thesis with your teacher
We often collaboratively write our thesis online in overleaf or host our latex on github.
But how should we share it with our teacher in a simple and fast way?
How can we let them know when the project is ready for review?

How: By hosting a website which contains a way of downloading the pdf for the teacher


MVP Required setup: Host using your own free github domain.

MVP:
1. At any moment, the teacher can click download as pdf, which will fetch the most recent pdf
from the github repository of the thesis.
2. If the student wants to notify when a logical new version is ready, they can click
a button which will send an email to the teacher. They can also add text of what they want
help with.
3. A github action automatically compiles the latex on new commits and pushes the pdf to the website
4. Teacher can leave feedback on the website for that draft.

Where are things stored: Github Pages?


later additions: 
-Separate the service codebase from the latex code.
-support both overleaf and github workflows