<h2>dcap - A Distributed Computation Architecture in Python</h2>
dcap is a lightweight server-client architecture that allows you to execute all kinds of different computational tasks on clients on a local network and have them send their results back to the server.
 
For an in-depth description, see <a href="http://byterial.blogspot.com/2013/02/dcap-distributed-computation.html" target="_blank">http://byterial.blogspot.com/2013/02/dcap-distributed-computation.html</a>
<br>
For an api documentation, see documentation/index.html

__OS Compatibility__:
- _Linux_: Tested on Ubuntu
- _OS X_: Some issues occur as sem_getvalue() from the multiprocessing is not implemented, see <a href="http://docs.python.org/2/library/multiprocessing.html target="_blank">the documentation</a>
- _Windows_: Does not work due to issues with the multiprocessing library, see <a href="http://docs.python.org/2/library/multiprocessing.html#multiprocessing-programming target="_blank">the documentation</a> . I currently do not have a Windows machine to test on.

