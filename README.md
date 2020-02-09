# BirdWords
# word jumble
score = 0
print("welcome to word jumble!! today's theme is BIRDS!")
print("if you guess the word correctly without a hint, you recieve 2 points.")
print("if you guess the word correctly with a hint, you recieve 1 point.")
print("if you guess the word incorrectly, you recieve 0 points.")
print("guess what the scrambled word is: rparto")
word1 = "parrot"
hint = input("need a hint? (yes or no)")
if hint == "yes":
    print("squawk squawk and colorful")
elif hint == "no":
    print("okay!")
answer1 = input("guess the word")
if answer1 == word1 and hint == "no":
    score += 2
    print("nice! your score is", score)
elif answer1 == word1 and hint == "yes":
    score += 1
    print("good! your score is now:", score)
elif answer1 != word1:
    print("Good try, but incorrect. Your score stays the same.")
    print("the word was", word1)

print("guess what the scrambled word is: eugnipn")
word2 = "penguin"
hint2 = input("need a hint? (yes or no)")
if hint2 == "yes":
    print("a cold bird")
elif hint2 == "no":
    print("okay!")
answer2 = input("guess the word")
if answer2 == word2 and hint2 == "no":
    score += 2
    print("nice! your score is", score)
elif answer2 == word2 and hint2 == "yes":
    score += 1
    print("good! your score is now:", score)
elif answer2 != word2:
    print("Good try, but incorrect. Your score stays the same.")
    print("the word was", word2)

print("guess what the scrambled word is: gnofilam")
word3 = "flamingo"
hint3 = input("need a hint? (yes or no)")
if hint3 == "yes":
    print("he really do be pink")
elif hint3 == "no":
    print("okay!")
answer3 = input("guess the word")
if answer3 == word3 and hint3 == "no":
    score += 2
    print("nice! your score is", score)
elif answer3 == word3 and hint3 == "yes":
    score += 1
    print("good! your score is now:", score)
elif answer3 != word3:
    print("Good try, but incorrect. Your score stays the same.")
    print("the word was", word3)

if score == 6:
    print("Final Score:", score, "out of 6")
    print("You're a bird expert!! You got all of the words with no hints!")
elif score == 0:
    print("Final Score:", score, "out of 6")
    print("You're a disgrace. You know nothing about birds.")
else:
    print("Final Score:", score, "out of 6")
    print("You're a decent bird word un-jumbler, I suppose.")
