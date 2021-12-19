Grades

This code is used to produce a Grade Curve Calculator that allows the user to input students' scores
until the user types "q" or "Q" to quit. Then it allows the user to input the expected average score 
to curve and displays the following information until the user types "q" or "Q" to quit:
                         * all the students' scores from the original gradebook and the corresponding 
                           letter grades;
                         * the number of scores in the orignal gradebook;
                         * the highest score and its letter grade in the original gradebook;
                         * the lowest score and its letter grade in the original gradebook;
                         * the average score in the original gradebook;
                         * the expected average score from the user input;
                         * all the students’ scores from the curved gradebook and the corresponding 
                           letter grades based on final grading policy described in the syllabus;
                         * the number of scores in the curved gradebook;
                         * the highest score and its letter grade in the curved gradebook;
                         * the lowest score and its letter grade in the curved gradebook;
                         * the actual average score in the curved gradebook

The purposes of each of the following files are stated below:


FinalGrade.cpp -           to provide the implementation of the member functions of the class named FinalGrade.

FinalGrade.h -             to provide the declaration of the class named FinalGrade.

Gradebook.cpp -            to provide the implementation of the member functions of Gradebook class.

Gradebook.h -              to provide the declaration of the class named Gradebook.

GradeReport.cpp -          to implement a Gradebook Report.
                           it allows the user to input students' scores
                           until the user types "q" or "Q" to quit, 
                           then displays all the valid scores from user input
                           and the corresponding letter grades,
                           the average score, the highest score, and the lowest score.

testGradebook.cpp -        to test if the definition of Gradebook class is correct.
                           it provides THREE testing cases of expected averages
                           to curve the scores based on each expected average.
                           each student's score is at the range [0,100].
                           the expected average is at the range (original average, 100].

GradeCurveCalculator.cpp - to help the professor implement the Grade Curve Calculator. 
                           it allows the professor to calculate the average score for the Final grade 
                           and helps the professor curve the scores based on the expected average.


Compile the source code for the full Grade Curve Calculator program by typing the following at the prompt $:
$ g++ FinalGrade.cpp Gradebook.cpp GradeCurveCalculator.cpp -o GradeCurveCalculator 

Compile the source code for only the Gradebook Report program by typing the following at the prompt $:
$ g++ FinalGrade.cpp Gradebook.cpp GradeReport.cpp -o GradeReport 

Compile the source code for only the Test Grade Curve Calculator program by typing the following at the prompt $:
$ g++ FinalGrade.cpp Gradebook.cpp testGradebook.cpp -o testGradebook

Code is available upon request

