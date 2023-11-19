### Hi there 👋

```python
class DataScientist(Human):
    def __init__(self, name, interests, expertise, languages):
        super(DataScientist, self).__init__(name, interests)
        assert isinstance(languages, list) and len(languages) > 0
        self.expertise = expertise
        self.languages = languages


me = DataScientist(
    name="Magnus",
    expertise=[
        "Machine Learning",
        "Deep Learning",
        "Reinforcement Learning
        "Data science",
        "Software Development (SOLID, TDD, ...)",
    ],
    interests=[
        "Skiing",
        "Hiking",
        "Cooking",
        "Coding",
    ],
    languages=[
        "Python",
        "Swift",
        "C++",
        "German",
        "English",
        "Catalan",
    ]
)

- 🔭 I’m currently working on <<Deep Learning for Additive Manufacturing>>
- 📫 How to reach me: [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/mglasder/)


