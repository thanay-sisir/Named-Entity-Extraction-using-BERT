# Named-Entity-Extraction-using-BERT

## Overview
This project is a Named Entity Recognition (NER) system developed using BERT (Bidirectional Encoder Representations from Transformers). The system identifies and classifies entities like person names, organizations, locations, and more from text inputs. The model is fine-tuned for both NER and Part-of-Speech (POS) tagging using a multi-task loss function.
## Project Structure
![Screenshot 2025-01-11 182418](https://github.com/user-attachments/assets/ec0e70e2-e60f-444b-90dc-448c59296cef)
# Inner files
![Screenshot 2025-01-12 010708](https://github.com/user-attachments/assets/b37889ef-8813-4b72-96e9-cceeca043f16)
![Screenshot 2025-01-12 010656](https://github.com/user-attachments/assets/15c93fe8-1fd8-42f8-b7ac-5e87176a77e3)
![Screenshot 2025-01-12 010646](https://github.com/user-attachments/assets/00c7cd84-fd20-486c-8a40-c3d68833e011)
# BERT Model
![image](https://github.com/user-attachments/assets/49181b36-30a0-4568-b943-eb7a8494699e)

* train.py: Script for training the model with NER and POS tagging.
* predict.py: Script for making predictions with the trained model.
* model.py: Defines the BERT-based architecture for entity recognition.
* engine.py: Training and evaluation loop implementation.
* meta.bin: Encoded metadata for label mapping of NER and POS tags.
* ner_dataset.csv: Dataset used for training and validation.
* requirements.txt: Dependencies for running the project.
## Dataset Overview
* Dataset Used: ner_dataset.csv
* Contains tokens, Part-of-Speech tags, and Named Entity tags for each word.
* Data Preprocessing:
 ![Screenshot 2025-01-12 000359](https://github.com/user-attachments/assets/e4e3179a-eb9c-4a3f-9f09-3f4cd31c738e)
![Screenshot 2025-01-12 000406](https://github.com/user-attachments/assets/8a8102cf-e55b-4cf2-bf84-fb360dbd0621)
* Replaced missing values in tokens with empty strings.
* Forward-filled missing sentence IDs.
* Encoded categorical labels for POS and NER tags using LabelEncoder.

# Final Otutput 
![Screenshot 2025-01-12 000406](https://github.com/user-attachments/assets/4ed94324-54ef-44e7-92dd-6ad3f248713f)
![Screenshot 2025-01-12 000813](https://github.com/user-attachments/assets/0352ac99-7702-4836-87d2-fd1020fa4f2b)
![Screenshot 2025-01-12 012904](https://github.com/user-attachments/assets/f09ed024-a71f-4e28-9532-6dc4f17ecc88)

