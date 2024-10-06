Here's a rewritten version of the provided text:

---

This project features an NLP-based chatbot implemented using a simple fully connected neural network with TensorFlow and TFLearn. The chatbot is trained on a custom dataset specified in a JSON file.

**Prerequisites:**
To get started, you need to install all the required libraries. Run the following command in your terminal:
```bash
pip install -r requirements.txt
```

**Dataset:**
The `dataset.json` file contains the intents that the model is trained on. Each sentence pattern and corresponding response is assigned a specific tag. The model classifies input sentences based on these tags and provides a random response associated with the correct tag. You can modify the JSON file to suit your specific needs.

**PyAudio:**
For Python versions above 3.6, PyAudio isn't directly supported via `pip install pyaudio` and must be installed in a different way.

- **Windows:** 
  Find the appropriate wheel file for your Python version (e.g., for Python 3.7) and install it using:
  ```bash
  pip install <.whl file name>
  ```
  
- **Ubuntu/Linux:**
  You can install PyAudio using:
  ```bash
  sudo apt-get install python3-pyaudio
  ```

**Executing the Code:**
- To train the model, run `trainModel.py`. You can adjust the number of epochs or layers as needed. The current architecture achieves approximately 95% accuracy in predicting tags.
  
- Use `textChatbot.py` to run the text-based chatbot with a GUI.

- Use `voiceBot.py` for a voice recognition-based chatbot.

---  
