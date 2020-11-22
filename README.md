# LargestDigitDectector
Classifier that detects the largest digit in an image

Ran on Google Colab
## How to Run:
1. Upload all the data in the Google Colab local env
2. Run all the code blocks in **Data Preprocessing** section, which will probably cause the RAM to approach its limit, so the preprocessed data is saved
3. Restart the runtime, run the imports code block, and this time, start running the notebook from the **Reload Preprocessed Data** section up to the **Train** section
5. After loading the preprocessed data, creating the model and training it, the RAM will probably approach its limit again, so the model itself is saved
6. Restart the runtime, run the imports code block, and this time, start running from the **Predictions** block.
4. Run the rest of the notebook in normal order

The predictions will be automatically saved as a csv, and zipped.
