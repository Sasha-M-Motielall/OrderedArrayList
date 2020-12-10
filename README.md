# OrderedArrayList
Part I: No NullArrayList
  We essentially discussed that we first need to check wether an input is null or not, in the former case we throw an exception. In the case of the latter, we would just need to call an old method.
	
Part II: OrderedArrayList
  For the first add method you can loop through it until you find a value that's greater than the input(or until the end). For the set method, first you remove the value at the index found prior, then you call the add method that we just wrote. For the private helper method we loop through ArrayList then call the helper method in the add method.
