# DLCV4995 - Final Project - Title and Theme Recognition on Video Game Covers
---
Since we have a large model file, it was not able to upload to github. You may use Lion Email (Columbia University Gmail) to access our project. For deadline issue, we are not going to modify any files under this shared folder after 11:58pm Dec 9th 2022. https://drive.google.com/drive/folders/12G9fqoPEWe9IvY06wewRJMnrQ-uGsS5F?usp=sharing
---
# Group Members:
- Ruiting Mei (UNI: rm3959)
- Tao Zhang (UNI: tz2544)
- Yi Zhang (UNI: yz4339)
# How to start
- Models were well trained and saved in `models` folder under the main directory. For convinient use, `theme_resnet18_model.pt` and `rating_resnet18_model_v2.pt` could be used by pytorch cpu, and other trained models under this directory are used by pytorch `MPS`.
- You can start to predict a game cover image under `final_project.ipynb`
- Running all code under Section `8.1.Prediction Code`, modify the path name to the main directory, such as `./`
- You can predict your own image by changing the `file_name` of the image file under the main directory and run `predict()`, or run `predict(your image directory)`
- The output of the prediction will show up a sentence including a cropped image with the name of the title, two of related video game's themes, and the expecting rate of the video game.
