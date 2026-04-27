# CSE-10124-LAB-3


### 1st sub-block

X goes thru layer norm -> X'
X' goes thru single head self attention -> X''
Y_attn = X + X'' (residual connection)

### 2nd sub-block

Y_attn goes thry layer norm -> Y'
Y' goes thru FFN (linear layer, ReLu, linear layer) -> Y''
Y = Y_attn + Y'' (residual connection)
