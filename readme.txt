OVERVIEW:
          The Typing Speed Tester is a Python program with a graphical user interface (GUI)
               designed to assess and improve typing skills.
          It provides a typing test where users can type a randomly selected paragraph within a specified time frame,
               and the program evaluates typing speed, accuracy, and more.
FEATURES:
          Dynamic Timer: The program includes a dynamic timer that counts down from a specified total time.
          Real-time Statistics: Users can view real-time statistics, including elapsed time, remaining time,
                                words per minute (WPM), total words, wrong words, and accuracy percentage.
          Random Paragraphs: The program shuffles and presents random paragraphs for a varied typing experience.
          Virtual Keyboard: A virtual keyboard is displayed, and the GUI responds to key presses
                            for an interactive experience.
          Threading: Threading is employed to manage parallel execution of the timer and statistics calculations.
PREREQUISITES:
          Installing packages:

          tkinter: GUI package for Python.
          ttkthemes: Package for themed GUI elements.

             pip install tk ttkthemes
RUN:
          python main.py
USAGE:
         1.Click the "Start" button to initiate the typing test.
         2.Type the displayed paragraph in the text area.
         3.Real-time statistics will be updated, including WPM, total words, wrong words, and accuracy.
         4.After the timer reaches zero, the test ends, and results are displayed.
         5.Click the "Reset" button to start a new test.
         6.Use the virtual keyboard for additional visual feedback.
