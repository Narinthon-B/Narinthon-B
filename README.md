## Hi there 👋
```python
class AboutMe:

  def __init__(self):
      self.name = "Narinthon"
      self.status = "Computer and Robotics Engineering Student"
      self.tech_stack = {
          "Language": ["Python", "SQL"],
          "Data": ["Pandas", "Numpy", "Matplotlib", "ELT", "Data Modeling"]
      }

  def say_hi(self):
      print("Thanks for stopping by my profile. Hope you find something interesting here.")

me = AboutMe()
me.say_hi()
