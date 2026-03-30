## Hi there 👋
```python
class AboutMe:

  def __init__(self):
      self.name = "Narinthon Tanwiboon"
      self.status = "Computer and Robotics Engineering Student"
      self.tech_stack = {
          "Language": ["Python", "SQL"],
          "Data": ["Automated ETL Pipelines","Database Design",
                  "Statistical Analysis", "Data Cleaning & Preprocessing"]
      }

  def say_hi(self):
      print("Thanks for stopping by my profile. Hope you find something interesting here.")

me = AboutMe()
me.say_hi()
