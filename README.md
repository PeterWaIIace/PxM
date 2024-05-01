![Untitled-2024-01-19-1143(2)](https://github.com/PeterWaIIace/PxM/assets/40773550/1e1254e6-8315-4852-869d-535034cd744e)

# PxM
Prettify your matrices and print them in human readable way. No dependencies 

## How to use:
Just copy `draw_array.py` into your code base, it has no dependencies

And then pass your JAX or Numpy arrays in following fashion:
```
display_array([array_1, array_2],["purple","blue"])
```

or to display it with values:
```
display_with_values([array_1, array_2],["green","yellow"])
```

Examples

just diplay:
```
⎡               ⎤                                       
⎢ .  .  .  .  . ⎥⎡               ⎤⎡               ⎤⎡   ⎤
⎢ .  . 5x2 .  . ⎥⎢ .  . 5x1 .  . ⎥⎢ .  . 5x1 .  . ⎥⎢2x1⎥
⎣               ⎦⎣               ⎦⎣               ⎦⎣   ⎦
⎡               ⎤                                       
⎢ .  .  .  .  . ⎥⎡               ⎤⎡               ⎤⎡   ⎤
⎢ .  . 5x2 .  . ⎥⎢ .  . 5x1 .  . ⎥⎢ .  . 5x1 .  . ⎥⎢2x1⎥
⎣               ⎦⎣               ⎦⎣               ⎦⎣   ⎦

```
or with values
```
                 ⎡               ⎤                                  
                 ⎢ 1.0  0.0  0.0 ⎥                                  
⎡               ⎤⎢ 0.0  1.0  0.0 ⎥⎡               ⎤⎡               ⎤
⎢ 1.0  1.0  1.0 ⎥⎢ 0.0  0.0  1.0 ⎥⎢ 1.0  1.0  1.0 ⎥⎢ 0.5  0.5  0.5 ⎥
⎣               ⎦⎣               ⎦⎣               ⎦⎣               ⎦
                 ⎡               ⎤                                                      
                 ⎢ 1.0  0.0  0.0 ⎥                                                      
                 ⎢ 0.0  1.0  0.0 ⎥                                                      
                 ⎢ 0.0  0.0  1.0 ⎥                                                      
⎡               ⎤⎢ 1.0  1.0  0.0 ⎥⎡                         ⎤⎡                         ⎤
⎢ 1.5  1.5  1.5 ⎥⎢ 0.0  0.0  1.0 ⎥⎢ 1.5  1.5  1.5  3.0  1.5 ⎥⎢ 0.0  0.0  0.0  0.5  0.5 ⎥
⎣               ⎦⎣               ⎦⎣                         ⎦⎣                         ⎦
                           ⎡                         ⎤                        
⎡                         ⎤⎢ 0.0  0.0  0.0  1.0  0.0 ⎥⎡          ⎤⎡          ⎤
⎢ 1.5  1.5  1.5  3.5  2.0 ⎥⎢ 1.0  0.0  0.0  1.0  1.0 ⎥⎢ 3.5  7.0 ⎥⎢ 0.5  0.5 ⎥
⎣                         ⎦⎣                         ⎦⎣          ⎦⎣          ⎦
```
