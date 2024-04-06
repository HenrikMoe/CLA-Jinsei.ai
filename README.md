# PixelCLA-ShipyardJinsei
Spreadsheet data mapping and automation services with the Pixel assistant.

# Shipyard + Jinsei.ai

Various campaign media data transformation and validation solutions powered by Jax Tensorflow and GPT/Grok. 

## How Jinsei.ai solutions will help Shipyard:

It is tediuos to hardcode your data transformations for every accounting statement positional format in the world. 

# CLA/PIXEL Solutions 

## 1) Pixel Turbocharged: Upload multiple files with automated formatting for mutliple spreadsheets

### Upload multiple files within Pixel chat and have them automtically formatted and synced with the CLA tool suite. 

### Assistant can take multiple file uploads and output the files to the CLA tool suite in a standardized format.

- Boilerplate Prompt (query syntax) Training: https://github.com/HenrikMoe/jinsei.ai-sbrm-rdf-llm-UI/blob/main/backend/server.js
- Boilerplate Classification Training: https://github.com/PortalToBlockchainOrganization/CryptoCountAI/blob/master/typeModelResult1.py
- Integrate Shipyard DB Queries to Taxonomy Element pairings 
- Needs collections of client ROI reports required by Shipyard clientele


## 2) Multi-SpreadSheet Data Formatting Automation

- excel sheet content to database mapping service 
- needs investment statements sets from compatible and not compatible excel sheets 

Sequence-to-Sequence TF JAX service for automating multi-spreadsheet content position format standardization.

### Service Interface/DevOps

Shipyard container routing, REST transfer protocol preference.  

### Service StartUp: Set Env & Run Models

Boilerplate Sequence to Sequence model: https://github.com/HenrikMoe/LodgeIt-JinseiAI/edit/main/xmlSeq2Seq.py

edit this

startup:
Navigate to the directory where you want to create the virtual environment
```linux
# cd (project root) 
```
Create a virtual environment (you can choose any name, here we use "venv")
```linux
python3 -m venv venv
```

Activate the virtual environment
```linux
source venv/bin/activate
```

Install required packages
```linux
pip install numpy TFANN matplotlib scikit-learn tensorflow
```

Make sure you are in the directory containing your script
```linux
cd (rn the csv and the py file are in Machine)
```
Run the script
```linux
python chat3deriv.py
```

Training Data ReadMe: https://

```python
# Training data organization
training_data = [
    {"input_xml": "<input_xml_1>", "target_xml": "<target_xml_1>"},
    {"input_xml": "<input_xml_2>", "target_xml": "<target_xml_2>"},
    # Add more examples as needed
]

# Extract input and target sequences from training data
input_xml_data = [example["input_xml"] for example in training_data]
target_xml_data = [example["target_xml"] for example in training_data]

```



