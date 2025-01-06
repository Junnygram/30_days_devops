Here’s a rephrased version for your README:

---

### Project Setup: Weather Dashboard

Follow these steps to set up the Weather Dashboard project:

1. **Create the Project Directory**  
   Run the following commands to set up the project structure:

   ```bash
   mkdir weather-dashboard
   cd weather-dashboard
   mkdir src tests data
   touch src/__init__.py src/weather_dashboard.py requirements.txt
   ```

2. **Set Up the `.gitignore` File**  
   Add the following entries to the `.gitignore` file to exclude unnecessary files:

   ```bash
   echo "-env" >> .gitignore
   echo "__pycache__/" >> .gitignore
   echo "*.zip" >> .gitignore
   ```

3. **Add Project Dependencies**  
   Add the required libraries to `requirements.txt`:

   ```bash
   echo "boto3==1.26.137" >> requirements.txt
   echo "python-dotenv==1.0.0" >> requirements.txt
   echo "requests==2.28.2" >> requirements.txt
   ```

4. **Install Dependencies**  
   Use the following command to install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. **(Optional) Using a Virtual Environment**  
   If you're using a virtual environment, activate it and install the dependencies:

   ```bash
   source "/Users/hostname/Desktop/30 days/.venv/bin/activate"   //not necessary
   python -m pip install -r requirements.txt
   ```

6. **Run the Weather Dashboard**  
   Execute the script:

   ```bash
   python3 src/weather_dashboard.py
   ```

7. **Set Up an API Key**
   - Create an account at [OpenWeatherMap API](https://openweathermap.org/api).
   - Generate an API key for your project.
   - Add the API key to a `.env` file for secure usage in your script.

---
