# Bottom-Up-Parser-using-Python


## Introduction

The bottom-up parsing method constructs the node in the syntax tree in post-order: the top of a subtree is constructed after all of its lower nodes have been constructed. When a bottom-up parser constructs a node, all its children have already been constructed and are present and known. We start from a sentence and then apply production rules in reverse manner in order to reach the start symbol. 

I have designed a Shift-Reduce parser in python which is a type of bottom up parser. As the parser performs both the shift and reduce operations by examining the input tokens and either performing shift operation on the stack or reducing the element at the top of stack, replacing the right hand side by the left hand side. 
