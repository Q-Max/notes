# notes

# Git

### To change default editor for git

>git config --global core.editor vim

### To recover a file to the current branch

>rm test.c
>git checkout test.c

### To branch

> git branch NAME

### To list branches

>git branch

### To change branch

>git checkout NAME

### To merge 2 branches

>git merge NAME

>\#will merge branch NAME to current branch

#Ruby

### methods

>class Girl

>end

>def Girl.age

> @age

>end

equal to

>class Girl

> def Girl.age

>   @age

> end

>end

equal to 

  class Girl
  
   def self.age
  
     @age
  
   end
  
  end


add a method to an existed class

  class String
    def is_email?(email)
      ....
    end
  end

  "aaa@gmail.com".is_email?

### self class > module > superclass

### some plugin
*kaminari
*bootstrap-sass
*devise
