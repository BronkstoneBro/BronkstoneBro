# Hi there, I'm Bronislav Veprintsev 👋

```python
class AboutMe:
    def __init__(self):
        self.name = "Bronislav Veprintsev"
        self.username = "BronkstoneBro"
        self.location = "Odessa, Ukraine"
        self.role = "Python Developer"
        self.skills = ["Django", "FastAPI", "Docker", "PostgreSQL"]
        self.interests = ["Programming", "Learning English", "Open Source"]
    
    def __str__(self):
        return f"Hello, I'm {self.name}, a passionate {self.role} from {self.location}."

    def currently_working_on(self):
        return "Various Django projects and mastering FastAPI."

    def learning(self):
        return ["Advanced Python", "System Design", "English language"]

    def looking_to_collaborate_on(self):
        return "Open Source Python projects."

    def ask_me_about(self):
        return ["Django", "FastAPI", "Docker"]

    def reach_me_at(self):
        return "https://t.me/bronkstonebro"

me = AboutMe()
print(me)

