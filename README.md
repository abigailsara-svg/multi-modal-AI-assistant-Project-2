# Multi-Modal AI Assistant

An advanced AI assistant capable of understanding both text and image inputs using Computer Vision and NLP techniques.

## Features

- Multi-modal AI interaction
- Image understanding using BLIP model
- Conversational memory
- Context awareness
- Intelligent reasoning engine
- Response validation
- Ambiguity handling
- Follow-up question support

## Technologies Used

- Python
- Flask
- Transformers
- PyTorch
- BLIP Image Captioning Model
- HTML/CSS

## Project Structure

```bash
Project-2/
│
├── app.py
├── requirements.txt
├── README.md
│
├── memory/
│   └── conversation_memory.py
│
├── reasoning/
│   ├── decision_engine.py
│   └── validator.py
│
├── models/
│   └── vision_model.py
│
├── templates/
│   └── index.html
│
├── uploads/
│
├── static/
│
└── venv/
```


## Installation

1. Clone repository

```bash
git clone <repository-link>
```

2. Create virtual environment

```bash
python -m venv venv
```

3. Activate virtual environment

Windows:
```bash
.\venv\Scripts\Activate.ps1
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

5. Run project

```bash
python app.py
```

## Example Usage

- Upload an image
- Ask questions like:
  - What animal is this?
  - Where is it?
  - What is happening?

The AI assistant remembers previous context and answers intelligently.

## Internship Task Objectives Achieved

- Multi-modal understanding
- Contextual reasoning
- Conversational memory
- Intelligent decision-making
- Evidence-based responses
- Validation handling

## Author

Abigail Sara David
