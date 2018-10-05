# PhrazeCat
Introduction and motivation

The widespread adoption of electronic medical records (EMRs) has resulted in physicians spending more time on data entry, writing clinical notes, and other EMR-related tasks. Today physicians spend up to 2 hours on EMR documentation for every 1 hour spent seeing patients (https://jamanetwork.com/journals/jamadermatology/article-abstract/2660011). In fact, the burden of documentation is the number one cause of burnout among physicians (https://catalyst.nejm.org/physician-burnout-endemic-healthcare-respond/). One solution to decrease the amount of time spent on documentation has been the development of medical scribes as an established profession to accompany physicians and enter data and write notes for them. A JAMA Dermatology study showed that physicians accompanied by scribes spent 50% less time on documentation. Another study demonstrated that cardiovascular physicians with scribes increased revenue by $1.3 million, but for an additional annual salary of $98,000 per scribe. 

As a fellow at Insight Data Science based in San Francisco, I took on a project to consult for a start-up company called Phraze. Phraze is developing a virtual medical scribe to eliminate the burden of manual documentation by physicians. Using machine learning, this tool records patient-physician conversations during doctor’s visits and generates a structured clinical note integrated into EMRs. As clinical notes are typically consistently structured into note sections, my project objective is to develop a model to automatically assign different parts of a conversation to a specific note section label. These note sections include: History of patient illness, physical exam, assessment, plan, and general conversation. For example, the goal of this project is to make these assignments:

“And your blood pressure dropped you said?” (Patient illness history)
“Yes it did.” (Patient illness history)
“Let’s go ahead and take your blood pressure.” (Physical exam)

“It was nice meeting you.” (General conversation)
“Nice to meet you too.” (General conversation)

