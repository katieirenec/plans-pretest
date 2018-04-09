================================
Plans Multiple Choice Pre-Test
================================


.. timed:: pretest-mc_timed
    :timelimit: 30
    :nofeedback:

    .. mchoice:: pre1
        :correct: b
	:answer_a: Finds the first height greater than 30
	:answer_b: Creates a list with only heights greater than 30
	:answer_c: Finds the tallest height
	:answer_d: Adds up all heights greater than 30
	:answer_e: Appends h to the tallList

	Choose the **BEST** description of the following code:
	
	    .. code-block:: python
	    
	    	heights = measureHeights()
	        tallList = []

		for h in heights:
		    if h > 30:
		        tallList.append(h)

		print(tallList)


	What will be printed?


    .. mchoice:: pre2
        :correct: d
        :answer_a: [True, False, False, False, False]
        :answer_b: [n]
        :answer_c: ["Alex", "Amilio", "Asabel", "Alivia", "Ariel"]
        :answer_d: ["Alex"]
        :answer_e: "A"

        If **getStudentsNames()** collects an input of ["Alex", "Emilio", "Isabel", "Olivia", "Uriel"], what is printed by the code below?

	    .. code-block:: python

	        names = getStudentNames()
	        aList = []

		for n in names:
		    if n.startswith("A"):
		        aList.append(n)

		print(aList)



    .. mchoice:: pre3
	:correct: c
	:answer_a: I
	:answer_b: II
	:answer_c: III
	:answer_d: IV
	:answer_e: V

	Our goal is to remove all the building heights that are **greater than 100** from the list of building heights. What code should fill in the blank?

	    .. code-block:: python

		for i in range(len(heights)):
	            ## MISSING CODE

		print(heights)

	
	**I.** 
	    .. code-block:: python
	
		if heights[i] > 100:
                    heights[i] = 100
	
	**II.**
	    .. code-block:: python

		del heights[i > 100]

	**III**
	    .. code-block:: python

		if heights[i] > 100:
                    del heights[i]

	**IV** 
	    .. code-block:: python

		heights.append(heights[i])

	**V**
	    .. code-block:: python

		if heights[i] > 100:
		    heights[i] = 0



    .. mchoice:: pre4
        :correct: a
	:answer_a: [ ]
	:answer_b: ["atie", "arthik", "evin", "amar"]
	:answer_c: ["del", "del", "del", "del"]
	:answer_d: [5, 7, 5, 5]
	:answer_e: ["Katie", "Karthik", "Kevin", "Kamar"]

	If **getStudentNames()** collects an input of ["Katie", "Karthik", "Kevin", "Kamar"], what is printed by the code below?

	.. code-block:: python

	    names = getStudentNames()
	    
	    for i in range(len(names)):
		if names[i].startswith("K"):
		    del names[i]

	    print(names)


    .. mchoice:: pre5
        :correct: a
	:answer_a: Determine if there is a dog shorter than 10
	:answer_b: Creates a list with only heights greater than 10
	:answer_c: Finds the shortest dog
	:answer_d: Adds up all heights less than 10
	:answer_e: Changes foundVeryShort to true

	Choose the **best** description of the following code:

	    .. code-block:: python

		heights = measureDogs()
		foundVeryShort = false

		for h in heights:
		    if h < 10:
			foundVeryShort = true

		print(foundVeryShort)




    .. mchoice:: pre6
        :correct: c
	:answer_a: foundShortName
	:answer_b: [false, false, false]
	:answer_c: False
	:answer_d: True
	:answer_e: [true, true, true]

	If **getStudentNames()** collects an input of ["Caitlyn', "Joe", "Kamar"], what is printed by the code below?

	    .. code-block:: python

		names = getClassNames()
		foundShortName = false

		for n in names:
		    if length(n) <= 2:
			foundShortName = true

		print(foundShortName)




When you are finished answering all of the questions, click the **Finish Exam** button.



