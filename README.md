# AI_Meets_Olfaction
Using VOC's to digitize scent and give technology- a sense of smell.  Our product Tracks Missing Individuals, Contraband and Explosives all using Artificial Intelligence and Google Cloud Platform.


project_structure/
│
├── config/
│   ├── __init__.py
│   └── config.py                  # Project configuration
│
├── data/
│   ├── __init__.py
│   ├── preprocessing.py           # Data preprocessing pipeline
│   └── dataset.py                 # Custom dataset class
│
├── models/
│   ├── __init__.py
│   └── voc_classifier.py          # PyTorch Model Architecture
│
├── training/
│   ├── __init__.py
│   ├── trainer.py                 # Model training script
│   └── vertex_ai_training.py      # Vertex AI training configuration
│
├── deployment/
│   ├── __init__.py
│   ├── model_deployment.py        # GCP Model Deployment
│   └── inference.py               # Model Inference Wrapper
│
├── services/
│   ├── __init__.py
│   ├── gemini_llm.py              # Gemini LLM Interaction
│   └── google_maps_integration.py # Google Maps Real-time Tracking
│
├── dashboard/
│   ├── __init__.py
│   └── firebase_dashboard.py      # Firebase Dashboard Configuration
│
├── requirements.txt               # Project Dependencies


