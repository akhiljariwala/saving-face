**To run this project, you must have links to several directories in your Google Drive. Please reach out if you need them.**

This project takes photos, attempts to detect children (ages 15 an younger) in the images, and then swaps each child face with a donor face of the same general age and gender.

This process can be broken down into three main sections:

Face Detection
Age and Gender Detection
Face Swapping
Each section is completed using a network specifically built for the given task.

Face Detection uses faced (https://github.com/iitzco/faced)
Age and Gender Detection is currently done using the process described here: https://data-flair.training/blogs/python-project-gender-age-detection/. We plan to reimplement using a network that we built
Face Swapping is achieved using fsgan (https://github.com/YuvalNirkin/fsgan)
