Summary
-
ArrayTest
-
    [1] should_resize_array

    Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
    
    A1: To learn more about iterating on an array, also setting and getting data from it. Also been able to know and use System functions to help copy an already existing array to another one.

    Q2: Why the test failed at first?
    
    A2: Because the expected values are not set. The Classes are not Implemented

    Q3: Why you corrected the test that way?
    
    A3: I completed the functions inside the MyStack file by pushing the value to the array and increasing the capacity of the array whenever it has passed its capacity. Finally popping the array from top to bottom and returning its results.

    Q4: Do you have further questions on this knowledge point?
    
    A4: None

CollectionsTest
-
    [1] should_go_through_an_iterator
    [2] should_create_a_sequence_without_putting_all_items_into_memory
    [3] should_predict_linked_list_operation_result
    [4] should_generate_distinct_sequence_on_the_fly
    [5] should_reflects_back_to_original_list_for_sub_range

    Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
    
    A1: To learn more about iterators and how to customize your own one. Also being able to utilize it in a loop, get and set their values. And also about different types of Collections such as Lists and Sets.

    Q2: Why the test failed at first?
    
    A2: Because the expected values are not set. The Classes are not Implemented

    Q3: Why you corrected the test that way?
    
    A3: Test [1] Used a while loop with the condition of .hasNext and adding the next value to the list.
    Test [2] Completed the implementation of the Sequence file by setting a global integers of the index and end variables, also edited the hasNext function to check if the index is less than the end variable as well as editing the next function to increment the index.
    Test [3] Answered Amy, Bob, and Carl as the sequence went from going to the first value which is Amy then adding Juliet, but when the previous method is called it will return the newly added object which is Juliet, so when remove is called, it will remove Juliet.
    Test [4] Completed the implementation of the DistinctIterable class by adjusting the constructor, it would create a new Set of objects and then iterate on the iterator and add the elements to the Set, a HashSet will not have duplicate data so it will only have distinct values in it.
    Test [5] Answered 0, 1, 2, 10, 11 as whatever happens to the data in the sublist will reflect all the data on the original list.

    Q4: Do you have further questions on this knowledge point?
    
    A4: None
