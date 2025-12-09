### 👨‍💻 Ahmad Musayev

```python
class DataScientist:
    def __init__(self):
        self.name = "Ahmad Musayev"
        self.university = "VU Amsterdam"
        self.role = "BSc AI Student"
        self.location = "Amsterdam, NL"
        
    def current_skills(self):
        return [
            "Python", 
            "Machine Learning",
            "Deep Learning",
            "Text Mining",
            "NLP", 
            "Data Visualization"
        ]
        
    def currently_learning(self):
        return "Deep Learning Architectures"

me = DataScientist()
print(me.current_skills())
