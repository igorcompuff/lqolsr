---------------------------------------------------------------------------------------------------------------------
		Lq OLSR - Extension of OLSR protocol to support link-quality metrics in NS3
---------------------------------------------------------------------------------------------------------------------

---> To Do
	- More appropriate MPR computation. Currently, all symetric neighbors are selected to be MPRs. Because this functionality
	  is not important in my PhD. research, I don´t intend to work on this any soon.
	  
---> Metrics
    - The protocol supports any metric subclassing from LqAbstractMetric;
	- I have already implemented the ETX metric following the draft-funkfeuer-manet-olsrv2-etx-01 (https://tools.ietf.org/html/draft-funkfeuer-manet-olsrv2-etx-01)
	
---> If you find any bugs, please let me know
