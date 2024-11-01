The data in this repo is get from http://nguyensmai.free.fr/KeraalDataset.html
The purpose of this repo is for learning purpose.


The dataset contains data from three groups of participants:

• Group1 : Rehabilitation Patients :
The data of the daily sessions of the 12 patients recruited is split into two subsets:

– Group1a: 14 recordings per exercise among 6 patients were annotated as detailed in below
– Group1b: the remaining recordings of the 12 patients without annotation.
• Group2 : Healthy participants with Kinect V2 recordings : Six healthy adults performed the exercises after the same instructions. They are free to execute the exercise correctly or with errors. As for group1, the recordings of the 6 healthy adults are split into two subsets:
– Group2a: 51 recordings per exercise were annotated as detailed inbelow
– Group2b: the remaining recordings of the 6 healthy adults without annotation.
• Group3 : Healthy participants : Three healthy adults performed correct execution of exercises and simulated the identified common errors described in below

Annotation description:
 On a global evaluation level, an assessment is given as either correct or incorrect (Challenge 1). In the case of an incorrect error, they can indicate if the execution has no errors but finished before the end (label code 4: incomplete) or the participant did not start the execution of the exercise (label code 5: motionless). On the error classification level, in the case of an incorrect movement, annotations first indicate whether the error is significant or small as well as the label of the error (Fig. 2) (Challenge 2). Moreover the body part causing the error is also indicated (Challenge 3). On a temporal level, the annotators can also indicate the time window where the error occurs (Challenge 4), and the same information as previously: whether the error is significant or small, the error label, and the body part causing the error. The annotation is carried out a frame level.