```flow
st=>start: Start
io=>inputoutput: verfication
op=>operation: Your Operation
cond=>condition: Yes or No
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```
