# Automin-2021
The trial data for the shared task is available in the following Github repository. The data folder is divided for one main task(Task_A) and two subsidiary tasks(TASK_B and TASK_C). The subsidiary tasks are optional.

Main Task A: The main task consists of automatically creating minutes from multiparty meeting transcripts. The generated minute would be evaluated both via automatic and manual metrics.
Task B: Given a pair of meeting transcript and minute, the task is to identify whether the minute belongs to the transcript. During our data preparation from meetings on similar topics, we found that this task could be challenging given the similarity in various named-entities.
Task C: Given a pair of minutes, the task is to identify whether the two minutes belong to the same or different meetings. This sub-task is important as we want to uncover how minutes created by two different persons for the same meeting may differ in content and coverage.

The Task_A folder contains three different meeting for trial purpose with meeting transcripts, minutes and original minutes. 
The Task_B folder contains meeting_TB1_en to meeting_TB6_en with transcripts and minutes along their meta-data in Annotations_Task_B.
The Task-C folder contains TC1_en to TC6_en with two minutes of same/different meeting. The meta-data for this task can be found in Annotations_Task_C.
