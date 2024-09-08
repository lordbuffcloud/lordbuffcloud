## Installation

1. Clone the repository:
   ```
   git clone https://github.com/lordbuffcloud/cr1m1nal-glxy.git
   cd cr1m1nal-glxy
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     .\venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. Set up your environment variables in a `.env` file (see Configuration section for details).

6. Download and set up LLM Studio:
   - Download LLM Studio from the official website.
   - Install LLM Studio following the provided instructions.

7. Download the Hermes model:
   - Open LLM Studio.
   - Navigate to the model download section.
   - Search for and download the Hermes model.

8. Run the LLM Studio server:
   - Open LLM Studio.
   - Load the Hermes model.
   - Start the server following LLM Studio's instructions. (keep port 1234)

9. Run the bot:
   ```
   python glxy_uncensored.py
   ```