# Cold Mail Generator

## Overview
This project leverages Generative AI to efficiently create personalized cold emails. Designed to assist businesses and professionals, the tool enables the crafting of tailored outreach emails by integrating advanced AI models with user-provided input data. By utilizing OpenAI's GPT models, the application ensures high-quality, contextually relevant email content. It is optimized for seamless deployment, easy customization, and provides an intuitive interface for a user-friendly experience.

## Features
- **Personalized Email Generation:** Creates cold emails tailored to the recipient's context.
- **Generative AI Integration:** Utilizes OpenAI's GPT models for high-quality, contextually relevant content.
- **User Input Integration:** Easily incorporates user-provided data, such as industry, purpose, and tone.
- **Customizable Outputs:** Allows tweaking of email structure and tone to meet specific needs.
- **Intuitive Interface:** Simple and user-friendly design for seamless interaction.

## Technologies Used
- **Streamlit:** Provides a lightweight and interactive web interface.
- **Python:** Core programming language for development.
- **OpenAI API:** Enables access to GPT models for generative content creation.
- **Pandas:** Handles data manipulation and processing.
- **Requests:** Facilitates API calls and external integrations.

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/cold-mail-generator.git
   cd cold-mail-generator
   ```

2. **Set Up Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up OpenAI API Key:**
   - Obtain an API key from [OpenAI](https://openai.com/api/).
   - Create a `.env` file in the project root and add your key:
     ```env
     OPENAI_API_KEY=your-api-key
     ```

5. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

## Usage
1. **Provide Input:** Enter relevant details such as target audience, purpose, and tone.
2. **Generate Email:** Click the "Generate" button to create a personalized email.
3. **Review and Edit:** Adjust the generated content as needed.
4. **Export or Copy:** Save the email or copy it to your clipboard for use.

## Directory Structure
```
cold-mail-generator/
├── data/                # Example input data and templates
├── src/                 # Source code for the application
│   ├── components/      # UI components
│   ├── logic/           # Core email generation logic
│   └── utils/           # Helper functions
├── tests/               # Test cases for the application
├── requirements.txt     # Dependencies
├── app.py               # Main Streamlit application file
└── README.md            # Project documentation
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Thanks to OpenAI for providing the GPT models.
- Inspired by the need for efficient and effective outreach tools.

## Contact
For questions, suggestions, or collaboration opportunities, please reach out at (https://www.linkedin.com/in/krishnaa-mishra/)
