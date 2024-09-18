Advanced animations extension:

- Now you can create bone groups. Bones can be easily added to a group by keywords. For example if your skeleton have bones "mixamorigLeftHandRing4,mixamorigLeftHandPinky1,mixamorigLeftHandPinky2" you can just write "hand" and all bones containing this word will be included to the group
- To exclude certain bones you can use "*". Example: you have bones "UpSpine,middleSpine, middleSpine2" and you want to add only "UpSpine,middleSpine" to your group. Just write "spine*" to achieve this
- Different animations can be played for certain groups independently
- Transition between animations can be called for picked bone groups independently
- Transition can move your bones to a start frame, end frame or any custom frame of the picked animation. An expression to find out frames amount for a certain animation is included
