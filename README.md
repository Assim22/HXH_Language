# HXH_Language
This is a programming language design by GOLD Parser Builder 
# PlC(PLD)
This is a simple programming language using some Grammer. and you can see the 
video on [Youtube](https://youtu.be/BAX0mLW1v4w)
# Using Condition
## if_else 
```
<if_else_stm>::=if'('<condition>')' Go <statement> End '['else <statement>']'
              
<condition>::=<expr><operator><expr>
            
<operator>::='<'|'>'|'=='|'!='
```
## Declaration
```
<declaration_stm>::=<type><id>';'
                  
<type>::=int|double
       
<id>::=Id|<id>Id|<id>Digit
```
## While
```
<while_stm>::= while'('<for_stm>')'Go <statement>
```
## Do_While
```
<do_while>::=Do<statement> while'('<for_stm>')''#'
```
## For
```
<for_stm>::=for'('<type><assign>'@'<condition>'@'<count>')'Go <statement> End
          
<count>::='--'<id>|<id>'--'|'++'<id>|<id>'++'|<assign>
```
## For_each
```
<foreach_stm>::=foreach'('<type><id> in <expr>')'<statement>';'
```


## Testing
After you run the code you see 


![WhatsApp Image 2023-05-08 at 3 17 17 PM](https://user-images.githubusercontent.com/119833997/236834452-2fc81953-63a0-4d5c-ad94-f0860802a333.jpeg)

## Author

* **Assim Abdelnour** - [github](https://github.com/Assim22)
