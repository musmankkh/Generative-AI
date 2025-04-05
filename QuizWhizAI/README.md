# QuizWhiz AI - Intelligent Question Generation System

QuizWhiz AI is an advanced question generation system that uses state-of-the-art NLP models to automatically create educational questions from any text input. Powered by T5 transformer models, it can generate high-quality questions suitable for quizzes, tests, and study materials.

## Features

- **Multiple Model Support**: Choose between base question generator or SQuAD-fine-tuned model
- **Adjustable Question Count**: Generate 1-10 questions from input text
- **Quality Optimization**: Advanced generation parameters for better questions
- **Easy-to-Use Interface**: Simple Gradio web interface
- **Educational Focus**: Specifically designed for learning applications

## Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/musmankkh/Generative-AI
   cd quizwhiz-ai
   ```


2. Download NLTK data:
   ```python
   python -c "import nltk; nltk.download('punkt')"
   ```

## Usage

1. Run the application

2. Input your text or URL, select options, and click "Generate Questions"

3. View and copy your generated questions

## Models Available

| Model Type | Description | Best For |
|------------|-------------|----------|
| `base` | General purpose question generator | Quick question generation |
| `squad` | Fine-tuned on SQuAD dataset | Higher quality educational questions |

## API Usage

You can also use QuizWhiz as a Python library:

```python
from quizwhiz import generate_questions

text = "The solar system consists of the Sun and eight planets."
questions = generate_questions(text, num_questions=3, model_type="squad")
print(questions)
```

## Configuration

Customize the behavior by modifying `config.yaml`:

```yaml
generation:
  max_length: 256
  temperature: 0.8
  top_k: 50
  top_p: 0.95
  no_repeat_ngram_size: 3
```

## Performance Notes

- First run will download model weights (several GB)
- GPU recommended for best performance
- Reduce `num_questions` if experiencing memory issues

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Maintainer: Muhammad Usman Asghar
Email: 42khan0@gmail.com 
Project Link: [https://github.com/musmankkh/Generative-AI](https://github.com/musmankkh/Generative-AI)

## Acknowledgments

- Hugging Face for the Transformers library
- Google for the T5 model architecture
- SQuAD dataset providers
- Gradio for the interface framework
```

Would you like me to elaborate on any of these future features or documentation files? I can provide more detailed specifications for any of the proposed enhancements.