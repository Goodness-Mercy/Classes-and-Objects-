# Classes-and-Objects-
Zuri Task on Classes and Objects 


class Student:
    # [assignment] Skeleton class. Add your code here
    def __init__(self, name, age, track, score):
        self.name=name
        self.age=age
        self.track=track
        self.score=score

    def change_name(self):
        Bob.name="Peter"
    def change_age(self):
        print("My age is 34")
    def get_score(self):
        print(Bob.score)
    def add_track(self):
        Bob.track.append("FE")
        print(Bob.track)






Bob = Student("Bob",26,["FE","BE"],20.90)

print("My name is " +""+ Bob.name)
print("My age is "+""+ str(Bob.age))
print("track value "+""+ str(Bob.track))
print("score is "+""+ str(Bob.score))






# Expected methods
Bob.change_name()
Bob.change_age()
Bob.get_score()
Bob.add_track()
