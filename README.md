# Hi, there!

```python
class Guy(object):

    # attributes
    name = "Bo"
    work = "Cal Poly"
    home = "California"
    hobby = "Traveling"
    interests = "Machine Learning and Mechatronics"
    
    # methods
    def update_status(string):
        print("i'm working on", string, "now!")
        
    def introduce(self):
        print("Hello, this is", self.name)
        print("I'm into", self.interests, "and", self.hobby)

Bo = Guy()
Bo.introduce()
Bo.update_status("deep learning")
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
