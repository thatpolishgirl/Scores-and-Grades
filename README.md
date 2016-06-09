# Scores-and-Grades
print 'Scores and Grades'
for count in range(1, 11):
    print 'Score:'
    grade = input()
    if grade in range(60, 70):
        print 'Your grade is D'
    elif grade in range(70, 80):
        print 'Your grade is C'
    elif grade in range(80, 90):
        print 'Your grade is B'
    elif grade in range(90, 101):
        print 'Your grade is A'
print 'End of program. Bye!'
