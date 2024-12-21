This repository contains a simple Rust program that demonstrates a common error: creating a dangling pointer. The program uses unsafe code to manipulate the vector's internal pointer directly, which can lead to undefined behavior if the vector is dropped before the pointer is dereferenced. The solution demonstrates a safe way to modify the vector's contents without creating dangling pointers.