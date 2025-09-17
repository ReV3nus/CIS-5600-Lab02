# lab02-debugging

name: Weike Qian
link: https://www.shadertoy.com/view/3fXBDl

BUGs:

 - BUG1: line 97: 'vec' : undeclared identifier                            | HOW: ERROR
 - BUG2: Wrong Resolution in line 11, should be x / y                      | HOW: see two x
 - BUG3: Wrong center point, should minus 0.5f with uv                     | HOW: see and seek
 - BUG4: Wrong marching methods, added steps and maximized mininum step    | HOW: Find error around spheres and seek into marching funcs
 - BUG5: Wrong shader effects because of wrong reflecting direction        | HOW: Checked for specular and diffuse part of color and divided the steps to find the error
