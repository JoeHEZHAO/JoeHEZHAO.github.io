---
permalink: /
title: "Know about me !"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

[2017 ~ Now]

> Machine/Computer Vision is such an <b>Exciting</b>/ <b>Fast-evolving</b>/ <b>Application-practical</b> field and I am delightful to be a part of it ! As a PhD. student under supervision of Professor <a href="http://www.cse.yorku.ca/~wildes/">Richard P. Wildes</a> York University Toronto Canada, my research focuses on video predictive understanding, which includes interesting tasks as Action/Activity Prediction/Anticiption, Video Prediction, Motion Planning, Vehicle/Pedestrian Trajectory tracking and etc. In a word, I do research on exploring the possible future.

[2015-2017]

> Before my Ph.D. journey, I worked with Professor <a href='https://www.bme.ufl.edu/labs/yang/'> Lin Yang</a> at University of Florida (<font color='orangered'>Go</font> <font color='blue'>Gator</font> !) as a master research assistant. During my stay, we came out some really cool projects towards biomedical imaging understanding (as listed below).

# Recent News

<div id='list_scroll'>
    <nav>
        <ul>
            <li> 2020.07.03: My paper "<b>On Diverse Asychronous Activity Anticiption</b>" gets accepted at ECCV2020 !! See u at online conference</li>
            <br />
            <li> 2019.07.22: My paper "<b>Spatiotemporal Feature Residual Propagation for Action Prediction</b>" get accepted at <a href='http://openaccess.thecvf.com/ICCV2019.py'><b>ICCV2019</b></a> ! See you in Seoul ! </li>
            <br />
            <li> 2018.01.15: I become a Ph.D. student in <a href='http://vision.eecs.yorku.ca/main/'>Vision Lab</a> Start working with Prof. Richard P. Wildes on Video/Activity Analysis !</li>
            <br />
            <li> 2018.01.01: I received <a href='https://gradstudies.yorku.ca/current-students/student-finances/funding-awards/ots/'>Ontario Tillium Scholarship</a> that grants 40,000\$ annually for my Ph.D. </li>
            <br />
            <li> 2018.01.01: I received <a href='https://vista.info.yorku.ca/opportunities/doctoral-scholarships/'>VISTA Scholarship</a> that grants 10,000\$ annually for my Ph.D. </li>
            <br />
            <li> 2017.06~09: I did research summer internship with <a href='http://deepinformatics.com.cn/'>Deepinformatics++ LLC. (迪英加科技)</a> for biomedical imaging processing. </li>
            <br />
            <li> 2017.05.01: I graduated from University of Florida, Master in Computer Science. </li>
        </ul>
    </nav>
</div>
<br />

# Selected Works

<table style='background-color:transparent border-collapse:collapse border: none'>
    <tbody>
        <tr>
            <span style="bold; color: #000066;">Spatiotemporal Feature Residual Propagation for Action Prediction</span>
        </tr><br />
        <tr>
            <font color='red'>He Zhao, Richard P. Wildes</font>
        </tr><br />
        <tr>
            <font color='green'> International Conference on Computer Vision (ICCV2019) </font>
        </tr>
        <tr>
            <td width="40%" style="border-style:hidden;">
                <img src="https://JoeHEZHAO.github.io/images/iccv_2019.png">
            </td>
            <td style="border-style:hidden;">
                <p style="text-align: justify;">
                Recognizing actions from limited preliminary video observations
                has seen considerable recent progress. Typically,
                however, such progress has been had without explicitly
                modeling fine-grained motion evolution as a potentially
                valuable information source. We address this
                task by investigating how action patterns evolve over time in 
                a spatial feature space. There are three key components to 
                our system. First, we work with intermediate-layer ConvNet 
                features, which allow for abstraction from raw data, while 
                retaining spatial layout, which is sacrificed in approaches 
                that rely on vectorized global representations. Second, instead 
                of propagating features per se, we propagate their 
                residuals across time, which allows for a compact representation 
                that reduces redundancy while retaining essential 
                information about evolution over time. Third, we employ a 
                Kalman filter to combat error build-up and unify across prediction 
                start times.
                </p>
            </td>
        </tr>
        <tr>
            <td style="border-style:hidden;"> </td>
            <td style="border-style:hidden;">
                [<a href='http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Spatiotemporal_Feature_Residual_Propagation_for_Action_Prediction_ICCV_2019_paper.pdf'>pdf</a>][<a href='https://github.com/JoeHEZHAO/Spatiotemporal-Residual-Propagation'>code</a>]
            </td>
        </tr>
    </tbody>
</table>

<table style='background-color:transparent border-collapse:collapse border: none'>
    <tbody>
        <tr>
            <span style="bold; color: #000066;">Construction Scene DPM Object Tracking via Detection</span>
        </tr><br />
        <tr>
            <font color='red'>He Zhao, Pingjun Chen, Lin Yang</font>
        </tr><br />
        <tr>
            <td width="40%" style="border-style:hidden;">
                <img src="https://JoeHEZHAO.github.io/images/flagDetection.gif">
                <img src="https://JoeHEZHAO.github.io/images/fireEquimentsDetection.gif">
            </td>
            <td style="border-style:hidden;">
                <p style="text-align: justify;">
                Built a Local Binary Patterns based software for face recogition, together with Deformable Part Model for object tracking. Implementation these two effective algorithms for contruction site videos with the aim to prevent from stranger invading and fire-fighting equipments stealing. Now we are heading towards implementing MOT on large-scale construction site video to monitor multiple objects.
                </p>
            </td>
        </tr>
    </tbody>
</table>

<table style='background-color:transparent border-collapse:collapse border: none'>
    <tbody>
        <tr>
            <span style="bold; color: #000066;">Deep Convolution Neural Network for Muscle Cell Segmentation</span>
        </tr><br />
        <tr>
            <font color='red'>He Zhao, Shaoju Wu, Lin Yang</font>
        </tr><br />
        <tr>
            <td width="40%" style="border-style:hidden;">
                <img src="https://JoeHEZHAO.github.io/images/segmentation.gif">
                <img src="https://JoeHEZHAO.github.io/images/DeepNetworkArchitect.png">
            </td>
            <td style="border-style:hidden;">
                <p style="text-align: justify;">
                Based on medical image data provided by BICI2 lab, implemented fully connected network edge detection methods with watershad as post-proecess and got a better detection and segmentation effect compared with random forest method. Now working on residual neural network to achieve better result and keep digging on deep learning.
                </p>
            </td>
        </tr>
    </tbody>
</table>

<table style='background-color:transparent border-collapse:collapse border: none'>
    <tbody>
        <tr>
            <span style="bold; color: #000066;">Random Forest Muscle Cell Segmentation</span>
        </tr><br />
        <tr>
            <font color='red'>He Zhao, Shaoju Wu, Pingjun Chen, Mason, Lin Yang</font>
        </tr><br />
        <tr>
            <td width="40%" style="border-style:hidden;">
                <img src="https://JoeHEZHAO.github.io/images/random_forest.gif">
            </td>
            <td style="border-style:hidden;">
                <p style="text-align: justify;">
                 Developed a cpp software implementation of an image segmentation algorithm based on paper <a href="https://arxiv.org/pdf/1406.5549.pdf" target="_blank">'Fast Edge Detection Using Structured Forests'(Piotr Dollár)</a>, for Muscle Cell Image gathered from University of Florida Shands Hospital. Combined with HOG(Histogram of oriented gradients) for feature extraction, UCM Segmentation algorithm, Watershed and self-defined Hierarchical segmentation framework for segmentation, this cpp dll-call software works quite well for our muscle cell data and totally get rid of matlab dependency.
                </p>
            </td>
        </tr>
    </tbody>
</table>

<table style='background-color:transparent border-collapse:collapse border: none'>
    <tbody>
        <tr>
            <span style="bold; color: #000066;">Online Muscle Cell Annotation Tool</span>
        </tr><br />
        <tr>
            <font color='red'>Pingjun Chen, He Zhao, Manish, Lin Yang</font>
        </tr><br />
        <tr>
            <td width="40%" style="border-style:hidden;">
                <img src="https://JoeHEZHAO.github.io/images/onlineAnnotationDemo.gif">
            </td>
            <td style="border-style:hidden;">
                <p style="text-align: justify;">
                Using python FLASK framework to build up an online platform, which utilizes our recent accomplishments on Cell-Image Segmentation Research. And allows everyone to modify the contour as groundtruth for further training in deep learning. With Flask's strong server-client interaction functionality, visitors would be able to modify the contour of cell online and re-submit it back to server. To make it more interactive, we use deep zoom package, paper.js and openseadragon as well.
                </p>
            </td>
        </tr>
    </tbody>
</table>
