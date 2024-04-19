### Hi there 👋

```python
class DeepLearningEngineer(Human):
    def __init__(self, name, interests, expertise, languages):
        super(DeepLearningEngineer, self).__init__(name, interests)
        assert isinstance(languages, list) and len(languages) > 0
        self.expertise = expertise
        self.languages = languages

    def working_on() -> str:
        return "Deep Learning for Additive Manufacturing"


me = DataScientist(
    name="Magnus",
    expertise=[
        "Machine Learning",
        "Deep Learning",
        "Reinforcement Learning",
        "Data Science",
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
```

### Get in touch:

📫 How to reach me: [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/mglasder/)


