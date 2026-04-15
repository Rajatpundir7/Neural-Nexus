# AI FOR SOCIAL GOODS

# PROBLEM STATEMENT: 
    Design an AI/ML-powered video surveillance system that analyzes real-time CCTV footage to detect and classify unusual events such as violence, theft, or accidents. The system must distinguish normal behaviors from anomalies despite challenges like limited anomaly data, noisy frames, and incomplete labels, while providing reliable, interpretable, and scalable alerts. For example, in a crowded metro station during rush hour, the model should filter routine passenger movement but quickly flag a sudden fight or accident, explain why it was detected, and notify security staff in real time. Each detected event should be classified on a scale of 1–10, where 1 represents normal activity and 10 indicates the most severe anomaly, enabling security teams to prioritize responses effectively.
## CLASSES(14):
    1. abuse -> 50 Videos
    2. arrest -> 50 videos
    3. arson  -> 50 Videos
    4. assult -> 50 Videos
    5. burglary -> 100 Videos
    6. explosion -> 50 Videos
    7. fighting -> 50 Videos
    8. normal -> 60 Videos
    9. road accidents -> 90 videos
    10. robbery -> 150 videos
    11. shooting   -> 50 Videos
    12. shop lifting -> 50 Videos
    13. stealing  -> 100 Videos
    14. vandalism -> 50 Videos

# ExPLANATION: 
    Data set is divided into 14 classes. And we are using 16 Frames per video  