### 1. A Tour of Computer Systems
* 1.1\~1.4: 강재영
* 1.5\~1.7: 김주영
* 1.8\~1.10: 배준현
  
### 2. Representing and Manipulating Information
* 2.1: 배준현
* 2.2: 김주영
* 2.3: 강재영  
  
### 3. Machine-Level Representation of Programs  
* 3.1\~3.3: 강재영
* 3.4: 배준현
* 3.5: 김주영
  
  
# CSAPP Contents  
## Part 0 Intro  
### 1. A Tour of Computer Systems 
1.1 Information Is Bits + Context 39  
1.2 Programs Are Translated by Other Programs into Different Forms 40  
1.3 It Pays to Understand How Compilation Systems Work 42  
1.4 Processors Read and Interpret Instructions Stored in Memory 43  
1.5 Caches Matter 47  
1.6 Storage Devices Form a Hierarchy 50  
1.7 The Operating System Manages the Hardware 50  
1.8 Systems Communicate with Other Systems Using Networks 55  
1.9 Important Themes 58  
1.10 Summary 63 Bibliographic Notes 64  
  
  
## Part I Program Structure and Execution  
### 2. Representing and Manipulating Information 67  
2.1 Information Storage 70  
2.2 Integer Representations 95  
2.3 Integer Arithmetic 120  
2.4 Floating Point 144   
2.5 Summary 162 Bibliographic Notes 163  
  
  
### 3. Machine-Level Representation of Programs  
3.1 A Historical Perspective 202  
3.2 Program Encodings 205  
3.3 Data Formats 213  
3.4 Accessing Information 215  
3.5 Arithmetic and Logical Operations 227  
3.6 Control 236                                                 // 1주  
3.7 Procedures 274  
3.8 Array Allocation and Access 291  
3.9 Heterogeneous Data Structures 301                           // 2주   
3.10 Combining Control and Data in Machine-Level Programs 312  
3.11 Floating-Point Code 329  
3.12 Summary 345 Bibliographic Notes 346                        //3주  

### 4. Processor Architecture 387  
4.1 The Y86-64 Instruction Set Architecture 391  
4.2 Logic Design and the Hardware Control Language HCL 408      //4주  
4.3 Sequential Y86-64 Implementations 420  
4.4 General Principles of Pipelining 448                        //5주
4.5 Pipelined Y86-64 Implementations 457                        //6주 7주
4.6 Summary 506  
  
   
### 5. Optimizing Program Performance 531  
5.1 Capabilities and Limitations of Optimizing Compilers 534  
5.2 Expressing Program Performance 538  
5.3 Program Example 540  
5.4 Eliminating Loop Inefficiencies 544  
5.5 Reducing Procedure Calls 548  
5.6 Eliminating Unneeded Memory References 550  
5.7 Understanding Modern Processors 553               
5.8 Loop Unrolling 567                                          // 38page 8주  
5.9 Enhancing Parallelism 572    
5.10 Summary of Results for Optimizing Combining Code 583
5.11 Some Limiting Factors 584
5.12 Understangding Memory Performance 589
5.13 Life in the Real World: Performance Improvement Techniques 597   
5.14 Identifying and Eliminating Performance Bottlenecks 598  
5.15 Summary 604    
  
    
### 6. The memory hierarchy    
6.1 Storage Technologies 617  
6.2 Locality 640   
6.3 The Memory Hierarchy 645   
6.4 Cache Memories 650  
6.5 Writing Cache-friendly Code 669  
6.6 Putting It Together: The Impact of Caches on Program Performance 675  
6.7 Summary 684  
  
    
### 7. Linking   
7.1 Compiler Drivers 707  
7.2 Static Linking 708  
7.3 Object Files 709  
7.4 Relocatable Object Files 710  
7.5 Symbols and Symbol Tables 711  
7.6 Symbol Resolution 715  
7.7 Relocation 725  
7.8 Executable Object Files 731   
7.9 Loading Executable Object Files 733  
7.10 Dynamic Linking with Shared Libraries 734  
7.11 Loading and Linking Shared Libraries from Applications 737  
7.12 Position-Independent Code (PIC) 740  
7.13 Library Interpositioning 743
7.14 Tools for Manipulating Object Files 749  
7.14 Summary 749  
  
   
### 8. Exceptional Control Flow  
8.1 Exceptions 759  
8.2 Processes 768  
8.3 System Call Error Handling 773  
8.4 Process Control 774  
8.5 Signals 792  
8.6 Nonlocal Jumps 817  
8.7 Tools for Manipulating Processes 822  
8.8 Summary 823   
  
  
### 9. Virtual Memory    
9.1 Physical and Virtual Addressing 839  
9.2 Address Spaces 840  
9.3 VM as a Tool for Caching 841  
9.4 VM as a Tool for Memory Management 847  
9.5 VM as a Tool for Memory Protection 848  
9.6 Address Translation 849   
9.7 Case Study: The Intel Core i7/Linux Memory System 861  
9.8 Memory Mapping 869  
9.9 Dynamic Memory Allocation 875  
9.10 Garbage Collection 901  
9.11 Common Memory-Related Bugs in C Programs 906  
9.12 Summary 911  
  
    
## Part III Interaction and Communication between Programs  
### 10. System-Level I/O 925  
10.1 Unix I/O 926
10.2 Files 927  
10.3 Opening and Closing Files 929  
10.4 Reading and Writing Files 931  
10.5 Robust Reading and Writing with the Rio Package 933    
10.6 Reading File Metadata 939  
10.7 Reading Directory Contents 941  
10.8 Sharing Files 942   
10.9 I/O Redirection 945  
10.10 Standard I/O 947  
10.11 Putting It Together: Which I/O Functions Should I Use? 947   
10.12 Summary 949  
  
  
### 11. Network Programming 953    
11.1 The Client-Server Programming Model 954  
11.2 Networks 955  
11.3 The Global IP Internet 960  
11.4 The Sockets Interface 968  
11.5 Web Servers 984  
11.6 Putting It Together: The Tiny Web Server 992  
11.7 Summary 1000  
  
  
### 12. Concurrent Programming 1007  
12.1 Concurrent Programming with Processes 1009  
12.2 Concurrent Programming with I/O Multiplexing 1013  
12.3 Concurrent Programming with Threads 1021  
12.4 Shared Variables in Threaded Programs 1028  
12.5 Synchronizing Threads with Semaphores 1031  
12.6 Using Threads for Parallelism 1049  
12.7 Other Concurrency Issues 1056  
12.8 Summary 1066  
  
## APPENDIX
### A. Error Handling 1077

