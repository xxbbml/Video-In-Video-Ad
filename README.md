# Video-In-Video-Ad

# Overview
Rapid development of mobile devices has led to explosive growth of videos and online platforms, which creates great demand foronline advertising in videos. Existing advertising methods often aim to randomly select a time point to insert advertisements into videos, which means that the video content at the selected point is likely not related to the ad content, resulting in unsatisfactory user experience. While previous works have neglected to understand rich semantics as well as multimodal information in video advertising, in this paper, in contrast to previous works, we present an innovative method for video-in-video advertising using multimodal modeling. First, we use different pre-trained models to extract corresponding representations, including semantics, scene, object, sentiment, audio and color. Then, through multimodal modeling, we learn the complementarity among different representations and obtain a unified video-level description. Finally, the unified representations of ads and videos are utilized to find the best matching result for each advertisement. Our method emphasizes the content similarity between ad and video, which would make the transition between video and ad more natural. Comprehensive experiments with both objective and subjective evaluations demonstrate the effectiveness and user-friendliness of our proposed video-in-video advertising framework.


Here are some example videos of our proposed method and compared methods:



**Example A:**

<iframe width="280" height="158" src="https://www.youtube.com/embed/InYc1092hHs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> <iframe width="280" height="158" src="https://www.youtube.com/embed/KlGId4-5OTY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/T69Xkspc_zU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/_MzuXtgXfWM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**Example B:**

<iframe width="280" height="158" src="https://www.youtube.com/embed/Hf-nYNQxhH0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> <iframe width="280" height="158" src="https://www.youtube.com/embed/_fUCm0uJrto" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/znVMrMNv3xE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/Kcx8X8ksa0E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**Example C:**

<iframe width="280" height="158" src="https://www.youtube.com/embed/S60yO9yEG2U" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> <iframe width="280" height="158" src="https://www.youtube.com/embed/ZqPU3LWIV0k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/TS8-xk6CFuA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><iframe width="280" height="158" src="https://www.youtube.com/embed/kVNLFl43oEA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
