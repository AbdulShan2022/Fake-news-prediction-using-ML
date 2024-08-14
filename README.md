<h1>ML Fake News Detection Using Logistic Regression</h1>

<h2>Overview</h2>

<p>This project aims to develop a machine learning model that predicts whether a news article is fake or real based on textual data. The model is trained using a logistic regression algorithm and utilizes a <code>test.csv</code> file containing the news data for predictions. The project is implemented in Python and leverages Streamlit for an interactive web application.</p>

<h2>Features</h2>

<ul>
<li><strong>Logistic Regression Model</strong>: A simple yet effective model for binary classification tasks like fake news detection.</li>
<li><strong>Streamlit Web App</strong>: A user-friendly interface for uploading data, viewing predictions, and interacting with the model.</li>
<li><strong>Preprocessing</strong>: The project includes necessary text preprocessing steps such as stopword removal, and vectorization.</li>
</ul>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>

<p>Ensure that you have Python installed on your machine. This project is compatible with Python 3.x.</p>

<h3>Setup Virtual Environment</h3>

<ol>
<li><p><strong>Create a Virtual Environment</strong>:
<code>bash
python3 -m venv venv
</code></p></li>
<li><p><strong>Activate the Virtual Environment</strong>:</p>

<ul>
<li>On Windows:
<code>bash
venv\Scripts ctivate
</code></li>
<li>On macOS/Linux:
<code>bash
source venv/bin/activate
</code></li>
</ul></li>
<li><p><strong>Upgrade pip</strong>:
<code>bash
pip install --upgrade pip
</code></p></li>
</ol>

<h3>Install Dependencies</h3>

<p>Install the required Python packages using the following command:</p>

<p><code>bash
pip install -r requirements.txt
</code></p>

<h3>Running the Project</h3>

<ol>
<li><p><strong>Prepare the Data</strong>:</p>

<ul>
<li>Ensure you have a <code>test.csv</code> file containing the news articles you want to test the model on.</li>
<li>Place this file in the project directory.</li>
</ul></li>
<li><p><strong>Run the Streamlit App</strong>:
<code>bash
streamlit run app.py
</code></p>

<p>This will launch a web browser window with the Streamlit interface, where you can upload your <code>test.csv</code> file and view the predictions.</p></li>
</ol>

<h3>Project Structure</h3>

<ul>
<li><strong>app.py</strong>: The main file containing the Streamlit app code.</li>
<li><strong>model.py</strong>: Contains the logistic regression model and preprocessing functions.</li>
<li><strong>requirements.txt</strong>: A list of Python packages required to run the project.</li>
<li><strong>test.csv</strong>: The CSV file used for testing the model (you'll need to decompress it in the content directory).</li>
<li><strong>venv/</strong>: The virtual environment directory (created after setting up the project).</li>
</ul>

<h3>Customization</h3>

<ul>
<li><strong>Configuring the Model</strong>: You can tweak the logistic regression parameters in <code>model.py</code> to improve accuracy.</li>
<li><strong>Adding New Features</strong>: Feel free to add more preprocessing steps or experiment with different machine learning algorithms.</li>
</ul>

<h2>Contributing</h2>

<p>Contributions are welcome! If you have ideas to improve the project or encounter issues, feel free to submit a pull request or open an issue on GitHub.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>
