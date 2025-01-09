## AI/NLP_TV_Series-Analysis-System
![image](https://github.com/user-attachments/assets/12d73eb9-d0ed-41c0-b752-7fa7e24ce99d)

### Problem Statement
The AI/NLP TV Series Analysis System addresses the challenge of analyzing TV series content by classifying themes, building character networks, and providing a chatbot for fan interaction. It processes scripts and related materials to identify recurring themes, maps character relationships into dynamic networks, and enables fans to engage with their favorite characters through an interactive chatbot, bridging the gap between storytelling and audience immersion.


## Project Structure

### Main Components:

1. **character_chatbot**
   - `__init__.py`: Initializes the chatbot module.
   - `character_chatbot.py`: Implements the chatbot functionality.
   - `character_chatbot_development.ipynb`: Jupyter notebook for chatbot development and testing.

2. **character_network**
   - `__init__.py`: Initializes the character network module.
   - `character_network_generator.py`: Generates a network graph of character relationships.
   - `character_network_generator.ipynb`: Jupyter notebook for developing the character network generator.
   - `named_entity_recognizer.py`: Identifies and extracts named entities from the text.
   - `naruto.html`: Sample visualization of the character network.

3. **data**
   - `Subtitles/`: Contains subtitle files for processing.
   - `download_link.txt`: Links to additional data resources.
   - `jutsus.jsonl`: JSONL file containing jutsu data.
   - `naruto.csv`: Dataset for the Naruto TV series.

4. **scraper**
   - `jutsu_data_scraper.py`: Scrapes data for jutsu-related information.

5. **stubs**
   - `ner_output.csv`: Output from the named entity recognizer.
   - `theme_classifier_output.csv`: Output from the theme classifier.

6. **text_classification**
   - `__init__.py`: Initializes the text classification module.
   - `cleaner.py`: Preprocesses and cleans text data.
   - `custom_trainer.py`: Custom training utilities for text classifiers.
   - `jutsu_classifier_development.ipynb`: Jupyter notebook for developing the jutsu classifier.
   - `jutsu_classifier.py`: Classifies text into jutsu-related categories.
   - `training_utils.py`: Helper functions for training text classifiers.

7. **theme_classifier**
   - `__init__.py`: Initializes the theme classifier module.
   - `theme_classification_development.ipynb`: Jupyter notebook for theme classification development.
   - `theme_classifier.py`: Classifies text into themes.

8. **utils**
   - Utility functions and scripts used across the project.

9. **Application Files**
   - `gradio_app.py`: Gradio-based application for user interaction.
   - `requirements.txt`: Python dependencies for the project.
   - `.gitignore`: Files and folders to ignore in version control.
   - `README.md`: Project documentation.

## Features

- **Theme Classification:** Identifies recurring themes in TV series scripts.
- **Character Network Generation:** Builds a dynamic graph of character relationships.
- **Interactive Chatbot:** Allows fans to chat with their favorite characters.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Gradio application:
   ```bash
   python gradio_app.py
   ```

## Usage

- Use the **Gradio app** to interact with the chatbot and explore the system's capabilities.
- Process TV series scripts and subtitles using the provided modules to classify themes and generate character networks.

## Data Sources

- Subtitles and datasets provided in the `data` folder.
- Additional data can be scraped using the `scraper` module.

