# Greeting and Purpose

Thank you so much for chooing our HITs．

As a part of our research project, we are now trying to build a deep neural network model to identify communication techniques in videos (we chose political ad videos as our target). If successful, our model can automatically find why the video is edited in the way it is, telling people some hints on what the video is trying to communicate. 

Training a deep neural network model requires a vast amount of data with . This series of HITs are designed to collect 

Below we provide our list of possible communication techniques in videos and then the instruction on how to use our interface to annotate temporal segments. We appreciate your time to read through this instruction to make wonderful annotations. 

**We may apply some criteria to automatically reject your input. Please try to comply with the instruction.**

# Communication Techniques in Videos

Videos usually have something that they want to convey to their viewers. In order to communicate the ideas well with the viewers, they are edited with some techniques. We identify the following techniques:

### Repetition

 Showing the same idea repeatedly to make viewers believe it.

### Mood 

Showing scenes with some colors or modify the dominating colors in the scenes so that the scenes give the impressions/emotions associated with the colors. For example, dark colors may imply negative impressions/nemotions; red may imply anger or heat. 

### Overwhelm

Showing many visual elements (e.g., changing scenes rapidly or packing many visual elements like images, subtitles, etc. in a scene), sometimes in a chaotic way, which may prevent the viewer from thinking. 

### Interview

Showing interview with some people (typically a single person), talking about some ideas as their own ones thought. By this, the viewer may think that the ideas are accepted by (a certian group of or general) people. 

### Presentation

Talking or presenting some ideas to convince the viewer. 

### Implication of Emotion

Showing some visual elements that imply certain emotions/impressions so that the topic in (the corresponding part of) the video can be associated with these emotions/impressions. For example, talking about a certain candidate in a policical ad video with showing a person with raising his/her clenched fist may imply confidence.

### Emotiong Mirroring

This is similar to Implication fo Emotion, but with showing facial expressions (instead of arbitrary visual elements).

### Implication of Claim

Showing some visual elements that support a certain idea in (the corresponding part of) the video. The visual elements are not necessarily associated with the context. For example, showing an image of a candidate together with an image of bills may give an impression that the candidate is mean about money. 

### Implication of Authority

Showing some visual elements that imply authority to give impression that the idea is authorized, which may not be necessarily the case.

### Slogans

Showing a slogan (as a visual element like a subtitle) to impress it. 

## Instruction

The typical workflow will be like this:

1. Watch the entire video to grab rough ideas on where to annotate.
2. Start over the video (Press [Space] to play/pause the viddeo).
   1. Press [s] when it comes to the start point of the part (referred to as a segment) that you want to annotate.
   2. Press [e] when it comes to the end point of the segment.
   3. Choose one of the 10 communication techniques for the segment.
   4. Describe your choice.
3. Continue the process until you find all segments in the video.

**Definition of "a segment": A segment is a part of the video, from the start time to tne end time. A segment is associated with one of the communication techniques and a comment. Each segment has a unique ID (8 random characters, called segment ID).

### Our interface

<div align="center">
    <img src="{{site.baseurl}}/images/overview.jpg" style="border: medium solid #000000; padding: 20px">
</div>

Our interface consists of 5 blocks:

#### Video Control Block

<div align="center">
    <img src="{{site.baseurl}}/images/video-control.png" style="border: medium solid #000000; padding: 20px">
</div>

Showing a video player, a seek bar, and three buttons. You can seek your video with using the seek bar. *Play [Space]* button toggles play/pause. *Set start [s]* and *Set end [e]* buttons are for setting the current time to the start and end times of the current segment. **Do not use video control in the player.**

#### Segment Visualization Block

<div align="center">
    <img src="{{site.baseurl}}/images/segment-visualization.png" style="border: medium solid #000000; padding: 20px">
</div>

Showing the segments that you find so far on the timelines (each gray bar is a time line for a communication technique). Your segments will be shown in different colors. A triangle is shown to indicate the start time of the corresponding segment. A tooltip appears when you put your mouse over the segment, showing "[technique of your choice] ([Segment ID]): [Your comment]".  

You can click on any segment to select it and you will be able to modify the segment in the **Add/Update Segment** block.

#### Add/Update Segment Block

<div align="center">
    <img src="{{site.baseurl}}/images/add-update-segment.png" style="border: medium solid #000000; padding: 20px">
</div>

This block deal with "current segment" with:


- a slider with two handles to set the start and end times, 
- radio buttons to choose technqiues,
- a text box to describe your choice of technique,
- "Add" button to add the current segment to the segment list, and
- "Update" button to modify a selected segment.

You can use both "Set start [s]" button or the slider's handle on the right (or keyboard shortcut [s]) to set the start time. The same applied to the end time.

On the right of "Update" button, you will find text saying "(New segment)" or "([Segment ID] is selected)". 

By default, the current segment is a new segment, and you can only add it to the list. Once your select a segment that you already added to list by cliking on one segment in the **Segment Visualization** block or in the *Review Your Segments** block, the selected semgment's ID will appear on the right of "Update" button. **Make sure that you are choosing the right one that you want to modify with the ID.** If a segment is selecte, both "Add" and "Update" buttoms will be activated, and you can either add modified segment as a new one to the list or update the current segment.

In the text box, you are asked to briefly describe your choice.  

- Repetition: Describe what is repeated. For example, a slogan may be repeated several times in a video; then write the slogan.
- Mood: Describe the mood, such as dark, bright, cool, hot, etc.
- Overwhelm: Briefly explain the main message brought by the segment.
- Interview: List the topics.
- Presentation: List the topics.
- Implication of Emotion: Describe the emotion brought by the segment.
- Emotion Mirroring: Describe the emotion brought by the segment.
- Implication of Claim: Describe the claim in the segment.
- Implication of Authority: Specify the authority (White House, court, an expert of something, etc.)
- Slogans: Write the slogan.

You can also mention your doubt or concerns on the segment in this text box. 

#### Review Your Segments block

<div align="center">
    <img src="{{site.baseurl}}/images/review-segment.png" style="border: medium solid #000000; padding: 20px">
</div>


This block lists the segments you added. Before submitting your HIT, please carefully review your segments. 

The list shows:

- segment ID,
- communication technique,
- time line, 
- comment,
- "Select" button, and
- "Remove" button.

You can select the segment by clicking "Select" button to modify the segment or add a new segment based on this segment. You can remove the segment by cliking "Remove" button. When you want to remove a segment, you may find the one that you want to remove in the Segment Visualization block and select it to check the segment ID. Then you can find the one with the ID in this block to remove it. 

#### Comment on This HIT Block

<div align="center">
    <img src="{{site.baseurl}}/images/comment.png" style="border: medium solid #000000; padding: 20px">
</div>


If you have something that you want to communicate with us, please use this text block. 

Please click "Submit" button when you are satisfied with your segment list.



## Questions?

Please use the Segment Visualization block
