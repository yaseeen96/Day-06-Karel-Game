# 100 Days Of Python - Day 06

## A Maze game

### A simple game to escape the maze utilizing functions and loops

## How to run?

```python
def turn_right():
  turn_left()
  turn_left()
  turn_left()


while not at_goal():
  if right_is_clear():
    turn_right()
    move()
  elif right_is_clear() and wall_in_front():
    turn_right()
    move()
  elif front_is_clear() and wall_on_right:
    move()

  else:
    turn_left()
    if (front_is_clear()):
      move()

```

1. Copy the above code.
2. Head over to [This website](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=test&url=user_world%3Atest)
3. Paste the code in the code editor.
4. Run the code in code editor - Look for a "Run" button or similar control within the Reeborg's World interface. This button is usually located near the code editor. Click the "Run" button to execute your Python code.
