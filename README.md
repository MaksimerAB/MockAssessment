## POS integration assessment

This assessment, though simplified, is made to mimic a real world scenario in order to test and encourage problem solving and logical thinking.

The scenario is as follows:

A customer has reached out to you asking for your help to automate the process of fetching orders from a POS system into their new ERP. At the end of each day the POS system creates text files with all of the transactions from that day and these files are uploaded to a FTP. The ERP on the other hand accepts orders in a JSON format through a REST API.

To simplify you can use a local folder on your computer as the FTP and instead of sending orders to an API write the orders to files on disc in a JSON format.

A diagram of what you will be creating: <br />
<br />
<img src="https://user-images.githubusercontent.com/1340052/147926048-b051c849-c214-4fbc-92fb-ae6a12f37887.png" alt="drawing" width="400" height="200"/>
<br />
<br />
The customer has provided you with the following information:
[POS text files examples](https://github.com/MaksimerAB/MockAssessment)
[Order DTO definition](https://github.com/MaksimerAB/MockAssessment)
They have also told you they want one order per file to the ERP
