# RAG with Chainlit for PDF QA

**No Installation Required:**

Users can directly run the application from the provided Colab link without installing any software or dependencies.

## Running the Application:

1. **Access the Colab Notebook:** Open the following link in your web browser: [[TGH] RAG_Langchain_Project_V2](https://colab.research.google.com/drive/1lNhhk5paglaivOQ-IAShkBynYkGkZlKN#scrollTo=kjQzxAYT4ZFh)

2. **Run the Cells:**

   a. **Enable Colab Runtime Execution:** Click the "Runtime" menu in the top toolbar and select "Run all cells".

   b. **Observe the Output:** The notebook will execute the code cells, and the application will launch automatically.



## Explanation of Code Cells:

**Cell 1:** This cell lists the Python libraries needed to run the application.

1. Purpose: To install the required dependencies for the project.

2. Significance: Ensures that users have the necessary libraries to run the code without encountering installation errors.

**Cell 2:** This cell contains the source code for the Chainlit application, defined in the `app.py` file.

1. Purpose: To define the Chainlit application's functionality, including user interface elements, event handling, and logic for processing uploaded files, generating responses, and interacting with the RAG model.

2. Significance: This cell is the core of the application, enabling users to upload files, ask questions, and receive answers.

**Cell 3:** This cell likely contains code for configuring and starting the ngrok tunnel.

1. Purpose: To create a secure tunnel that allows users to access the locally running Chainlit application from their web browsers.

2. Significance: Enables remote access to the application without requiring users to install or configure anything on their own machines.

**Cell 4:** This cell runs the Chainlit application using the `chainlit run app.py` command.

1. Purpose: To launch the Chainlit application within the Colab notebook environment.

3. Significance: Initiates the interactive user interface and starts serving the application.

**Notes**:
- _Cell 3 - ngrok Authentication Token_: Replace `2ipkWlfoUMwqOkYuSxB7PLjHkBj_6vidSqzTVg8mFzHJs3rTA` with your own ngrok authentication token (go to [https://ngrok.com/](https://ngrok.com/)).

- _Access the Application_: After running cell 4, copy and paste the public URL displayed in the cell 3's output into your web browser to access the Chainlit application.

## Using the Application:

1. **Upload a PDF or text file:** Click the upload button and select your file.
2. **Ask a question:** Once the file is processed, type your question about the uploaded content in the chat interface.
3. **Get the answer:** The application will use the RAG model to retrieve relevant information from the document and generate a response to your question.
