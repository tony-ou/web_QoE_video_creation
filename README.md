# web_QoE_video_creation
This repo gives examples on using Moviepy to customize webpage loading videos.

Tutorial is in: https://github.com/tony-ou/web_QoE_video_creation/blob/main/video_creation.ipynb which contains
- how to delay certain region of a page
- how to relatively speedup region of a page
- how to add browser header and countdown timers to videos
- Demo on how to create test videos for "separate_poke2" campaign 


# Archived: Record actual page load process
[WebPageTest](https://www.webpagetest.org/) is a tool for measuring webpages' performance. You can configure network condition (e.g. bandwidth, RTT) and collect metrics like SpeedIndex of the webpage. Additionally, it has a functionality to record the video o page load. **To get high resolution video you should check the box as below.**

   ![wpt](https://github.com/tony-ou/web_QoE_guide/blob/main/files/wpt.png)

It is possible to do page recording in batch, but the public version of WPT doesn't supports this feature. So you need to set up your own WPT server (e.g. on Amazon EC2). ([A Step by Step Guide to setting up an AutoScaling Private WebPageTest instance](https://www.robinosborne.co.uk/2019/05/20/a-step-by-step-guide-to-setting-up-an-autoscaling-private-webpagetest-instance/))
