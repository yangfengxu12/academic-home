---
layout: archive
permalink: /
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

I received my Ph.D. in Computer Science and Technology from [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) in 2026 under the supervision of [Prof. Zhice Yang](https://yangzhice.com). Before transferring to ShanghaiTech's Ph.D. program, I pursued master's studies at ShanghaiTech (2019–2022) through joint training at the [Shanghai Advanced Research Institute, Chinese Academy of Sciences (SARI)](https://www.sari.ac.cn) under the supervision of Prof. Jianming Wei, with mentorship from [Dr. Xiaoyuan Ma](https://maxiaoyuan.com/). I received my bachelor's degree from North University of China in 2018.

<p style="color: #d73a49; font-weight: bold; margin-top: 1em;">🔴 I am currently seeking a postdoctoral position!</p>

## Research Interests
{: #research}

My research focuses on **LiDAR-based sensing and the security and privacy of autonomous driving systems**. Previously, I worked on wireless network coexistence, heterogeneous networking, and cross-technology communication to enable robust connectivity for embedded devices.

## News
{: #news}

<ul id="news-list">
  <li><strong>[2026-07-01]</strong> 🎓 I received my Ph.D. in Computer Science and Technology from ShanghaiTech University!</li>
  <li><strong>[2026-05-21]</strong> 🎉 I passed my Ph.D. defense!</li>
  <li><strong>[2026-03-17]</strong> 🎉 Our paper "Enabling Seamless LoRa-to-Mobile Bridging via Wi-Fi Spectrum Scanning" was accepted to <strong>IEEE SECON'26</strong>!</li>
  <li><strong>[2025-08-05]</strong> 🎉 Our paper "An In-model Spy in Edge Intelligence" was accepted to <strong>RAID'25</strong>!</li>
  <li><strong>[2025-04-15]</strong> 🏆 I received an <strong>ACM SIGBED Student Travel Grant</strong> for CPS-IoT Week 2025 (10/110).</li>
  <li class="hidden-news"><strong>[2025-04-06]</strong> 🎉 Our demo and poster were accepted to <strong>ACM SenSys'25</strong>!</li>
  <li class="hidden-news"><strong>[2025-03-10]</strong> 🎉 Our paper "LiDARMarker: Machine-friendly Road Markers for Smart Driving Systems" was accepted to <strong>ACM SenSys'25</strong>!</li>
  <li class="hidden-news"><strong>[2024-12-06]</strong> 🎉 Our paper "Enable Autonomous Backscatter in Everyday Devices" was accepted to <strong>IEEE INFOCOM'25</strong>!</li>
  <li class="hidden-news"><strong>[2023-06-30]</strong> 🏆 I received the <strong>SIST Outstanding Teaching Assistant Award</strong>.</li>
  <li class="hidden-news"><strong>[2022-10-01]</strong> 🎉 Our demo paper was accepted to <strong>EWSN'22</strong>!</li>
  <li class="hidden-news"><strong>[2022-03-10]</strong> 🎉 Our paper "EMU: Increasing the Performance and Applicability of LoRa through Chirp Emulation, Snipping, and Multiplexing" was accepted to <strong>ACM/IEEE IPSN'22</strong>!</li>
  <li class="hidden-news"><strong>[2021-09-20]</strong> 🎉 Our dataset paper was accepted to <strong>DATA'21 (Data: Acquisition to Analysis)</strong>, a workshop co-located with SenSys/BuildSys 2021!</li>
  <li class="hidden-news"><strong>[2021-02-17]</strong> 🏆 Our paper was nominated for the <strong>EWSN Best Paper Award</strong>!</li>
  <li class="hidden-news"><strong>[2021-01-15]</strong> 🎉 Our paper "ChirpBox: An Infrastructure-Less LoRa Testbed" was accepted to <strong>EWSN'21</strong>!</li>
  <li class="hidden-news"><strong>[2020-11-16]</strong> 🏆 Our poster won the <strong>EWSN Best Poster Award</strong>!</li>
  <li class="hidden-news"><strong>[2020-11-16]</strong> 🎉 Our poster was accepted to <strong>EWSN'20</strong>!</li>
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

**Conference Papers**

- **[IEEE SECON'26]** <span class="badge badge-ccf-b">CCF-B</span> Jiaqi Zhou, **<u>Fengxu Yang</u>**, Yihui Yan, Zhice Yang, "Enabling Seamless LoRa-to-Mobile Bridging via Wi-Fi Spectrum Scanning". [[Paper]](/files/papers/conference/zhou_secon26lora2mobile.pdf)
- **[RAID'25]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a">CORE A</span> **<u>Fengxu Yang</u>**, Paizhuo Chen, Yihui Yan, Zhice Yang, "An In-model Spy in Edge Intelligence". [[Paper]](/files/papers/conference/yang_raid25deepspy.pdf)
- **[ACM SenSys'25]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a-star">CORE A*</span> **<u>Fengxu Yang</u>**, Zaizhou Yang, Jiaqi Zhou, Zhice Yang, "LiDARMarker: Machine-friendly Road Markers for Smart Driving Systems". [[Paper]](/files/papers/conference/yang_sensy25lidarmarker.pdf)
- **[IEEE INFOCOM'25]** <span class="badge badge-ccf-a">CCF-A</span> <span class="badge badge-core-a-star">CORE A*</span> Si Liao, **<u>Fengxu Yang</u>**, Huangxun Chen, Zhice Yang, "Enable Autonomous Backscatter in Everyday Devices". [[Paper]](/files/papers/conference/liao_infocom25.pdf)
- **[ACM/IEEE IPSN'22]** <span class="badge badge-ccf-b">CCF-B</span> <span class="badge badge-core-a-star">CORE A*</span> **<u>Fengxu Yang</u>**, Pei Tian, Xiaoyuan Ma, Carlo Alberto Boano, Ye Liu, Jianming Wei, "EMU: Increasing the Performance and Applicability of LoRa through Chirp Emulation, Snipping, and Multiplexing". [[Paper]](/files/papers/conference/yang_ipsn22emu.pdf)
- **[EWSN'21]** <span class="badge badge-core-a">CORE A</span> Pei Tian, Xiaoyuan Ma, Carlo Alberto Boano, Ye Liu, **<u>Fengxu Yang</u>**, Xin Tian, Dan Li, Jianming Wei, "ChirpBox: An Infrastructure-Less LoRa Testbed". [[Paper]](/files/papers/conference/tian21chirpbox.pdf) <span style="color:#d73a49; font-weight:600;">(Best Paper Award Nominee)</span>

**Journal**

- **[Sensors'21]** Qingjie Guo, **<u>Fengxu Yang</u>**, Jianming Wei, "Experimental Evaluation of the Packet Reception Performance of LoRa", Sensors, 2021, 21(4): 1071. [[Paper]](/files/papers/journal/guo_sensors21.pdf)

**Patents**

- **<u>Fengxu Yang</u>**, Yu An, Bobo Zhou, Shaoyu Wang, Huitong Fu, "Elderly Mobility Aid Monitoring Device Based on the BeiDou Satellite Navigation System". CN206479642U (Granted)

**Workshops, Demos, and Posters**

- **[ACM SenSys'25 Demo]** Zaizhou Yang, Yihui Yan, **<u>Fengxu Yang</u>**, Zhice Yang, "Demo Abstract: Using Fingerprint Scanner for On-Body Messaging". [[Paper]](/files/papers/workshop_demo_poster/demo_yan_sensys25.pdf)
- **[ACM SenSys'25 Poster]** Yihong Hang, Hao Li, Huangxun Chen, **<u>Fengxu Yang</u>**, Zhice Yang, "Poster Abstract: LLM-Piloted Visual Privacy Agent on Mobile Systems". [[Paper]](/files/papers/workshop_demo_poster/poster_hang_sensys25.pdf)
- **[EWSN'22 Demo]** **<u>Fengxu Yang</u>**, Pei Tian, Xiaoyuan Ma, Jianming Wei, Carlo Alberto Boano, "Demo: Real-Time Decoding of LoRa Packets Without Prior Knowledge of their Spreading Factor". [[Paper]](/files/papers/workshop_demo_poster/demo_yang_ewsn21sfdec.pdf)
- **[DATA'21]** Pei Tian, **<u>Fengxu Yang</u>**, Xiaoyuan Ma, Carlo Alberto Boano, Xin Tian, Ye Liu, Jianming Wei, "Dataset: Environmental Impact on the Long-Term Connectivity and Link Quality of an Outdoor LoRa Network". The 4th Workshop on Data: Acquisition to Analysis (DATA ’21), co-located with SenSys/BuildSys 2021. [[Paper]](/files/papers/workshop_demo_poster/workshop_tian_sensys21.pdf)
- **[EWSN'20 Poster]** Xiaoyuan Ma, Dan Li, **<u>Fengxu Yang</u>**, Carlo Alberto Boano, Pei Tian, Jianming Wei, "Poster: Chirpbox – A Low-Cost LoRa Testbed Solution". [[Paper]](/files/papers/workshop_demo_poster/poster_tain_ewsn20chirpbox.pdf) <span style="color:#d73a49; font-weight:600;">(Best Poster Award)</span>

<div id="awards"></div>

## Honors & Awards

- ACM SIGBED Student Travel Grant, CPS-IoT Week (10/110), 2025
- Outstanding Teaching Assistant Award, ShanghaiTech University, 2023
- Second Prize, Future Light – Future Network Technology Innovation Competition, 2022
- Best Paper Award Nominee, EWSN, 2021
- Best Poster Award, EWSN, 2020
- National Undergraduate Innovation and Entrepreneurship Training Program, 2017
- Third Prize, International Underwater Robot Competition, 2017
- First Prize, Shanxi Province Undergraduate Electronic Design Contest, 2016
- Third Prize, National College Student Smart Internet Innovation Competition, 2016
- Third Prize, International Underwater Robot Competition, 2016
- Third Prize, China Robot Competition, 2016
- First Prize, International Underwater Robot Competition, 2015
- Second Prize, National Undergraduate Electronics Design Contest, 2015
- Second Prize, Robot Competition for College Students in Five Provinces of North China, 2015

<div id="teaching"></div>

## Teaching Experience

**Teaching Assistant**

- Computer Networks (CS120), Fall 2022, Fall 2023, and Fall 2026
- Wireless and Mobile Systems (CS222), Spring 2024
- Introduction to Information Science and Technology (SI100B), Spring 2020


<div id="service"></div>

## Professional Service

**Reviewer**

- IEEE Transactions on Green Communications and Networking (TGCN), 2026
- IEEE International Conference on Mobile Ad Hoc and Smart Systems (MASS), 2023

