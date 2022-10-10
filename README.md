# estimate_gradient

For this assignment, make a python notebook that contains your names. In the notebook, put the answers to the following question (code, values, explanation depending on the item).

Define your Diff function in python.
Compute Diff(x) for 20 random points. What is the average value of Diff? What is the lowest and highest value you found? Is random search a good way to minimize this function?
Set xzero=(50,50). Compute Diff(x)=Diff(50,50).
Create a function to compute and print the gradient of Diff by using a small delta=0.001.
Use this function to print the gradient at (0,0), (100,0), (0,100) and (100,100). Based on these values, is it likely that the minimum of the function is inside this area? And the maximum?
Define xzero=(50,50) and stepsize=1.0. Make a function to compute xnext by taking e a small step into the opposite direction of the gradient, so that diff decreases. E.g. if the gradient is (0.4,0.6), do xnext=(oldx1-0.4*stepsize,oldx2-0.6*stepsize)
Repeat this multiple times (make a function to do this automatically) and print x and Diff(x) at each step. You may need to adjust stepsize if you overshoot or are not moving at all. Try to reach a local minimum.
Repeat step 7 with starting points (0,0) and (100,100). Do you always end up at the same point?
Make the nicest possible chart using mathplotlib that shows what the Diff function looks like.
Show the gradient field as well in a chart. Use a new plot or add the gradient to the original plot.
You should hand in the python notebook.
