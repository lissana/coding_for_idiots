00 - intro
==

in this course we will follow a practical approach to learn to code (the art of programming),
some things will be repeated time after time, while other things will be barely mentioned


01 - identity problems
==

what is the best mentality in my opinion? you are ought to read "just on time", searching for solutions, explanations and examples when trying to get something done.
we gotta start with a goal, a problem to solve, etc. not be reading theory just for the sake of it, at least not until you have reached a level advanced enough, where abstract theory makes sense on its own.
most books are structured in this way, introducing theorical concepts, explanations and the application of them, then you are giving some exercises.

how polyglots learn human languages? with an active mind, trying to crack the next paragraph, trying to find similarities and differences like playing the detective's game, and that is how you should learn programming too, playing the detective's game on each piece of code, each line.

how this book should be used?
- **type every example**, muscular memory counts.
- see what can you **infer** from each example, compare them in your head with what u have seen already

02 - right into a task
==

"what? but i don't know anything..." u might be thinking
and that is precisely how it should be, u should have a goal in mind, a task to solve, and basically be searching on all those books, manuals, blogs, etc. "how i do X?", in a sense a programmer has to be a constant learner.

we will write some words in ascii art, for those who don't know what ascii art is, google it.

for example
```
# #  #  ### # #  #  ### ###  #  ###  
### # # # # # # # #  #   #  # # # #  
### ### # # ### ###  #   #  ### # #  
# # # # # # # # # #  #   #  # # # #  
# # # # # # # # # #  #   #  # # # # 
```

using a template of each letter
```
 #  ##   ## ##  ### ###  ## # # ###  ## # # #   # # ###  #  ##   #  ##   ## ### # # # # # # # # # # ### ### 
# # # # #   # # #   #   #   # #  #    # # # #   ### # # # # # # # # # # #    #  # # # # # # # # # #   #   # 
### ##  #   # # ##  ##  # # ###  #    # ##  #   ### # # # # ##  # # ##   #   #  # # # # ###  #   #   #   ## 
# # # # #   # # #   #   # # # #  #  # # # # #   # # # # # # #    ## # #   #  #  # # # # ### # #  #  #       
# # ##   ## ##  ### #    ## # # ###  #  # # ### # # # #  #  #     # # # ##   #  ###  #  # # # #  #  ###  #  
```

okay, now that we have something to do, lets start learning how to do it. 
we will open the REPL and start playing with it.

first lets define some things, type the following:
```clojure
> (def expected_text "MANHATTAN")
..
>
```

and now type:
```clojure
> expected_text
"MANHATTAN"
> 
```

as u see we can instruct the interpreter to remember a value, binding it to a name of our choise, in this example expected\_text is the name and "MANHATTAN" the value, then we observe that we are using double quotes enclosing the value, that is how we introduce literal text into the programs. text is often refered to as strings of characters.

there are many transformations that we can apply to strings out of the box, check the strings section on: https://clojure.org/api/cheatsheet many of these are pretty intuitive like, join togerher multiple strings into one

```
> (str/join ["aaa" "bbb" "ccc"])
"aaabbbccc"
```

thinking like a computer program
==


names over numbers
==

