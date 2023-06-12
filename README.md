# usercode

**Test Driven Development Practice**
Using the files tab on the left, double click on the ConcertTicket.ConcertTicket class, and the ConcertTicket.Wallet class.


Get familiar with these files and read through the comments!

Implement getSize() method (size is the number of tickets currently present in the wallet)

Implement getLength() method (length is the capacity of the wallet - maximum number of tickets our wallet can hold)

There is no method for removing a ConcertTicket from the wallet! Your job is to write that method. The method should be called remove. It should take no parameters, and it should return the most recently added ConcertTicket.

Copy
1
2
3
4
5
6
7
8
9
10
11
12
13
14
public ConcertTicket remove() {
      // Create a ConcertTicket reference variable (DO NOT create a
      // new ConcertTicket - JUST create the reference variable)

      // Use the size variable (which always points at the next empty
      // slot) to get the last added ConcertTicket from the array:

      // Set that array slot to null:

      // Decrement the size variable:

      // Return the Concert Ticket:

   }
Once you are done, make sure there are no syntax errors. You can do so by opening the problems view - by clicking on this button in the bottom left -


Which opens this tab -






If there are no errors, go to WalletTest.java in the test/ConcertTicket folder. Click on thick double green arrow on line 7 to run all tests -




If all tests have passed, hit submit!
