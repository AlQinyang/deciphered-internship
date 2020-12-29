# `simple-http`

## Problem Statement
Implement a simple `HTTP/1.1` client-server library in `C` from the ground up, without using any libraries specifically built for this purpose. You will be relying on the availability of the `TCP/IP` layer and hence, you are allowed to use socket-io interfaces/libraries to aid your implementation.
You are allowed to look at simple implementations online to get an idea of the design however, direct plagiarism will be penalized. Given below is a list of tasks to be completed in the order of precedence.

> More tasks completed = More points obtained.

## Tasks
1. Implement an `HTTP Client` that can connect to any existing demo `HTTP` server and communicate using `GET, POST`. You are free to use an existing server or deploy a test server using Python `Flask` etc. The main objective of this task is to get the client working.
2. Implement the `HTTP Server` that can communicate with your client
3. (Bonus) Implement a secure tunnel using `AES-256` (use any standard library implementation). Keys can be assumed to be pre-shared.

## Deliverables
1. Code Repository
2. Report on the implementation - Write a short report on how you went about implementing your client/server. Also, make a note of which features from the `RFC` are supported. Please point out any strong points/features of your implementation (e.g. speed, codebase-size, ease of use, modularity, etc. ). This report should also contain the steps to reproduce the demo.
3. A short video demonstrating the working client/server interactions. (`asciicinema` preferred)


*****This problem statement is currently open**
