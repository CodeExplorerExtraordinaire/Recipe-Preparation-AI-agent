# AI Recipe Assistant

The AI Recipe Assistant is a smart, AI-powered cooking companion that helps users create personalized recipes using the ingredients they already have at home. It leverages advanced **Retrieval-Augmented Generation (RAG)** techniques to generate meal suggestions tailored to dietary preferences, available ingredients, cooking time, and serving size.

## 🔍 Overview

Designed to simplify meal planning and reduce food waste, this assistant enables users to input whatever groceries they have on hand and receive step-by-step cooking instructions in return. It supports a wide range of dietary requirements such as vegetarian, vegan, gluten-free, and keto, and can offer substitutions for unavailable ingredients.

This project is ideal for:
- Home cooks looking for quick solutions
- Students with limited pantry supplies
- Busy professionals who want to save time
- Anyone aiming to cook smarter and reduce waste

## ✨ Key Features

- Personalized recipe suggestions based on user input
- Ingredient substitutions and dietary adaptation
- Step-by-step cooking instructions
- Support for multiple diets and preferences
- Time- and serving-based recipe adjustments
- Designed to minimize food waste

## 🚀 How It Works

1. User inputs the ingredients they have.
2. Assistant asks for dietary needs, servings, and time limits.
3. A RAG-based model retrieves relevant recipes and adapts them to the user's input.
4. Output includes:
   - Recipe title
   - Ingredient list
   - Preparation steps
   - Cooking tips and optional ingredient swaps

## 🛠️ Technologies Used

- **Natural Language Processing (NLP)**
- **Retrieval-Augmented Generation (RAG)**
- **AI/ML Backend** (e.g., watsonx.ai, custom LLMs)
- **Optional Frontend** (React, Flask, or Streamlit)
- **Markdown for output formatting**

## 🧪 Sample Input

```
Ingredients: eggs, tomatoes, onions, bread
Diet: vegetarian
Time: under 30 minutes
Servings: 2
```

**Output:**  
A vegetarian tomato-egg sandwich recipe with step-by-step instructions and suggested swaps for missing items like cheese or lettuce.

## 📦 Folder Structure (Suggestion)

```
ai-recipe-assistant/
├── README.md
├── /docs
│   └── AI_Recipe_Assistant_Documentation.pdf
├── /data
│   └── ingredients_database.json
├── /models
│   └── rag_model_config.yaml
├── /notebooks
│   └── recipe_generation_demo.ipynb
├── /frontend
│   └── (Optional UI files)
└── /examples
    └── sample_inputs_outputs.md
```

## 📋 Future Improvements

- Voice input and output for hands-free cooking
- Integration with grocery APIs for real-time inventory
- Multilingual recipe support
- Nutrition estimation and meal planning features

## 📝 License

This project is open-source and available for educational and research purposes. If used commercially, please ensure compliance with the licenses of any third-party tools or models.

## 🙌 Contributing

Contributions are welcome! If you’d like to suggest improvements, fix bugs, or add new features, feel free to fork the repository and create a pull request. Please ensure your code is well-documented and follows best practices.

## 📬 Contact

For questions, feedback, or collaboration opportunities, feel free to open an issue or contact the project maintainers directly via GitHub.
