# Monkey Language

Implementation of a interpreted language following **Writing a interpreter in Go** book by **Thorsten Ball**.

The idea is to be something javascript syntax-like.


- [x] Lexing
- [ ] Parsing
- [ ] Evaluation
- [ ] Extending the Interpreter

### REPL
```bash
Feel free to type in code!
>> let a = 1 + 1;
{Type:LET Literal:let}
{Type:IDENT Literal:a}
{Type:= Literal:=}
{Type:INT Literal:1}
{Type:+ Literal:+}
{Type:INT Literal:1}
{Type:; Literal:;}

>> let add = fn(x, y) { x + y; };
{Type:LET Literal:let}
{Type:IDENT Literal:add}
{Type:= Literal:=}
{Type:FUNCTION Literal:fn}
{Type:( Literal:(}
{Type:IDENT Literal:x}
{Type:, Literal:,}
{Type:IDENT Literal:y}
{Type:) Literal:)}
{Type:{ Literal:{}
{Type:IDENT Literal:x}
{Type:+ Literal:+}
{Type:IDENT Literal:y}
{Type:; Literal:;}
{Type:} Literal:}}
{Type:; Literal:;}
```
