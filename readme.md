## Dante's Inferno bash 🔥💻🔥 

---

*Hopefully obvious disclaimer: this doesn't reflect/impose religious beliefs but is just an exploration of an incredibly famous work of literature as a way to motivate the somewhat boring learning of commands*

----

Let's learn about Dante Alighieri's *Divine Comedy* at the same time we learn about bash! (idk man I went to a liberal arts college...). This epic poem has the famous *Inferno* where we're toured through the 9 circles of hell by Virgil.

![](https://www.thoughtco.com/thmb/Avbsf-KY0ImBByRdI1UatD7knW0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/illustration-to-the-divine-comedy-by-dante-alighieri--abyss-of-hell---1480-1490--found-in-the-collection-of-the-biblioteca-apostolica-vaticana--486777773-5c3a03c246e0fb00016261f2.jpg)

Use ***<u>only</u>*** your bash command line to navigate the file structure that represents the circles of hell.  Points will be counted off if actions outside of your provided commands are needed to help navigate.

Below are the levels of hell listed out with your tasks.

----

Possible bash commands/ideas encountered:

* `cd` and using `..`
* `ls` and some of it's options like `-a` and potentially `-R`
* `head` and `tail`
* `touch`
* executing programs and `chmod`
* `mv`
* `mkdir`
* `unzip`

----

## Levels of hell and your tasks

Once you complete the task listed in a level of hell `cd` into the next level of hell.

### Limbo

Here you'll find a castle with 7 walls surrounding it.  Show the names of some of the people Dante encountered here.  The 'people' exist as files, list these files and show the contents of at least one to see more about that person.

### Lust

The inhabitants of this circle of hell are punished by being blown back and forth by strong winds... so it might be hard to spot them with them being 'hidden' by the wind.  List out the names of the people here and show the contents of at least one people files.

### Gluttony

Here we encounter souls without famous names `¯\_(ツ)_/¯`. They're being guarded by Cerberus (view him if you dare!).  One glutton we encounter is name Ciacco, but... given he's a glutton the file is a little unwieldy.  Use commands to show just the first line of the file and the last line of the file to see his prediction.

### Greed

Here we're supposed to see two groups of people jousting... but I don't see anyone even looking for hidden people...

Create two blank files, one named `hoarders` and one named `spenders`. Make sure you've named them exactly like this. Once you've created them run the program `joust` by typing `./joust`.  The program will either depict the jousting scene (v gruesome) or let you know that you didn't create the needed files.

If you get an error saying `permission denied: ./joust` run the command `chmod +x joust`; this gives the `joust` program permission to be executed (aka ran).  Look more into the `chmod` command and what all it can do.

For extra exposure to what bash can do you can look into the contents of the `joust` file.

### Anger

Here we're transported by Phlegyas on the river Styx to the City of Dis.  Unlike Dante, we have to do some of the heavy lifting here. Make a directory called `dis` and move the `boat` to the newly created `dis` directory.

### Heresy

In this circle of hell, heretics are trapped inside flaming tombs!  In `tombs.zip` there are some people who Dante encounters in this circle of hell.  Use the command line to unzip this file and then view the names.

### Violence

A minotaur blocks our entrance to this 7th circle of hell.  Canonically, our guide Virgil, talks us past this beast, but we'll take the easy way out and just remove him from our path.  Delete the minotaur file and proceed to the next level of hell.

### Fraud

Here we see all sorts of people guilty of many different forms of deception and fraud including alchemists!! Copy the lead file and name the copy of the file gold.

### Treachery





