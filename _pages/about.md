---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- https://cdn.jsdelivr.net/gh/yuezunli/acad-homepage.github.io@google-scholar-stats/gs_data.json -->

<span class='anchor' id='about-me'></span>

<p style="text-align:justify">
I am an Assistant Professor/Lecturer at the <a href="https://ai-ouc.cn/">Institute of Artificial Intelligence</a>, at <a href="https://www.ouc.edu.cn/main.htm">Ocean University of China</a>. </p>

<p style="text-align:justify">
My research focuses on multimedia forensics, computer vision and vision security.
I have published more than 30 papers in prestigious conferences and journals, including NeurIPS, ICCV, CVPR, ECCV, TIFS, TCSVT, and PR, with total <a href='https://scholar.google.com/citations?user=v0Qt7BAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>, <b>including several papers with more than 1,000 citations each</b> (CVPR20, CVPRW19, ICASSP19, WIFS18). The WIFS18 paper was also featured on <b>CCTV13’s "World Weekly" special on deepfakes [7:43]</b>. I serve as a reviewer for top conferences and journals, such as TPAMI, TIP, IJCV, TIFS, ICCV, CVPR, AAAI, NeurIPS, ICLR, etc. I have been recognized on Stanford’s 2024 list of the top 2% of scientists worldwide and am a recipient of the 2024 ACM Qingdao Rising Star Award. </p>

<p style="text-align:justify">
I was a Senior Research Scientist at the Department of Computer Science and Engineering of <a href="https://www.buffalo.edu/">University at Buffalo, SUNY</a>, 
working with <a href="https://cse.buffalo.edu/~siweilyu/lyu_lab.html">Siwei Lyu</a>. 
I was a summer intern at <a href="https://www.ge.com/research/">GE glocal research center</a> during 2016 - 2018.
I received Ph.D. degree in computer science at <a href="https://www.albany.edu/">University at Albany, SUNY</a> in 2020, advised by <a href="https://cse.buffalo.edu/~siweilyu/lyu_lab.html">Siwei Lyu</a> (IEEE/IAPR Fellow). 
I received M.S. degree in Computer Science in 2015 and B.S. degree in Software Engineering in 2012 at Shandong University. </p>

<p style="text-align:justify">
Currently I am leading <a href="https://yuezunli.github.io/ligroup/">Vision Analysis and Security (VAS) lab</a> <img src="images/logo.png" width="25">. Our lab has multiple openings. <b>Please drop me an email if you are interested in internship / M.S. program.</b>
I am also a member of <a href="https://yuezunli.github.io/planktongroup/">PVOA group</a> which focuses on underwater computer vision reserach. Drop me an email if you are interested.</p>

### 📌 Representative Works

<table class="tab1" width="100%" style="table-layout:fixed;word-break:break-all;background:#fafafa">
    <tr>
        <th>CVPR'20</th>
        <th>CVPRW'19</th>
        <th>WIFS'18</th>
        <th>ICASSP'19</th>
        <th>ICCV'21</th>
    </tr>
    <tr>
        <td><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Celeb-DF_A_Large-Scale_Challenging_Dataset_for_DeepFake_Forensics_CVPR_2020_paper.pdf">[Celeb-DF]</a>
              <a href="https://github.com/yuezunli/celeb-deepfakeforensics">[<i class="fa fa-github" style="color:black"></i>]</a></td>
        <td><a href="http://openaccess.thecvf.com/content_CVPRW_2019/papers/Media%20Forensics/Li_Exposing_DeepFake_Videos_By_Detecting_Face_Warping_Artifacts_CVPRW_2019_paper.pdf">[FWA]</a>
            <a href="https://github.com/yuezunli/CVPRW2019_Face_Artifacts">[<i class="fa fa-github" style="color:black"></i>]</a></td>
        <td><a href="https://arxiv.org/abs/1806.02877">[In Ictu Oculi]</a>
            <a href="https://github.com/yuezunli/WIFS2018_In_Ictu_Oculi">[<i class="fa fa-github" style="color:black"></i>]</a></td>
        <td><a href="https://arxiv.org/pdf/1811.00661">[Head Pose]</a>
            <a href="https://github.com/rbassett3/headpose_forensic">[<i class="fa fa-github" style="color:black"></i>]</a></td>
        <td><a href="http://openaccess.thecvf.com/content/ICCV2021/html/Li_Invisible_Backdoor_Attack_With_Sample-Specific_Triggers_ICCV_2021_paper.html">[ISSBA]</a>
            <a href="https://github.com/yuezunli/ISSBA">[<i class="fa fa-github" style="color:black"></i>]</a></td>
    </tr>
    <tr>
        <td>
            <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>
            <img src="https://img.shields.io/badge/citations-1400+-blue?style=social&logo=google-scholar" />
        </td>
        <td>
            <img src="https://img.shields.io/badge/citations-1100+-blue?style=social&logo=google-scholar" />
        </td>
        <td>
            <img src="https://img.shields.io/badge/citations-1100+-blue?style=social&logo=google-scholar" />
        </td>
        <td>
            <img src="https://img.shields.io/badge/citations-1100+-blue?style=social&logo=google-scholar" />
        </td>
        <td>
            <img src="https://img.shields.io/badge/citations-500+-blue?style=social&logo=google-scholar" />
        </td>
    </tr>
    <tr>
        <td>
            <iframe 
                src="https://www.youtube.com/embed/vLTiluewGQY">
            </iframe>                            
        </td>
        <td>
            <img src="images/representative/fwa.png">
        </td>
        <td>
            <a href="https://tv.cctv.com/2019/04/28/VIDE0aLKiWV83f2PrbZDF4G0190428.shtml"><img src="images/representative/wifs18.png"></a>
        </td>
        <td>
            <img src="images/representative/headpose.png">
        </td>
        <td>
            <iframe
                src="https://www.youtube.com/embed/yFW5lQL9JK8">
            </iframe>                            
        </td>
    </tr>
</table> 

# 🔥 News
- 2025.01: &nbsp;🎉🎉 The work of TSOM (WACV 2025) is elected as Oral. &nbsp; <span style="color:red">New!</span> 
- 2025.01: &nbsp; I gave a talk on face forensics in the wild at CSIG Young Scholars forum. &nbsp; <span style="color:red">New!</span>
- 2024.11: &nbsp;🎉🎉 One paper on phytoplankton tracking is accepted by IEEE TCSVT. 
- 2024.11: &nbsp;🎉🎉 Awarded BMVC outstanding reviewer. 
- 2024.10: &nbsp;🎉🎉 One paper on sequential deepfake detection is accepted by WACV. 
- 2024.09: &nbsp;🎉🎉 One paper on deepfake detection is accepted by NeurIPS. 
- 2024.09: &nbsp;🎉🎉 Elected among <a href="https://topresearcherslist.com/Home/Search?AuthFull=Li,+Yuezun">World's Top 2% Scientists 2024 by Stanford University</a>. 

                
# 📖 Publications <font size="1">(+ Advised student, # Corresponding author, * Equal contribution)</font>

#### Preprints
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/forensicsadapter2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Forensics Adapter: Adapting CLIP for Generalizable Face Forgery Detection](https://arxiv.org/pdf/2411.19715)

Xinjie Cui<sup>+</sup>, **Yuezun Li<sup>#</sup>**, Ao Luo, Jiaran Zhou, Junyu Dong

arXiv:2411.19715, 2024.

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/faceposion2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hiding Faces in Plain Sight: Defending DeepFakes by Disrupting Face Detection](https://arxiv.org/pdf/2411.19715)

Delong Zhu<sup>+</sup>, **Yuezun Li<sup>#</sup>**, Baoyuan Wu, Jiaran Zhou, Zhibo Wang, Siwei Lyu

arXiv:2412.01101, 2024. (Extended from ICME 2023)

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/faceposion2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HRGR: Enhancing Image Manipulation Detection via Hierarchical Region-aware Graph Reasoning](https://arxiv.org/abs/2410.21861)

Xudong Wang<sup>+</sup>, **Yuezun Li<sup>#</sup>**, Huiyu Zhou, Jiaran Zhou, Junyu Dong

arXiv:2410.21861, 2024.

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/dfcam2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Active Fake: DeepFake Camouflage](https://arxiv.org/pdf/2409.03200)

Pu Sun, Honggang Qi<sup>#</sup>, **Yuezun Li<sup>#</sup>**

arXiv:2409.03200, 2024.

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/uwstereo2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UWStereo: A Large Synthetic Dataset for Underwater Stereo Matching](https://arxiv.org/abs/2409.01782)

Qingxuan Lv<sup>+</sup>, Junyu Dong<sup>#</sup>, **Yuezun Li<sup>#</sup>**, Sheng Chen, Hui Yu, Shu Zhang, Wenhan Wang

arXiv:2409.01782, 2024. 

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/hypersfda2024arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[High-order Neighborhoods Know More: HyperGraph Learning Meets Source-free Unsupervised Domain Adaptation](https://arxiv.org/abs/2405.06916)

Jinkun Jiang<sup>+</sup>, Qingxuan Lv, **Yuezun Li<sup>#</sup>**, Yong Du, Sheng Chen, Hui Yu, Junyu Dong<sup>#</sup>

arXiv:2405.06916, 2024. 

[**Code**](-) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div> -->



#### 📆 2025 (WACV\*1)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/tsom2024wacv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Texture, Shape and Order Matter: A New Transformer Design for Sequential DeepFake Detection](https://arxiv.org/abs/2404.13873)

Yunfei Li<sup>+</sup>, **Yuezun Li<sup>#</sup>**, Xin Wang, Baoyuan Wu, Jiaran Zhou, Junyu Dong

IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025. <b><span style="color:red">(Oral)</span></b>

[**Code**](https://github.com/OUC-VAS/TSOM) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/papers/tsom2024wacv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Texture, Shape and Order Matter: A New Transformer Design for Sequential DeepFake Detection](https://arxiv.org/abs/2404.13873)

Yunfei Li<sup>+</sup>, **Yuezun Li<sup>#</sup>**, Xin Wang, Baoyuan Wu, Jiaran Zhou, Junyu Dong

IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025. <b><span style="color:red">(Oral)</span></b>

[**Code**](https://github.com/OUC-VAS/TSOM) <strong><span class='show_paper_citations' data='v0Qt7BAAAAAJ:_xSYboBqXhAC'></span></strong>

</div>
</div>

#### 📆 2024 (NeurIPS\*1, TIFS\*2, TCSVT\*2, BMVC\*2, ACCV\*1, PG\*1, CVIU\*2, TETC\*1, ICASSP\*1, ICMR\*1, KBS\*1)


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.