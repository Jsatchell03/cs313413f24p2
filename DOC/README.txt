TODO what happens if you use list.remove(Integer.valueOf(77))?
    If you only have one lin of "list.remove(Integer.valueOf(77))" one instance of 77 gets removed but not
    all of them. If you put "list.remove(Integer.valueOf(77))" in the while loop it runs more times than there are 77s
    and, we get an error.
TODO also try with a LinkedList - does it make any difference?
    When I ran the test using a linked list the build was still successful

TODO run test and record running times for SIZE = 10, 100, 1000, 10000, ...
    Linked List 10: 939, 100: 946, 1000: 1s, 10000: 11s
    ArrayList 10: 896, 100: 888, 1000: 1s, 10000 11s
    Array list was faster with smaller tasks but as the tasks got larger the difference was no longer noticeable
