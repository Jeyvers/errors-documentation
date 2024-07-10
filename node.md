ERROR: 
Emitted 'error' event on Server instance at:
    at emitErrorNT (node:net:1920:8)
    at process.processTicksAndRejections (node:internal/process/task_queues:82:21) {
  code: 'EADDRINUSE',
  errno: -48,
  syscall: 'listen',
  address: '::',
  port: 3000
}

Node.js v21.6.0
[nodemon] app crashed - waiting for file changes before starting...

PROBLEM: I CALLED app.listen(port, () => console.log(`Server is listening on port ${port}...`));
TWO TIMES IN THE APPLICATION
