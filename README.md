# thread-safe-counter

#Project2 (thread-safety by semaphore)

OS environment : Window10, Ubuntu 20.04

Result
Mutex perfomance time is faster than Semaphore. Because Mutex has just two states, lock or unlock. So it performs simply and threads cannot use at the same. But Semaphore dosen't have lock owner process, it could be entering critical section. Therefore this disadvantage makes spending more time than Mutex.
