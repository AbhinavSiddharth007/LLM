# LLM
This is a small scale LLM (GPT) trained on Wizzard Of Oz 

## Why have we seclecd this as our project :
###1. Alignment with Our Interests
We are deeply interested in artificial intelligence and natural language processing. Python serves as the foundational language for building AI products, particularly in machine learning and deep learning applications. This project allows us to explore these areas hands-on.

###2. Application of Academic Learning
This project builds upon the theoretical knowledge and practical skills we've acquired through our previous courseworks . It represents a practical synthesis of concepts and practical things taught by our instructors.

###3.Inspiration of the project :
Our work is inspired by Andrej Karpathy's educational YouTube tutorial series on building language models from scratch, specifically his "nanoGPT" implementation. This educational resource provided an excellent foundation for understanding the core mechanics of transformer-based models.

### Technical Implementation
Technology Stack

PyTorch: Primary deep learning framework for model architecture and training
NumPy: Numerical computations and array operations
tiktoken (OpenAI): Tokenization library for text processing
Custom implementations: Based on concepts from recent research papers in the field

Design Philosophy
We have intentionally kept the implementation straightforward and accessible, focusing on clarity and educational value rather than production-scale complexity. This approach makes the codebase easier to understand and modify for learning purposes.
Training Data
The model is trained on "The Wizard of Oz" by L. Frank Baum, providing a rich, narrative text corpus that demonstrates the model's ability to learn language patterns, story structure, and contextual relationships.
Project Structure
├── data/               # Training text corpus
├── model/              # GPT architecture implementation
├── tokenizer/          # Text tokenization utilities
├── training/           # Training scripts and configurations
└── inference/          # Text generation and model evaluation
Key Features

Character or token-level text generation
Transformer-based architecture with self-attention mechanisms
Configurable hyperparameters (layers, heads, embedding dimensions)
Training visualization and loss tracking
Interactive text generation interface

Learning Outcomes
Through this project, we have gained practical experience in:

Implementing transformer architectures from scratch
Understanding attention mechanisms and their role in language modeling
Training neural networks with PyTorch
Working with text data preprocessing and tokenization
Debugging and optimizing deep learning models

Acknowledgments

Andrej Karpathy for the educational nanoGPT tutorial
Our instructors for providing the theoretical foundation
The open-source AI community for tools and resources
