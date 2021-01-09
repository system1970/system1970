```python
class Profile:
	def __init__(self, name, hobby):
		self.name = name
		self.hobby = "My favourite hobby is " + hobby
		self.funfact = None
    	
	def introduce(self):
		print("Hi there, I'm {}.".format(self.name))
	
	def greet(self, visitor):
		print(f"Hello, {visitor}")				
	
	def add_funfact(self,fact=None):
		self.funfact = fact
	
	def get_funfact(self):
		return self.funfact if self.funfact else "There's nothing interesting about me :("
``` 

<hr>

```python
>> system1970 = Profile("system1970","procrastination")
>> system1970.introduce() 
```
> Hi There, I'm system1970.
```python
>> system1970.get_funfact()
```
> There's nothing interesting about me :(
```python
>> system1970.add_funfact("Rumor has it system1970 sleeps more than snorlax")
>> system1970.get_funfact()
```
> Rumor has it system1970 sleeps more than snorlax

## Github Stats
<img src="https://github-readme-stats.vercel.app/api?username=system1970&amp;show_icons=true">

If you're new to github watch this [tutorial](https://www.youtube.com/watch?v=lR_hYwCAaH4&ab_channel=TheCodingTrain) 

 - 💬 Ask me anything about Python or front end development
<hr>
<h2>Contacts:<br /></h2>
<ul>
     <li>Gmail: pracursergamedev@gmail.com/prabhakaran.code@gmail.com</li><br />
</ul>
<hr>
<!--
**system1970/system1970** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
