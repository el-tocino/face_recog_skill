face# face recognition mycroft skill

veryearly work, using obama pic instead of webcam pic, works well with [server](https://github.com/JarbasAI/JarbasAI/tree/patch-13/)

add persons to known faces folder, name of picture is person name

        2017-06-13 16:17:25,704 - Skills - DEBUG - {"type": "face_recognition_request", "data": {"source": "cli:35164", "user": "unknown", "file": "../tmp_file.jpg"}, "context": null}
        2017-06-13 16:17:25,706 - FaceRecogSkill - INFO - cli:35164 request facerecog for ../tmp_file.jpg
        2017-06-13 16:17:25,708 - FaceRecogSkill - INFO - loading unknown image
        2017-06-13 16:17:25,737 - FaceRecogSkill - INFO - getting face encodings of unknown image
        2017-06-13 16:17:27,916 - FaceRecogSkill - INFO - comparing to person obama.jpg
        2017-06-13 16:17:27,929 - FaceRecogSkill - INFO - match found, unknown image is obama
        2017-06-13 16:17:27,936 - Skills - DEBUG - {"type": "speak", "data": {"target": "cli:35164", "mute": false, "expect_response": false, "more": false, "utterance": "obama", "metadata": {"source_skill": "FaceRecogSkill"}}, "context": null}
        2017-06-13 16:17:28,103 - Skills - DEBUG - {"type": "face_recognition_result", "data": {"target": "cli:35164", "result": "obama"}, "context": null}
