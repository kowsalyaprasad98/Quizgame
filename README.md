[QuizGameCode.txt](https://github.com/kowsalyaprasad98/Quizgame/files/8749159/QuizGameCode.txt)
# Quizgame
This game is a quiz game and the game consists of national symbols of India. I simply wrote this program by using functional calls, flag value.
def Ques(entered,answer):
    attempt=0
    c=1
    global score
    while c and attempt<3:
        if entered.lower()==answer.lower():
            score+=1
            print("Correct Answer")
            c=0
        else:
            if attempt<2:
                entered=input("Sorry Wrong Answer, try again")
            attempt+=1
    if attempt==3:
        print("Correct Answer is:",answer)
score=0
print("Guess National Symbols of INDIA")
entered1=input("What is the national animal of India?")
Ques(entered1,"tiger")
entered2=input("What is the national bird of India?")
Ques(entered2,"peacock")
entered3=input("What is the national fruit of India?")
Ques(entered3,"mango")
entered4=input("What is the national anthem of India?")
Ques(entered4,"jana gana mana")
entered5=input("What is the national aquatic animal of India?")
Ques(entered5,"river dolphin")
entered6=input("What is the national song of India?")
Ques(entered6,"vandemaataram")
entered7=input("What is the national tree of India?")
Ques(entered7,"banyan")
entered8=input("What is the national flower of India?")
Ques(entered8,"lotus")
entered9=input("What is the national river of India?")
Ques(entered9,"ganga")
print("Your Score:",score)
