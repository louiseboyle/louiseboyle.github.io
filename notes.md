---
layout: default
title: Markdown Notes
---

--------------------Page--------------------

start every page with this:

---
layout: default
title: [insert title here]
---



--------------------Text--------------------

Type text normally to insert, it will insert in order as shown in code (writing is displayed top to bottom)

*Italics*

**Bold Writing**


--------------------Headings--------------------

"#" define a headings, 1 hashtag is biggest, 6 is smallest headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


--------------------Links--------------------

Create a link to a page:
[Hyperlink Text to appear]({% link folder/subfolder/file_name.md %})

Create link to external website:
[Hyperlink Text to appear](https://webstite-url.com).

--------------------Images--------------------

to insert an image:
![Any Image Name](/Images/image-name.JPG){:.lead width="800" height="100"}

change width and height to suit


--------------------Tables--------------------

Create tables like this:

| Velocity     |0.0         | 1400.0      | 1410.0  | 2300.0  |
|:------------:|:----------:|:-----------:|:-------:|--------:|
| Acceleration |1600.0      | 160.0       | 0.0     | null    |
| Displacement |Far         | Mid         | Close   | null    |

Lines dont need to be in line but makes it readable in code

--------------------Code--------------------

to insert a code snippet put "~~~" then whatever language to syntax (python, java, c++, etc)
~~~python
def ang_to(self, ideal: 'Vec3') -> float:
        cos_ang = self.dot(ideal) / (self.length() * ideal.length())      
        return math.acos(cos_ang)
~~~
