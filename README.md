## Data Classification by LabelSpreading
  
  We will implement Label Spreading to classify data points from two circles

## LabelSpreading class implementation
  Defines the LabelSpreading class and provide the necessary methods to build the graph and compute the graph Laplacian for label spreading.<br>

  The _build_graph method is responsible for constructing the graph Laplacian. <br>
  It first computes the affinity matrix using the specified kernel. <br>
  Then, it computes the normalized Laplacian matrix by subtracting the laplacian matrix from the affinity matrix. <br>
  Finally, it sets the diagonal elements of the Laplacian matrix to zero.<br>

  ![labelSpreading](https://github.com/im-Shree/DataClassification-LabelSpreading/assets/90651908/9dd79fe6-7384-43a4-a11a-40088d341817)
