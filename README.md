```python
class Profile:
	def __init__(self, name, hobby):
		self.name = name
		self.hobby = "My favourite hobby is " + hobby
		self.funfact = None
    	
	def introduce(self):
		print("Hi there, I'm {}. My favoruite hobby is {}.".format(self.name,self.hobby))
	
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
> Hi There, I'm system1970. My favourite hobby is procrastination.
```python
>> system1970.get_funfact()
```
> There's nothing interesting about me :(
```python
>> system1970.add_funfact("Rumor has it system1970 sleeps more than snorlax")
>> system1970.get_funfact()
```
> Rumor has it system1970 sleeps more than snorlax

## Stats
<img align="left" src="https://github-readme-stats.vercel.app/api?username=system1970&show_icons=true&theme=radical" width="400" height="250">

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=system1970&layout=compact)](https://github.com/system1970/Sorting-Algorithms-Visualizer)

<img src="https://github-readme-stats.vercel.app/api/wakatime?username=system1970&layout=compact">

## Contacts
<ul>
     <li>Gmail: prabhakaran.code@gmail.com</li><br />
</ul>

<hr>

## Where does this fit?
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
