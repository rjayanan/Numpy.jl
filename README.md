# Numpy.jl
A Julia package designed to make using the Python library Numpy more accessible to users

# Pre-existing Workflow to Use Numpy in Julia
using Pkg
Pkg.add("PyCall")
using PyCall
np = pyimport("numpy")

# Solution 
Have a Package that can be used directly to access Numpy without having to make an pyimport call 
More user friendly and utilizes less code

# Example
using Pkg
Pkg.add("Numpy")
np = Numpy()
