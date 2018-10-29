---
layout: post
title:      "Explaining Variables & Methods to My Mom "
date:       2018-10-29 19:16:11 +0000
permalink:  explaining_variables_and_methods_to_my_mom
---


    Getting the woman to sit down for a sec was probably the hardest part about this all (she is a very busy woman). Nonetheless, she caught on pretty quickly and understood better than when I was learning. Here is how it all went down. 

    Beginning with the basics: 

     I began by explaining that any word in Ruby that is not already defined will return an error. So in order to not receive an error message we must first define the variable that we are wanting to call. For example, if I wanted to call on the word  
	 "pozole", alone it would return an error message, because Ruby isn't a fan of words she doesnt know. So in order to help her understand how great pozole is we define the variable "pozole". We can define a varible by setting it equal to a string. In this case what I could do is put pozole equal to the string "hell yes." Now everytime that I call the variable "pozole" it will return the string "hell yes." 
	 The importance behind this is that it helps us store data so we can later save time by simply calling a variable we already defined rather than having to type an entire defintion or explination out everytime we need it. 


	 Defining Methods: 

	A method is like building a small machine. Now this machine can help us do a lot more with a little less effort. ( yes, I am still putting in effort, mom)  For example, if I wanted to say something multiple time, (like when I'm trying to get your attention mom, but you keep ignoring me) in computure format, I could just type "Maaaaaaa" twenty times, but it's very tiring and well I really don't wanna do that. So instead I would create a method that will say "Maaaaaa" for me twenty times with out me having to actually keep saying it.
	
	The way it starts is by using the *def* key word. This is to help define my method, which I will call *distrubing_my_mother*. Now I have to define a varible as to what my method will do. So my variable will be *phrase* = "Maaaaa" Now to put it all together it will look something like this: 

```
1.  def disturbing_my_mother
2.  phrase = "Maaaaa"
3.    puts phrase 
4.    puts phrase
5.    puts phrase
6.    end 
```

          Now whenever I want to get your attention all I have to do is call on the method I created: disturbing_my_mother and it will say "Maaaaa" however many times I've set it to. 
			




