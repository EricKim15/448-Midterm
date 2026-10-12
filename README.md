# 448-Midterm

In this project, we examined whether responses from three AI systems; ChatGPT, Google Gemini, and Perplexity, could be distinguished based on their response patterns. We submitted the same 100 questions about 2025 fantasy football statistics and leaders to each system, collecting 300 responses. Using these responses, we developed code in Google Colab to predict which system generated each answer and evaluate how accurately the systems could be identified.

Features & Capabilities:
   - Questions and Response Excel Spreadsheet: Organizes 100 Questions and the corresponding AI’s response
   - Tokenizer: Converts response text into tokens for processing and analysis.
   - Response Analysis: Examines text patterns that may help distinguish the three AI systems.
   - Classifier for AI source predictions: Predicts which AI system generated a response.
   - Performance Evaluation: Measures classification accuracy and identifies which AI systems are most frequently confused. 


Installation Instructions:
   1. Open Google collab  and sign with with your account
   2. Upload the project’s notebook or use an accessible link provided
   3. Import all required Python libraries, and run the established cells
   4. Upload the data set containing the labeled response from ChatGPT, Gemini, and Perplexity
   5. If necessary, update file path for the data set
   6. Run each cell to process the responses, train the classifier, and evaluate the ability to evaluate the AI based on the given response

Usage Example: 

Configuration Details: As this project runs in Google Colab using Python, before running the notebook, set the dataset’s file path and specify the columns containing the response text and AI system labels. Model settings, such as the training and testing split and random seed, should match those defined in the notebook.
