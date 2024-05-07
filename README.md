# MIT-6.5840-Lab-2

## Pass Record
![PassRecord](https://github.com/RLungWu/MIT-6.5840-Lab-2/blob/master/img/pass.png)

## Reference
Lab Page: https://pdos.csail.mit.edu/6.824/labs/lab-kvsrv.html

## What did I do?
In this Lab, I created a simple KV server.
In the src/kvsrv file, you can see my code.

### Special thing I do
I use uuid as the specific ID of every request. To avoid duplicate request, in the common.go, Request of RPC call must be unique.

## Feedback
This is a simple lab. 
What we have to do is to help build the RPC call and deal with easy error handling.
