numpy:
np.array(): Creates a NumPy array from input data.
print(): Outputs values to the console or terminal.
np.zeros(): Generates an array filled with zeros of specified shape.
+ (Addition): Adds two vectors element-wise.
- (Subtraction): Subtracts one vector from another element-wise.
* (Multiplication): Multiplies a scalar by a vector, performing scalar multiplication.
np.dot(): Computes the dot product of two arrays or vectors.
np.cross(): Calculates the cross product of two 3D vectors.
np.linalg.norm(): Computes the Euclidean norm (magnitude) of a vector.
/ (Division): Divides one array by another, performing element-wise division for normalization.

pandas:
pd.Series(): Creates a Series object from input data, representing vectors.
+ (Addition): Adds two vectors element-wise using Series addition.
* (Multiplication): Multiplies a vector by a scalar element-wise using Series multiplication.
.dot() method: Computes the dot product of two column vectors represented as Pandas Series.
** (Exponentiation): Raises each element in the series to the power of 2 for magnitude calculation.
.sum() method: Sums up the squared elements to compute the magnitude.
np.sqrt(): Calculates the square root, used to find the norm or magnitude of a vector.
/ (Division): Divides one Series by its magnitude to normalize it.

tensorflow:
tf.constant(): Used to create constant tensors.
tf.add(): Performs element-wise addition of two vectors.
tf.multiply(): Performs element-wise multiplication (Hadamard product) between a vector and a scalar.
tf.reduce_sum(): Computes the dot product of two vectors by summing the products of their corresponding elements.
tf.square(): Calculates the square of each element in a tensor.
tf.reduce_sum(): Summation operation to calculate the magnitude (length) of a vector.
tf.sqrt(): Square root function to find the magnitude of a vector.
tf.divide(), normalize_vector(v): Normalizes a vector by dividing it by its magnitude.
tf.tensordot(): Computes the dot product between two vectors.

pytorch:
torch.tensor(): Used to create vectors from lists or arrays.
torch.add, vector1 + vector2 (implicitly using addition operator): Performs element-wise addition between two vectors.
torch.sub, vector1 - vector2 (implicitly using subtraction operator): Performs element-wise subtraction between two vectors.
torch.mul, vector1 * vector2 (implicitly using multiplication operator): Performs element-wise multiplication (Hadamard product) between two vectors.
torch.dot: Computes the dot product of two vectors.
torch.linalg.cross: Computes the cross product of two vectors.
torch.norm: Calculates the norm (length or magnitude) of a vector.
torch.sum: Calculates the sum of all elements in the vector.
torch.mean: Computes the mean (average) of the elements in the vector.