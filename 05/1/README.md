# Rock Paper Scissors with Teachable Machine

This project uses a model trained with Teachable Machine to classify images of rock, paper, and scissors.

## Files
- teachable.ipynb: Jupyter notebook for testing model functions.
- rock-paper-scissor.py: Command line script to classify a single image.
- rock-paper-scissor-live.py: Live classification using a webcam.
- keras_Model.h5: Trained model file.
- labels.txt: Class labels.

## YouTube Video
Watch the live classification demo [here](https://youtu.be/HW8p2XjJQM8).

## How to Use
1. Install dependencies: `pip install numpy tensorflow pillow opencv-python matplotlib`.
2. Run the Jupyter notebook `teachable.ipynb` to test functions.
3. Use `rock-paper-scissor.py` to classify a single image:
    ```sh
    python rock-paper-scissor.py --image-path path_to_image.jpg
    ```
4. Use `rock-paper-scissor-live.py` to classify images from the webcam:
    ```sh
    python rock-paper-scissor-live.py
    ```

## Notes
- Ensure you have a webcam connected for live classification.
