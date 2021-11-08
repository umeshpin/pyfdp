First install Numpy into your Python environment and load it 

For that  

Either do 
```python
sudo apt-get install python-numpy
```
or
Use PIP installer
```python
pip install numpy
```

Numpy can be imported in Python interface by typing the command 
```python
from numpy import *    # or use
import numpy as np
```
Once you import the package in to the Python environment, it is ready to use. Ready, Steady, Go!!!

```python
import numpy as np 
A= np.array ([[78, 41, 53], [65, 86, 49], [94, 49, 56]])
```

Like most modern programming languages, indexing starts from 0. The element 78 is referred to as A[0,0]. Type the following:

```python
A[0]   # first row  
A[-1]  # last row 
A[0,0] # first row, first column 
A[0,1] # first row, second column 
A[:2] # first two rows  
A[:,1] # second column
```

To create an array with elements in the range 0–99, the following code can be used. 

```python
import numpy as np		
x =np.array(range(100))
```

Here is another Python magic, if you would like to convert the array created just now into three 4x2 matrices, you can simply use the following command:

```python
x.reshape((4,5,5)) 
```

To define matrices consisting only of zeroes or ones, or an identity matrix, try the following:

```python
np.zeros((2,4)) 
```
Identity Matrix

```python
np.identity(3)
```

If you wish to create a matrix with a dimension same as that of another matrix, but containing elements as only zeroes, or only ones, it is very easy in Python! Try the following:

```python
np.ones_like(A)
```

To split an array with elements 0 to 19 into three, try the following command:
```python
x =array(range(20))
split=array_split(x, 3)
```

T
