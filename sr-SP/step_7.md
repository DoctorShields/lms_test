## Костими

Сада ћеш направити да твоја певачица изгледа као да пева!

\--- task \---

You can change how your singer sprite looks when it's clicked by creating a new costume. Click on the Costumes tab, and you'll see the singer costume.

![screenshot](images/band-singer-costume-annotated.png)

\--- /task \---

\--- task \---

Right-click on the costume and then click on **duplicate** to create a copy of it.

![screenshot](images/band-singer-duplicate.png)

\--- /task \---

\--- task \---

Click on the new costume (called 'Singer2'), and then select the line tool and draw lines so it looks like your singer is making a sound.

![screenshot](images/band-singer-click.png)

\--- /task \---

\--- task \---

The names of the costumes aren't very helpful at the moment. Type into the text boxes of the costumes to change their names to 'not singing' and 'singing'.

![screenshot](images/band-singer-name-annotated.png)

\--- /task \---

\--- task \---

Now that you have two different costumes for your singer, you can choose which costume is displayed! Add these two code blocks to your singer sprite:

```blocks3
када је кликнуто на овај лик :: events
+замени костим са (пева v) :: looks
репродукуј звук (певачица1 v) до краја :: sound
+замени костим са (не пева v) :: looks
```

The code block for changing the costume is in the `Looks`{:class="block3looks"} section.

\--- /task \---

\--- task \---

Click on your singer on the stage. Does she look like she is singing?

\--- /task \---

\--- task \---

Now make your drum look like it's being hit!

![screenshot](images/band-drum-final.png)

- Употреби упутства за мењање костима лика певачице.

Remember to test that your new code works!

\--- /task \---