# Mutex and Channel basics

### What is an atomic operation?
> *an operation where a CPU can both read and write to the bus, while all other have to wait for the operation to complete in order to use the bus.

### What is a semaphore?
> *a variable which keeps track of available resourses and which units have access to them

### What is a mutex?
>  a mutex is a mutually exlusive flags which makes it so only one process have access to ta resource at a given time.

### What is the difference between a mutex and a binary semaphore?
>  a binary semaphore can be signaled by other threads, but a mutex can only be released by the thread that acquired it.

### What is a critical section?
> a critical section is a part of a program which has access to shared resources.

### What is the difference between race conditions and data races?
 > race condition is when the sequence or timing of events is different from what is intended. Data race is when there are two concurrent memory writes which target the same memory address.

### List some advantages of using message passing over lock-based synchronization primitives.
 it's easier.

### List some advantages of using lock-based synchronization primitives over message passing.
performance is better.
