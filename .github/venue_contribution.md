# Contributing with your desk to the venue page of the OHBM 2021 Brainhack

You will have to add file of your image to the [`img/venue` folder](https://github.com/ohbm/hackathon2021/tree/main/img/venue) and modify the file [`_data/venue.yml`](https://github.com/ohbm/hackathon2021/blob/main/_data/venue.yml).

So here are the steps you need to do to make a pull request to do so. If you have never made a pull request, you could join the Git and GitHub session of the TrainTrack and then use this as an exercise to practice.

 1. **Find a image you want to add**
    If you don't have one, you can search some freely available images on [unsplash](https://unsplash.com/).
 2. **Fork the hackathon2021 repository to create a copy of it your github account**
    You can find more information about forking [here](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
 3. **Clone the repository from your github account to your computer**

 ```
 git clone https://github.com/_YOUR_GITHUB_USERNAME_/hackathon2021.git
 ```

  1. **Create a new branch where you want to add your image, and switch to that branch**

 ```
 git branch YOUR_NAME-venue_page_img
 git checkout YOUR_NAME-venue_page_img
 ```

  1. **Add the image file**
    Put a copy of your image in the `img/venue` folder and rename it with your github username like so `GITHUB_USERNAME.jpg`.
 2. **Modify the `_data/venue.yml`**
    You can simply add the following code to the top of the file and replace the YOUR NAME and IMAGE_FILENAME with the appropriate values.

 ```
 -
   name: "YOUR NAME"
   image: IMAGE_FILENAME
 ```

  1. **Add and then commit all the changes you have made**

 ```
 git add --all
 git commit -m 'adding image to venue page'
 ```

  1. **Update your github repository by pushing to it the changes made on the repository on your computer**

 ```
 git push
 ```

  1. **Open a pull request**
    Go and [open a pull request page](https://github.com/ohbm/hackathon2021/compare) from the `hackathon2021` repository.
  2. **We (and the magic of automation) will take care of the rest.** :-)

