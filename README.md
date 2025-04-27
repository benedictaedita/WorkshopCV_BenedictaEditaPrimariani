# Instructions for Running the Project
1. **Download the following files:**
     - `workshop_cv.ipynb`
     - `haarcascade_frontalface_default.xml`
     - The "images" folder
2. Place all the downloaded files into a single folder.
3. Open the `workshop_cv.ipynb` notebook.
4. Before running the notebook, ensure that the file paths are correct.
5. Modify the file path references in the code to match the directory where the downloaded files is.
   Code cells that has file path references:
   - 3rd cell of "Load Image and Labels" `(sample_image, sample_gray = load_image('file path of the test image')`
   - 6th cell of "Load Image and Labels" `(dataset_dir = 'file path of the "images" folder')`
   - 1st cell of "Real-time Face Recognition" `(DATASET_PATH = 'file path of the "images" folder')`
7. Execute the `workshop_cv.ipynb` notebook. Make sure to run the cells from the first one to the last, in order.
