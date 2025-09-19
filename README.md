# Multi_Question_Color_Recommender
This project uses Openai API key to create a complete color recommender system from scratch using a json data for a huge paint industry company. This project is designed for India Specific Clients

### The main.py
The main.py code creates a python pipeline that uses different combination of question answers from user and according to the answers it gives color recommendations with an explanation of why this colors are recommended. However, this process is not dynamic. By dynamic I mean the user needs to write their choice every time. So, we need a system in which the user will select suitable options only and the questions will come autometically. 

### The question_color_recommender.py
To overcome the previous issue where the user must write their answers, this file is developed along with the `app.py` to make the process more streamline from the user perspective. Now, one question will come with its different options in a multiple choice format. Thus 5 questions will appear. Once, all the five questions are answered, the user will autometically see the top 3 suggested colors with reasons like how the user selection helps the recommendation engine to find the colors and the reason behind selection of three colors.
