# Team Website Contribution
Now you get to make some changes. The website has "cards" to display some information for each cohort. Each person will be assigned a cohort number and will only make changes to that "card". 

### 1. Navigate to your folder:
Open Terminal and navigate to your project folder. Make sure to checkout the branch you created earlier and check status - this is important.
```
%git checkout <yourBranch>
```

### 2. Open Visual Studio Code (VS Code):
While in Terminal open VS code by entering the following command:
```
%code .
```
VS Code will open in the corresponding folder. If this command does not launch VS Code for you, please follow these [instructions](https://code.visualstudio.com/docs/setup/mac) to configure this shortcut from Terminal.  

### 3. Preview your work
In order to preview your work in your browser, use [Live Server](https://www.geeksforgeeks.org/how-to-enable-live-server-on-visual-studio-code/). This is a VS code feature that will show a "live" version of the website and will update when you make changes in the html. To access the Live Server, right click on the `<>home.html` file and select "Open with Live Server" from the pop up menu.

<img src="images/SelectLiveServer.jpg" width="40%" length="40%"> 

The webpage will open in your browser and should look like this:

<img src="images/webPageStart.jpg" width="40%" length="40%"> 

### 4. Make the assigned changes to the website
Each person will be assigned a cohort card number. You can find your assigned Cohort number in the the HTML under "title" <br> ```<p class="title">COHORT 1</p>```. 

```js
 <div class="column">
          <div class="card">
            <img src="images/SamplePic.jpg" alt="Cohort1">
            <div class="container">
              <h2>Your Name</h2>
              <p class="title">COHORT 1</p>
              <p>Some text that describes me lorem ipsum ipsum lorem.</p>
              <p>example@example.com</p>
              <p><button class="button">Contact</button></p>
            </div>
          </div>
        </div>
        
 ```       
You will update the following: 
- Upload your picture to the image folder (shoulder and up). We can take the picture here. The image file name will be `cohort#.jpg`. So the image for cohort 1 will be `cohort1.jpg`. In order to make the image square you can use the following website: https://squareanimage.com/ 
- Change the `img src=` to point to the image you uploaded
- In the `<h2>Your Name`, enter your First and Last Name
- In the `<p>Some text...`, enter a short sentence that describes something about you (i.e.: a hobby, that you are a Tech Participant at NFAR, etc.)
- in the `<p> example@example.com`, enteryour@autest.net email address

### 5. Review your work
Review your work as you are making changes. Save changes and refresh the browser to see your changes. Once you are satisfied with your changes you can submit for it to get merged with the main repository. 

### 6. Stage, Commit, and Push changes to your branch
Once you are ready to merge your branch changes with the main repository, you will need to stage, commit, and push to the remote repository.  

Stage your files: 

```
%git add home.html
%git add images/<cohort#.jpg>
```
Commit your files: 

```
%git commit –m “changes to card "#" ”
```
Push your branch changes to the remote repository:

```
%git push
```
Go to the website project repository in GitHub. While in GitHub, click on "branches":

<img src="images/branchesLink.PNG" width="60%" length="60%"> 

Make sure your remote branch is updated with the changes you pushed. 

<img src="images/branchUpdatesStatus.png" width="80%" length="80%"> 

You are now ready to submit a pull request. 

### [Next - Step 6: Submit a Pull Request:](6_SubmitPullRequest.md)
