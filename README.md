# Crown-of-Throrns

Detection of crown-of-thorns starfish (COTS) in underwater videos of coral reefs.

### Using YOLOv7

In order to use the yolov7 notebook, run each cell of the notebook and then either:
- Create a folder 'test_images' and store all images to be tested in it.
- Run the cells to generate a 'test_images' folder with randomly selected images to test with.

Then, run the wandb login and install the artifacts.

Finally, install yolov7 from the repository using the respective cell in the notebook, and replace the 'detect.py' file in yolov7 with the 'detect.py' given.

Then run the final cell of the notebook to run the detection, where the results will be stored in the yolov7/runs folder.
