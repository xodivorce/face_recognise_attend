# [Face Recognition Based Attendance System](https://en.wikipedia.org/wiki/Facial_recognition_system)

### Welcome to the Face Recognition Attendance System using OpenCV and Python. This system captures images using a camera and marks attendance by comparing them with images in the database. - deveoped by [@xodivorce](https://instagram.com/xodivorce) ✨
[![status](https://img.shields.io/badge/status-active-brightgreen.svg?style=flat)](https://github.com/xodivorce/face_recognise_attend)
[![version](https://img.shields.io/badge/version-v6.9.12-yellow.svg?style=flat)](https://github.com/xodivorce/face_recognise_attend)
[![PRs](https://img.shields.io/badge/PRs-welcome-blue.svg?style=flat)](https://github.com/xodivorce/face_recognise_attend)
<br></br>

### 📌 Tech Stack

Here’s what fuels this Application:

![PYTHON](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![DBIL](https://img.shields.io/badge/Dlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NUMPY](https://img.shields.io/badge/Numpy-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OPENCV-PYTHON](https://img.shields.io/badge/OpenCV-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SCIKIT IMAGE](https://img.shields.io/badge/Scikit-3776AB?style=for-the-badge&logo=python&logoColor=white)


**Note: Developed on macOS Sonoma 14.3.1. May not work on other operating systems due to dependencies on OpenCV, pandas, and Flask.**

### 🛠️ How to Contribute: Let’s Make Magic!

Want to jump in and sprinkle some magic on this project? Follow these steps:

1. **Fork and Clone**:
   - Hit “Fork” at the top-right of the page to make your copy. Then clone it to your local machine:
     ```bash
     git clone git@github.com:xodivorce/xodivorce_in.git
     ```
2. **Set Up Your Local Playground**:
    ```bash
    #Visit the project to your working directory:
     cd face_recognise_attend
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

5. Collect the Faces Dataset:
    ```bash
     python get_faces_from_camera_tkinter.py
    ```

6. Convert the dataset:
    ```bash
     python features_extraction_to_csv.py
    ```

7. Take attendance:
    ```bash
     python attendance_taker.py
    ```

8. Check the Database:
    ```bash
     python app.py
    ```

9. **Create a Feature Branch**:
    - Before diving in, create a new branch for your feature or fix:
    ```bash
     git checkout -b cool-new-feature
    ```

10. **Work Your Magic**:
    - Make your changes, test them, and get ready for a pull request.

11. **Commit and Push**:
    - Once you’re happy, commit and push your changes:
  ```bash
     git add .
     git commit -m "Add some cool feature"
     git push origin cool-new-feature
    ```

12. **Open a Pull Request**:
    - Go to the main repository and create a pull request. Let us know what you’ve done and why it’s awesome!

13. **Celebrate Your Contribution** 🎉:
    - Enjoy the glory of your awesome contribution! We appreciate all your help and ideas.

🚀 **Got Ideas or Spotted a Bug?**  
Don’t be shy! [*Open an issue*](https://github.com/xodivorce/face_recognise_attend/issues) to discuss new features, enhancements, or any bugs you find. Your feedback is golden!!

- Let’s create something epic together! 🌟

### 📝 License & Usage

This project is licensed under the [**GNU General Public License v3.0**](LICENSE). By accessing or contributing to this project, you agree to the following terms:

1. **Contributions**:
   - Contributions (code, documentation, etc.) are welcome and must be made under the same GPLv3 license.

2. **Use of Content**:
   - Content can be viewed, downloaded, and used according to the terms of the GPLv3. This includes the freedom to use, modify, and distribute the software.

3. **Attribution**:
   - Proper credit must be given to the original authors. Include a link to the GPL license and indicate any changes made to the original content.

4. **Derivative Works**:
   - Modified versions of the content can be distributed under the same GPLv3 license. This ensures that all modifications remain free and open-source.

5. **Requesting Permission**:
   - For specific permissions or exceptions not covered by the GPL, contact the Owner at *hey@xodivorce.in*.

6. **Copyright Infringement**:
   - Unauthorized use that violates the terms of the GPLv3 may result in legal action.

© 2024 Prasid (xodivorce.in). All rights reserved.

**🌟 Like this project? Please consider giving it a star to show your support!**

<br></br>

****

An Open Sourced Project - Crafted with ❤️ by **xodivorce**