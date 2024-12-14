# Unresponsive Node.js Server

This repository demonstrates a common issue in Node.js servers where a delayed response causes slow initial response times.  The `bug.js` file contains a server that waits for 5 seconds before sending a response. The `bugSolution.js` file offers a solution.

## Bug

The server introduces an artificial 5-second delay before responding to requests.  This can lead to frustrating user experiences and potential timeouts, especially in production environments.

## Solution

The solution involves careful asynchronous programming.  In this case, while not an asynchronous operation (send is not an async function), it helps illustrate how to organize asynchronous tasks effectively.