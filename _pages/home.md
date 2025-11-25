---
layout: archive
permalink: /
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

I am a Ph.D. candidate in the [School of Information Science and Technology](https://sist.shanghaitech.edu.cn/sist_en) at [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) in Shanghai, China, supervised by [Prof. Zhice Yang](https://yangzhice.com). I was admitted to the Ph.D. program after completing my master's training at the [Shanghai Advanced Research Institute, Chinese Academy of Sciences](https://www.sari.ac.cn) (2019–2022), where I worked with Prof. Jiangming Wei and was mentored by [Dr. Xiaoyuan Ma](https://maxiaoyuan.com). I received my bachelor's degree from the School of Information and Communication Engineering, North University of China, in Taiyuan, Shanxi, China, in 2018.

<p style="color: #d73a49; font-weight: bold; margin-top: 1em;">🔴 I am currently on the job market for postdoctoral positions!</p>

## Research Interests
{: #research}

My research primarily focuses on **LiDAR-centric perception and the security and privacy of autonomous driving systems**. Previously, I worked on wireless network coexistence, heterogeneous networking, and cross-technology communication to enable robust connectivity for embedded devices.

## News
{: #news}

<ul id="news-list">
  <li><strong>[2025-08-05]</strong> 🎉 Our paper "An In-model Spy in Edge Intelligence" was accepted by <strong>ACM RAID'25</strong>!</li>
  <li><strong>[2025-04-15]</strong> 🏆 Received <strong>ACM CPS-IoT Week Student Travel Grant</strong> (10/110).</li>
  <li><strong>[2025-04-06]</strong> 🎉 One demo and one poster were accepted by <strong>ACM SenSys'25</strong>!</li>
  <li><strong>[2025-03-10]</strong> 🎉 Our paper "LiDARMarker: Machine-friendly Road Markers for Smart Driving Systems" was accepted by <strong>ACM SenSys'25</strong>!</li>
  <li><strong>[2024-12-06]</strong> 🎉 Our paper "Enable Autonomous Backscatter in Everyday Devices" was accepted by <strong>IEEE INFOCOM'25</strong>!</li>
  <li class="hidden-news"><strong>[2023-06-30]</strong> 🏆 Received <strong>SIST Outstanding Teaching Assistant</strong> Award.</li>
  <li class="hidden-news"><strong>[2022-10-01]</strong> 🎉 Our demo paper was accepted by <strong>ACM EWSN'22</strong>!</li>
  <li class="hidden-news"><strong>[2022-03-10]</strong> 🎉 Our paper "EMU: Increasing the Performance and Applicability of LoRa" was accepted by <strong>ACM/IEEE IPSN'22</strong>!</li>
  <li class="hidden-news"><strong>[2021-09-20]</strong> 🎉 Our dataset paper was accepted by <strong>ACM SenSys'21 Workshop</strong>!</li>
  <li class="hidden-news"><strong>[2021-01-15]</strong> 🎉 Our paper "ChirpBox: An Infrastructure-Less LoRa Testbed" was accepted by <strong>ACM EWSN'21</strong>!</li>
  <li class="hidden-news"><strong>[2021-02-17]</strong> 🏆 Received <strong>EWSN Best Paper Nominee</strong>!</li>
  <li class="hidden-news"><strong>[2020-11-16]</strong> 🏆 Received <strong>EWSN Best Poster</strong> Award!</li>
  <li class="hidden-news"><strong>[2020-11-16]</strong> 🎉 Our poster was accepted by <strong>ACM EWSN'20</strong>!</li>
</ul>

<button id="news-toggle" class="btn btn--primary btn--small" onclick="toggleNews()">Show More</button>

<script>
function toggleNews() {
  var hiddenNews = document.querySelectorAll('.hidden-news');
  var btn = document.getElementById('news-toggle');
  var isHidden = hiddenNews[0].style.display === 'none' || hiddenNews[0].style.display === '';
  
  hiddenNews.forEach(function(item) {
    item.style.display = isHidden ? 'list-item' : 'none';
  });
  
  btn.textContent = isHidden ? 'Show Less' : 'Show More';
}
</script>


<div id="publications"></div>

## Publications

**Conference**

 - **[RAID'25]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a">Core A</span> **<u>Fengxu Yang</u>**, Yihui Yan, Paizhuo Chen, Zhice Yang, "An In-model Spy in Edge Intelligence". [[Paper]](/files/papers/conference/yang_raid25deepspy.pdf)
 - **[ACM SenSys'25]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a-star">Core A*</span> **<u>Fengxu Yang</u>**, Zaizhou, Jiaqi Zhou, Zhice Yang. "LiDARMarker: Machine-friendly Road Markers for Smart Driving Systems". [[Paper]](/files/papers/conference/yang_sensy25lidarmarker.pdf)
 - **[IEEE INFOCOM'25]** <span class="badge badge-ccf-a">CCF-A</span> <span class="badge badge-core-a-star">Core A*</span> Si Liao, **<u>Fengxu Yang</u>**, Huangxun Chen, Zhice Yang. "Enable Autonomous Backscatter in Everyday Devices". [[Paper]](/files/papers/conference/liao_infocom25.pdf)
 - **[ACM/IEEE IPSN'22]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a-star">Core A*</span> **<u>Fengxu Yang</u>**, Pei Tian, Xiaoyuan Ma, Carlo Alberto Boano, Ye Liu, Jianming Wei. "EMU: Increasing the Performance and Applicability of LoRa through Chirp Emulation, Snipping, and Multiplexing".[[Paper]](/files/papers/conference/yang_ipsn22emu.pdf)
 - **[EWSN'21]** <span class="badge badge-core-a">Core A</span> Pei Tian, Xiaoyuan Ma, Carlo Alberto Boano, Ye Liu, **<u>Fengxu Yang</u>**, Xin Tian, Dan Li, Jianming Wei, "ChirpBox: An Infrastructure-Less LoRa Testbed". [[Paper]](/files/papers/conference/tian21chirpbox.pdf) 
 <span style="color:#d73a49; font-weight:600;">(Best paper nominee)</span>

**Journal**

- **[MDPI Sensors'21]** Qingjie Guo, **<u>Fengxu Yang</u>**, Jianming Wei, "Experimental Evaluation of the Packet Reception Performance of LoRa", Sensors, 2021, 21[4]: 1071. [[Paper]](/files/papers/journal/guo_sensors21.pdf)

**Workshop & Demo & Poster**

- **[ACM SenSys'25 Demo]** Zaizhou Yang, Yihui Yan, **<u>Fengxu Yang</u>**, Zhice Yang, "Demo Abstract: Using Fingerprint Scanner for On-Body Messaging". [[Paper]](/files/papers/workshop_demo_poster/demo_yan_sensys25.pdf)
- **[ACM SenSys'25 Poster]** Yihong Hang, Hao Li, Huangxun Chen, **<u>Fengxu Yang</u>**, Zhice Yang, "LLM-Piloted Visual Privacy Agent on Mobile Systems". [[Paper]](/files/papers/workshop_demo_poster/poster_hang_sensys25.pdf)
- **[EWSN'22 Demo]** **<u>Fengxu Yang</u>**, Pei Tian, Xiaoyuan Ma, Carlo Alberto Boano, Ye Liu, Jianming Wei. "Demo: Real-Time Decoding of LoRa Packets Without Prior Knowledge of their Spreading Factor". [[Paper]](/files/papers/workshop_demo_poster/demo_yang_ewsn21sfdec.pdf)
- **[ACM SenSys'21 Workshop]** Pei Tian, **<u>Fengxu Yang</u>**, Xiaoyuan Ma, Carlo Alberto Boano, Xin Tian, Ye Liu, Jianming Wei. "Dataset: Environmental Impact on the Long-Term Connectivity and Link Quality of an Outdoor LoRa Network". [[Paper]](/files/papers/workshop_demo_poster/workshop_tian_sensys21.pdf)
- **[EWSN'20 Poster]** Xiaoyuan Ma, Dan Li, **<u>Fengxu Yang</u>**, Carlo Alberto Boano, Pei Tian, Jianming Wei. "Poster: Chirpbox-A Low-Cost LoRa Testbed Solution". [[Paper]](/files/papers/workshop_demo_poster/poster_tain_ewsn20chirpbox.pdf)
 <span style="color:#d73a49; font-weight:600;">(Best Poster)</span>

<div id="awards"></div>

## Honors & Awards

- ACM CPS-IoT Week Student Travel Grant (10/110), 2025
- SIST Outstanding Teaching Assistant, 2023
- The 2nd prize of 6th Future Network Development Conference, 2022
- EWSN Best Paper Nominee, 2021
- EWSN Best Poster, 2020
- The 3rd prize of International Underwater Robot Competition, 2017
- The 1st prize Shanxi Undergraduate Electronic Design Competition, 2016
- The 3rd prize of National Intelligent Things Association Competition, 2016
- The 3rd prize of International Underwater Robot Competition, 2016
- The 3rd prize of China Robot Competition, 2016
- The 1st prize of International Underwater Robot Competition, 2015
- The 2nd prize of National Undergraduate Electronic Design Competition, 2015
- The 2nd prize of Robot Competition in North China, 2015

<div id="teaching"></div>

## Teaching Experience

**Teaching Assistant**

- Wireless and Mobile System (CS222) 2024
- Computer Network (CS120) 2022, 2023
- Introduction of Information Science and Technology (SI100B) 2020

<div id="service"></div>

## Professional Service

**Reviewer**
- IEEE International Conference on Mobile Ad-Hoc and Smart Systems (MASS), Reviewer, 2023