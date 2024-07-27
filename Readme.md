# 🎉 Face Recognition Based Attendance System

# Welcome to the Face Recognition Attendance System using OpenCV and Python. This system captures images using a camera and marks attendance by comparing them with images in the database.

### 📌 Tech Stack

Here’s what fuels this site:
![PYTHON](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![DBIL](https://img.shields.io/badge/Dlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NUMPY](https://img.shields.io/badge/Numpy-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OPENCV-PYTHON](https://img.shields.io/badge/OpenCV-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SCIKIT IMAGE](https://img.shields.io/badge/Scikit-Image-3776AB?style=for-the-badge&logo=python&logoColor=white)


# **Note: Developed on macOS Sonoma 14.3.1. May not work on other operating systems due to dependencies on OpenCV, pandas, and Flask.**

### 🛠️ How to Contribute: Let’s Make Magic!

Want to jump in and sprinkle some magic on this project? Follow these steps:

1. **Fork and Clone**:
   - Hit “Fork” at the top-right of the page to make your copy. Then clone it to your local machine:
     ```bash
     git clone git@github.com:xodivorce/xodivorce_in.git
     ```

3. Download the dlib models:
   - Visit: *https://drive.google.com/drive/folders/1SZcMLxUho7fc9ugj_cGEGmOu38A8zcKU?usp=share_link*
   - Place the `data` folder inside the repo.

4. Install specific versions of dependencies [*usingpip*](https://pypi.org/project/pip/):

- **Dlib installation**:
  ```bash
      # Dlib version = 19.24.2
       pip install dlib==19.24.2
      ```

- **Numpy installation**:
    ```bash
      # Numpy version = 1.26.4
       pip install numpy==1.26.4
      ```

- **OpenCV-Python installation**:
    ```bash
      # Opencv-python version = 4.9.0
       pip install opencv-python==4.9.0
      ```

- **Pandas installation**:
    ```bash
     # Pandas version = 2.2.2
       pip install pandas==2.2.2
      ```

- **Scikit-Image installation**:
    ```bash
     # Scikit-image version = 2.2.2
       pip install scikit-image==2.2.2
      ```

- **Flask installation**:
    ```bash
     # Flask version = 3.0.3
       pip install flask==3.0.3
      ```

# 🎬 Usage

# 1. Collect the Faces Dataset:
python get_faces_from_camera_tkinter.py

# 2. Convert the dataset:
python features_extraction_to_csv.py

# 3. Take attendance:
python attendance_taker.py

# 4. Check the Database:
python app.py

# 🛠️ How to Contribute: Let’s Make Magic! 🌟

# Want to jump in and sprinkle some magic on this project? Follow these steps:

# 1. **Fork and Clone**:
#    - Hit “Fork” at the top-right of the page to make your copy. Then clone it to your local machine:
git clone git@github.com:xodivorce/face_recognise_attend.git

# 2. **Set Up Your Local Playground**:
#    - Move the project to your working directory:
cd face_recognise_attend

# 3. **Create a Feature Branch**:
#    - Before diving in, create a new branch for your feature or fix:
git checkout -b cool-new-feature

# 4. **Work Your Magic**:
#    - Make your changes, test them, and get ready for a pull request.

# 5. **Commit and Push**:
#    - Once you’re happy, commit and push your changes:
git add .
git commit -m "Add some cool feature"
git push origin cool-new-feature

# 6. **Open a Pull Request**:
#    - Go to the main repository and create a pull request. Let us know what you’ve done and why it’s awesome!

# 7. **Celebrate Your Contribution** 🎉:
#    - Enjoy the glory of your awesome contribution! We appreciate all your help and ideas.

# 🚀 **Got Ideas or Spotted a Bug?**  
# Don’t be shy! [*Open an issue*](https://github.com/xodivorce/face_recognise_attend/issues) to discuss new features, enhancements, or any bugs you find. Your feedback is golden!!

# Let’s create something epic together! 🌟

# 📝 License & Usage

# This project is licensed under the [**Xodivorce License Agreement**](xodivorce_license.txt). By accessing or contributing to this project, you agree to the following terms:

# 1. **Contributions**:
#    - Contributions (code, documentation, etc.) are welcome but must be reviewed and approved by the Owner.

# 2. **Use of Content**:
#    - Content can be viewed, downloaded, and printed for personal use only. For any other use, explicit permission from the Owner is required.

# 3. **Attribution**:
#    - Proper credit must be given to the Owner, including a link to this license and noting any changes made.

# 4. **No Derivative Works**:
#    - Modified versions of the content cannot be distributed without prior written permission.

# 5. **Requesting Permission**:
#    - To use any content from this project, contact the Owner at hey@xodivorce.in.

# 6. **Copyright Infringement**:
#    - Unauthorized use may result in a copyright strike and legal action.

# **🌟 Like this project? Please consider giving it a star to show your support!**

# An Open Sourced Project - Crafted with ❤️ by xodivorce