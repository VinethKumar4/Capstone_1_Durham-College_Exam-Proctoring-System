# Capstone_1_Durham-College_Exam-Proctoring-System
Exam Proctoring System 


1. Install Cuda Toolkit
2. Install CudNN
3. Libraries to be installed
	cmake
	dlib with cuda support
	face_recognition
	pytorchyolo with cuda support
	opencv
	imutils
	PIL
	pickle
	
4. Copy the source code to your project folder
5. Add candidate data to the data directory (if any, optional)
6. Run main.py as "python main.py -d data"

The majority of companies are adopting WFH culture now a days. So, the recruitment process
is facing challenges in assessing online tests of large number of candidates.

We propose a system that can help recruiters to categorize candidates before pushing them in
the interview round if they have used any unfair means during the online exam by recording a
video of them while they attempt the test.

Scope Of Work
Develop and implement the algorithm to detect if a candidate is using unfair means during
virtual examination.
• Assumptions:
➢ The images on which the model will learn will be taken at the beginning of the
test.
➢ The main test video on which the algo will run will be done later and not at
runtime.
• Limitations:
➢ The algo will flag moments in the test video which seem unfair instead of a fix
judgement. This in turn will make the invigilator look at the flagged moments.
➢ Heavy compute power required.
• Constraints:
➢ The learning images should not have any other face in the background except for
the candidate.
➢ The test should be taken in a well-lit room.
