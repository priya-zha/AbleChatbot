# AbleChatbot

**How to Run**

**1. Open the File in Google Colab**

     Open the notebook file in Google Colab.

     Please run the cells in order.

     
**2. Install Required Packages**

     Once you reach the last cell that installs all the packages:

     pip install --upgrade --force-reinstall llama-index

     Colab will ask you to restart the session. Click on "Restart" to proceed.


**3. Prepare the Data Directory**

     Create a directory in Colab with the name 'Able'

     Add the file data.pdf inside the Able directory. This file contains the necessary data for the chatbot. Then run the cells in the order.


**4. Authenticate with Hugging Face**

     Once you reach to the cell that asks for the Hugging Face access token, run the cell:

     from huggingface_hub import notebook_login
     notebook_login()


     If you don't have a Hugging Face account, create one at Hugging Face.

     Click on your profile icon, navigate to Access Tokens, and create a new token.

     Copy the token and paste it when prompted in the Colab cell.

     
**5. Run the Remaining Cells**

     Execute the other cells in order.
     

**6. You have two ways to interact with the chatbot:**

     Python CLI: Use the command-line interface to talk with the chatbot.

     Gradio Interface: A web-based interface to interact with the chatbot.


**7. Screenshots of Chatbot Results**

     I have provided screenshots of the chatbot’s results, named result1 and result2.

     You can find them in the Colab notebook for reference.
