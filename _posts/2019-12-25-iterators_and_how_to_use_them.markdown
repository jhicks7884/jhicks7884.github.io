---
layout: post
title:      "Iterators And How To Use Them"
date:       2019-12-26 02:37:10 +0000
permalink:  iterators_and_how_to_use_them
---

Iterators in ruby lets start by defining what an Iterator is, And then what it does.


   The Definition of Iterate is - Doing one thing multiple times , Iterators are methods you would use with Arrays, and            Hashes.

  so i picked a few iterators to Show Examples of there uses,
	
1. 	.each
    `ary = [1, 2, 3, 4, 5, 6, ]
		    ary.each do |i|
				    puts  i`
						
2. 	.select
   [1, 2, 3, 4, 5, 6].select { |num| num.odd?  #=> should be 3, 5

3. 	.all
    ary = ['a', 'b', 'c', 'e', 'f']
		   ary.all #=> should show all in the Array

4. 	.include and .include?
   ary =[1, 2, 'a', 'b', 'c', ]
	    ary.inlude?("b", 'c')  #=> should be true

5. 	.times 

     1.times do | num | 
               puts " #{num{ Hello"
			   end
				 output = 0 Hello # printed 1 time  at index 0

Iterators can also be chained together Heres an example of this type  use ,
    
		ary.select.all  | the |  ary.include?(the) ......fyi - example - 
		
		Hope this is Helpful....
