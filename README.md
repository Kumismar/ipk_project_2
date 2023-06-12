# IPK project 2
Server implementation of calculator protocol for IPK course at FIT BUT.

Final evaluation: 6.26/20

The final points are bad. 4 points were taken for poor documantation and the rest for their automatic tests.

Evaluating tests for TCP communication were only sending a stream of commands to the server separated with newline characters; this program doesn't support it at all.

Also, I've read the assignment poorly; this server only support two-operand queries, most of the evaluation tests contained at least three.

However, it still does something; it processes two-operand queries almost perfectly (wrote quite good tests imo) and processes both TCP and UDP queries when you send them one by one.

You can read the protocol [here](https://git.fit.vutbr.cz/NESFIT/IPK-Projekty/src/branch/master/Project%201/Protocol.md).

## For FIT students that came for an inspiration
It's not anything you'd like to take inspiration from. However, the simplified functionality (described above) is implemented quite well.
