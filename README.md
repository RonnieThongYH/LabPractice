# LabPractice

![Image PNG Import Git Hub](https://github.com/RonnieThongYH/LabPractice/blob/master/images/3d-render-korean-finger-heart-symbol-i-love-you.png?raw=true)


Exercise 5
7.5 Add and Commit Changes
Open your terminal/command prompt and navigate to your local Git repository.
Check the status of your files with git status.
Stage all changes for commit with git add . (The dot means all files; you can also add specific files).
Commit the changes with a descriptive message using git commit -m "Your commit message". Replace "Your commit message" with something descriptive about the changes you made.
7.6 Create a Git Tag
Create a tag named “Lab2_v1.1” using git tag Lab2_v1.1.
7.7 Push Changes to GitHub
Push the committed changes to GitHub with git push origin main (or master, depending on your default branch name).
Push the tag to GitHub using git push origin Lab2_v1.1.
7.8 Create a GitHub Release

(CREATE A NEW GITHUB RELEASE "LAB2_v1.1" based on the corresponding Git tag.
Go to your GitHub repository in a web browser.
Navigate to the “Releases” section found under the repository name.
Click “Draft a new release”.
Choose the tag you just pushed, in this case, “Lab2_v1.1”.
Fill in the release title and description as needed.
Publish the release by clicking “Publish release”.

Additional Exercise 6
8.1 Implement the calc_median_temperature() Function
Write the function calc_median_temperature() in your code. This function should:
Take a list of numbers (temperatures).
Sort the list in ascending order.
Find and return the median temperature.
8.2 Push Changes to GitHub
Follow the same steps as 7.5 and 7.7 to add, commit, and push these new changes.

8.3 Create a New GitHub Release
Tag the new commit using git tag Lab2_v1.2.
Push the tag using git push origin Lab2_v1.2.
Follow the same steps as 7.8 to create a new release named “Lab2_v1.2” on GitHub.
Remember to test your code thoroughly before committing and pushing, especially for the calc_median_temperature() function to ensure it works correctly.

----------------------------------------------------------------------------------------------------------


Inserting a PNG image into a GitHub README file is quite straightforward. Here are the steps to do it:

Upload the Image to Your GitHub Repository:

First, you need to upload the PNG image to your repository. You can place it in any directory, but many people create a specific directory like /images or /assets for organization.
To upload, navigate to the repository on GitHub, click on 'Add file' > 'Upload files', and then drag and drop your image file. Commit the file to the repository.
Link the Image in Your README.md File:

Open the README.md file in edit mode.
To insert the image, you will use the Markdown image syntax which is ![alt text](URL).
The "alt text" is a brief description of the image, which is helpful for accessibility and SEO.
The "URL" is the path to the image in your repository. If your repository's URL is https://github.com/yourusername/yourrepository and you have placed the image in an images folder, the URL will be https://github.com/yourusername/yourrepository/blob/main/images/yourimage.png (assuming your default branch is main).
Here's an example of what the Markdown might look like:

markdown
Copy code
![Description of Image](https://github.com/yourusername/yourrepository/blob/main/images/yourimage.png)
Preview and Commit:
Use the preview tab in GitHub's editor to make sure the image displays as expected.
Once confirmed, commit the changes to the README.md file.
That's it! Your image should now be visible in your README on GitHub. Remember that the path to the image is case-sensitive and should exactly match the path and filename in your repository.
