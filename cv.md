# Vladislav Terebey

## Contact information:
- Telegram: vterebey
- Email: vladterebei@gmail.com
- Discord: vlad_terebey
- LinkedIn: https://www.linkedin.com/in/terebey-vladislav/

---

## Briefly About Myself:
I am 19 years old, I am a 2nd year student at BSUIR. I have good analytical thinking and basic programming skills.

---

## Skills and Proficiency:
- Programming languages: 
    * С#
    * Python
- Version control systems and development tools:
    * Git

---

## Code example:
Part of the code used to calculate the Jilb metric. Parsing library tree-sitter-scala is used.
``` python
def calculate_jilb_metrics(tree):
    root_node = tree.root_node
    cursor = tree.walk()
    num_branches = 0
    cursor.goto_first_child()
    while True:
        node = cursor.node
        if cursor.goto_first_child():
            num_branches += 1
            while cursor.goto_next_sibling():
                num_branches += 1
            cursor.goto_parent()
        if not cursor.goto_next_sibling():
            if not cursor.goto_parent():
                break
    return num_branches + 1 
```

---

## Work experience:
During my studies at the university, I wrote 3 term papers related to game and network development.

---

## Education:
- 2nd year student of BSUIR

---

## Languages:
English - Intermediate
Russian - Native
Belarusian - Native

