# CloudPhy
This is the repository of our Inter IIT Project
The aim of this Project was to extract vitals from monitor screens using images.
We used Corner Regression and UNET++ ensembling model to extract monitor screens from overall images.
The extracted images we then passed through a YoloV5 + Paddle OCR weighted box fusion to get bounding boxes of vitals on screens
The bounding boxes were then passed through Parseq OCR to detect the numbers and store them.
And finally these numbers were assigned to their respective vitals using our custom architecture CRABB-Net , outputing a dictionary of all the useful vitals on screen.
The PPT shows all the work we've done on this project
The notebook is a demo for the accuracy to be calculated.
## Here are the weights for the model : https://drive.google.com/file/d/1yf4VYtoKLXT7hcXvroFhkcVhAihc6XKg/view?usp=sharing
