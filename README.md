영단어 퀴즈

e = [ "happy" , "sad" , "peace" , "angry" ]
    
d = { "fruit" :["apple", "orange"] ,
     "vegetale" : "tomato",
     "grain" : "rice" ,
      "emotion" : ["happy" , "sad" , "peace" , "angry"]}
print("퀴즈게임을 시작합니다.")
for i in d:
    a = input(f"{i}에 해당하는 영단어를 쓰세요")
    if a == d[i]:
        print("정답입니다")
        c = c + 1
    else:
        print("오답입니다")
