# cs2110-homework-9-dynamic-memory-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 9-Dynamic Memory Solved](https://www.ankitcodinghub.com/product/cs2110-homework-9-dynamic-memory-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92783&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 9-Dynamic Memory Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.1 Purpose

The purpose of this assignment is to introduce you to dynamic memory allocation in C. You will also learn how to implement a singly-linked list data structure in C.

How do we allocate memory on the heap? How do we de-allocate it when it is no longer used?

1.2 Task

In this assignment, you will be implementing a singly-linked list data structure. Your linked list nodes will have struct data (of type struct user*). You can find details about this struct and the fields it contains in the included list.h file. Your linked list will be able to add, remove, and mutate, and query the data stored within it.

You will be writing code in 1. list.c

2. main.c

The main.c file is included only for your own testing purposes.

1.3 Criteria

You will be graded on your ability to implement the linked list data structure properly. Your implementation must be as described by each function’s documentation. Your code must manage memory correctly, meaning it must be free of memory leaks.

Note: A memory leak is when a block of memory is allocated for some purpose, and never de-allocated before the program loses all references to that block of memory.

2 Instructions

2.1 Implementation Overview

You have been given one C file, list.c, in which to implement the linked list data structure. Implement all functions in this file. Each function has a block comment that describes its expected behavior.

Be sure not to modify any other files. Doing so will result in point deductions that the autograder will not reflect.

Remember that the struct data passed to certain functions (struct user *data) is malloc-ed data. However, this data is allocated separately from the node structs that contain it.

Forgetting to free this data when it is removed can cause memory leaks (memory that is no longer being used, but is never freed). Freeing memory when it should be returned to the struct user can created dangling pointers (memory that’s freed but still being referenced), causing use-after-free bugs. Keep both of these in mind when writing your code.

You are given a struct linked_list, which has a head pointer that points to the first node in the list and a size which represents the length of the linked list. You also have a struct node that has a next pointer

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
to the next node and also a struct user pointer that points to a struct user in memory. Refer to the following diagram for a visual representation of struct linked_list and struct node:

Once you’ve implemented the functions in the list.c file, or after implementing a few, compile your code using the provided Makefile. You may test your functions manually by writing your own test cases in the provided main.c, or run the autograder’s test suite. See the Testing section below for more information.

Please COMPILE OFTEN. The compiler will reveal many syntax errors that you would rather find early before making them over and over throughout your code. Waiting until the end to compile for the first time will cause big headaches when you are trying to debug code. We speak from experience when we say compile often. 🙂

2.2 Implementation Tips

<ul>
<li>Helper functions: There are three helper functions defined in list.c. You should use them to your advantage. NOTE: As seen in list.c, the helper functions are static, which means they are not part of the file’s public interface and therefore will not be tested by the autograder. Improper implementations of these helpers may cause other tests to fail, so be sure to check them if your other functions fail any tests.</li>
<li>Push/add functions: For these functions, make sure to read the documentation about what to do when malloc fails. In most cases, this means that you need to return 1 to indicate something went wrong.</li>
<li>Pop/remove functions: As we mentioned, you should free things that are no longer used to avoid memory leak, but you also don’t want to free prematurely. Here, the potential candidates for freeing are: the nodes, the struct user data inside the node, and the pointers inside the struct user. Think carefully about what you’re doing in these functions (hint: look at return type) and figure out what should be freed.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
• Modifying functions: For these keep in mind that you might not need as much memory as the data originally needed, or you may need more, and in either case you should reallocate memory accordingly.

2.3 Testing and Autograding

To compile and test your code, use the provided Makefile as detailed below. All commands should be run from inside of the CS 2110 Docker container.

2.3.1 Manual testing

To manually test specific functions in your code, fill in the main function in main.c with tests and run $ make hw9

This will create an executable called hw9. Then, you can run your tests via your main function by running $ ./hw9

2.3.2 Running the Autograder

To run the autograder’s test suite, run:

<pre>    # Run all test cases
    $ make run-tests
</pre>
<pre>    # Run a specific test case
    $ make run-tests TEST=test_list_contains_NULL_name
</pre>
Note that the above only runs logical tests on your implementation. The local autograder does not test for memory errors by default, though the one on Gradescope does. To test your code for memory errors locally, you must run valgrind.

To check your code for memory errors using valgrind, run: # Run all test cases

<pre>    $ make run-valgrind
</pre>
<pre>    # Run a specific test case
    $ make run-valgrind TEST=test_list_pop_front_nonempty
</pre>
3 Deliverables

Please upload the following files to Gradescope: 1. list.c

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
4 Appendix

</div>
</div>
<div class="layoutArea">
<div class="column">
4.1

4.1.1

1.

2.

4.1.2

1.

2.

4.1.3

</div>
<div class="column">
Rules and Regulations

General Rules

Although you may ask TAs for clarification, you are ultimately responsible for what you submit. As such, please start assignments early, and ask for help early. This means that (in the case of demos) you should come prepared to explain to the TA how any piece of code you submitted works, even if you copied it from the book or read about it on the internet.

If you find any problems with the assignment it would be greatly appreciated if you reported them to the TAs. Announcements will be posted if the assignment changes.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
