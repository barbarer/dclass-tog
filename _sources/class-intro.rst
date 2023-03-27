Introduction
-----------------------------------------------------

Please read the following, watch the videos, and try to solve the problems.

Solving Write Code Problems
==============================

If you see a problem like the one below you will need to write Python code.  The problem
will have unit tests that you can run to check that your code is working
correctly.  Click on the "Run" button to compile and run your code.  Look after
the code area for compiler errors and/or unit test results.

See the video below for an example.

.. youtube:: w9hTOJ7iJpE
    :divid: class-tog-write-code-video-ex
    :optional:
    :width: 1020
    :height: 826
    :align: center

Try to finish writing the code for the following problem.

.. activecode:: class-tog-intro-sample-write-code-triple-ps
    :practice: T
    :autograde: unittest

    Write a function called ``triple(num)`` that takes a number ``num`` and
    returns the number times 3. For example, ``triple(2)`` should return 6 and
    ``triple(-1)`` should return -3.  Look below the code to check for any
    compiler errors or the results
    from the test cases.  Be sure to ``return`` the result.
    ~~~~
    def triple(num):
        # write code here

    print(triple(2))
    print(triple(-1))

    ====
    from unittest.gui import TestCaseGui
    class myTests(TestCaseGui):

        def testOne(self):
            self.assertEqual(triple(2),6,"triple(2)")
            self.assertEqual(triple(3),9,"triple(3)")
            self.assertEqual(triple(-1),-3,"triple(-1)")
            self.assertEqual(triple(0),0,"triple(0)")
            self.assertEqual(triple(11),33,"triple(11)")

    myTests().main()


Write Code with Pop-Up Mixed-up Code
=======================================

You may also see a write code problem that allows you to pop-up the
equivalent mixed-up code problem. You can use this problem to help you
solve the write code problem.  To pop-up the mixed-up code problem
click on the drop down near the top of problem.  You will still need
to write the code in the write code problem even if you solve the mixed-up
code problem.

.. youtube:: zz4ATp31_vk
    :optional:
    :divid: iwgex-ps-toggle-itcse
    :width: 780
    :height: 498
    :align: center

Solving Mixed-up Code Problems
==================================

If you see a problem like the one below you will need to put the mixed-up
code in the correct order on the right side. You
may need to indent the blocks as well.  There may also be extra blocks that are not
needed in a correct solution that you can leave on the left side. Click the "Check" button
to check your solution.

See the video below for an example.

.. youtube:: Rf7oWHlo-e0
    :divid: iwgex-ps-parsons1-itcse
    :optional:
    :width: 650
    :height: 415
    :align: center

Try to solve the following mixed-up code problem.  This problem doesn't require any indentation.

.. parsonsprob:: intro-simple-parsons-no-indent-ps-itcse
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right. The text in each block
   defines the order.
   -----
   First block
   =====
   Second block
   =====
   Third block

Try to solve the following mixed-up code problem. This problem requires indentation.

.. parsonsprob:: intro-simple-parsons-indent-ps-itcse
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   The text in each block defines the order and indentation.
   -----
   First block
   =====
   Second block
   =====
       Third block that needs to be indented

Try to solve the following mixed-up code problem. This problem requires indentation and has extra blocks that are not needed in a correct solution.

.. parsonsprob:: intro-simple-parsons-indent-with-dist-ps-itcse
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   There is an extra block that is not needed in the correct solution.
   -----
   First block
   =====
   Second block
   =====
   Extra block that is not needed #paired: This block is not needed
   =====
       Third block that needs to be indented

The mixed-up code problems have a "Help me" button at the bottom of the
problem. Once you have checked at least three incorrect solutions you can
click the button for help.  It will remove an incorrect code block, if you used
one in your solution, or combine two blocks into one if there are more
than three blocks left.

See the video below for an example.

.. youtube:: QejZ7u642IU
    :divid: iwgex-ps-parsons2-itcse
    :optional:
    :width: 650
    :height: 415
    :align: center


Feedback
==================================

.. shortanswer:: iticse-ex1-intro-ps-sa-itcse

   Please provide feedback here. Please share any comments, problems, or suggestions.

What to do next
============================
.. raw:: html

    <p>Click on the following link to learn about how to write classes and methods: <b><a id="intro-class"><font size="+2">Introduction to Classes</font></a></b></p>

.. raw:: html

    <script type="text/javascript" >

      window.onload = function() {

        a = document.getElementById("intro-class")
        a.href = "class-intro-classes.html"

      };

    </script>
