# Environmental Awareness App

Environmental Awareness App is a Streamlit-based application that provides educational content on sustainability and ecology. It uses AI to deliver customized information on various environmental topics, adapting to different content types and difficulty levels.

## Features

- Interactive environmental education with AI
- Customizable environmental topics and content types
- Adjustable difficulty levels (Beginner, Intermediate, Advanced)
- Support for various AI models (OpenAI and Ollama)
- Conversation saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/Environmental-Awareness-App-Streamlit100.git
   cd environmental-awareness-app
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3. Enter your name and configure your environmental education preferences in the sidebar:
   - Select environmental topics of interest
   - Choose the content type
   - Set the difficulty level

4. Start asking questions about environmental topics or request specific information

5. Engage with the AI to learn about sustainability and ecology

## Customization

- Modify the `ENVIRONMENTAL_TOPICS` and `CONTENT_TYPES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus
- Add new content types or modify existing ones to suit different learning styles

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
