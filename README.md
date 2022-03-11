# Video-Summarization

## Video Motivation
### Video usage and consumption

There has been a noticeable uptick in video usage over the past three years. A few stats evidencing this include that video consumption on mobile devices rises a whopping 100 percent each year. In addition, 78 percent of people report watching videos online each week while 55 percent of those watch on a daily basis. More than half (54%) demand more video content on top of what they already consume. Viewers claim they retain 95 percent of a message when obtained via video and a significant 92 percent of mobile users report sharing videos with others. The vast majority of businesses are shifting their strategies accordingly with 81 percent incorporating the tactic into the plans–a 63 percent increase year-over-year.

### Short-form video
Short-form videos continue to trend in 2021. The growth of Instagram reels and TikTok is living proof of that. Although these clips last about 15 seconds, they let brands communicate with the audience in a very exciting way thanks to their relevance and ambiance. Many of these videos go viral thanks to the unusual approach of adding memorable music that underlines the personality of a brand.

<b> How video data is increasing day by day..reports till Jan 2022</b>
<ol>
  <li>statista 2021 https://www.statista.com/statistics/1101966/video-platforms-marketing-worldwide/ </li>
  <li>Wistia 2021 state of video report https://assets.ctfassets.net/j7pfe8y48ry3/47ztlqdwdvMaBcfUEyHy9G/bdbd0de1e74839bf6382aecbf6d09805/Wistia_2021-State-of-Video-Report.pdf       </li>
  <li>Wistia 2021 report description: https://wistia.com/learn/marketing/announcing-the-2021-state-of-video-report</li>
  <li>Cisco 2018-2023 report: https://www.cisco.com/c/en/us/solutions/collateral/executive-perspectives/annual-internet-report/white-paper-c11-741490.pdf </li>
  <li>Wyzowl The State of Video Marketing 2021 report : https://wyzowl.s3.eu-west-2.amazonaws.com/pdfs/Wyzowl-Video-Survey-2021.pdf </li>
  <li><b>Thedrum -The state of video marketing in 2021: https://www.thedrum.com/profile/depositphotos/news/the-state-of-video-marketing-in-2021-infographic</li>
  <li>Social Media Week 2020 Video Marketing and Statistics: What Brands Need to Know : https://socialmediaweek.org/blog/2019/10/2020-video-marketing-and-statistics-what-brands-need-to-know/</li>
  <li>video marketing statistics 2022: https://invideo.io/blog/video-marketing-statistics/</li>
  <li>video consumption statistics 2021: https://techjury.net/blog/video-consumption-statistics/#gref</li>
</ol>
  
### Video Summarization Advantages
  
Video summarization is a process that facilitates fast browsing among large video collections. It also allows more efficient content indexing. Video summarization refers to creating a summary of a video that addresses three main points. (1) The video summary should contain scenes and events not only as short as possible from the video but also the most important one. For example, in a soccer game, the summary must contain goals, fouls, shot boundaries, goal attempt, and some other important scenes. (2) The video summary should maintain a continuous connection amongst scenes. It means that the video summary should not contain video segments connected in a blind way. (3) The summarized video should not contain any redundancy. That is, the video summary should have a free repetition that is verydifficult to achieve. It is necessary to detect various events in the game to generate a summary(doi: 10.14569/IJACSA.2015.061133)<sup>1</sup>.

### Similarity Measures
  <ol>
    <li>5 Similarity Measure https://dataaspirant.com/five-most-popular-similarity-measures-implementation-in-python/ </li>
    <li>other Similarity formulas: https://www.researchgate.net/figure/The-Six-Similarity-Metrics-Used-in-This-Study-for-PSSM-Column-Similarity-and-Motif_fig5_6416709 </li>
    <li></li>
    <li></li>
  </ol>
### Image Similarity
  <ol>
    <li>OpenCv Histogram https://docs.opencv.org/3.4/d8/dc8/tutorial_histogram_comparison.html</li>
    <li>Perceptual Image Similarity 2019 https://github.com/oke-aditya/image_similarity</li>
    <li>Many Similariy Measures https://programmersought.com/article/95107003012/</li>
    <li>Perceptual Similarity Metric https://github.com/richzhang/PerceptualSimilarity</li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
     
  </ol>
  ### Perceptual Loss
  <ol>
    <li>opencv perceptual loss https://www.kaggle.com/bigironsphere/loss-function-library-keras-pytorch</li>  
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ol>
  ### use ResNet50, 34, VGG 16, 19 for feature extraction instead of GoogleNet features
   <ol>
    <li>understanding of h5 file for complete dataset for creating our own. refer create_dataset.py</li>
    <li>extract resnet50 features and replace feature group in h5 file. to extract every layer features of resnet50 using pytorch refer link: https://debuggercafe.com/visualizing-filters-and-feature-maps-in-convolutional-neural-networks-using-pytorch/</li>
    <li>optionally visualize every layer images using above link.</li>
    <li>reshape every dimention of selected frame to 1024 for standard machine summary given in summme dataset for extracted features using Spatial pyramid pooling.</li>
    <li>create your own file for summme dataset using Resnet50 feature vectors.</li>
  </ol>
  
  
  
  ### References
  1. Khan, Y. S., & Pawar, S. (2015). Video summarization: survey on event detection and summarization in soccer videos. International Journal of Advanced Computer Science and Applications, 6(11), 256-259.

 
