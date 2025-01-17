---
layout: default
---

# Resume

---

## SKILLS

- `Languages`: English (TOEFL 97, IELTS 7.5), Chinese (Native)
- `Programming`: Proficient in Python; basic knowledge of Shell, Java, JavaScript, and C/C++.
- `Quality Assurance`: Test Design, Functional/Automation/Performance/Security Testing
- `Product Experience`: AI-Based Solutions (LLM & ML, such as Virus Detection Engines), Cloud Services (Food Delivery, IoT Platforms), Mobile & Web Applications (IoT, Network Firewalls), Other Domains (IoT Smart Devices, Custom OS Testing, etc.)
- `Tools & Frameworks`:
  - **Testing Tools**: Postman (API), JMeter (Performance), Kali Linux (Security), etc.
  - **Automation**: Selenium (Web), Appium (Mobile), Python with unittest(General), etc.
  - **Development**: PyCharm (IDE), MySQL & MongoDB (Databases), Flask (Web), OpenAI API (LLM Integration), etc.
  - **DevOps & CI/CD**: Docker, Conda, Git, GitHub Actions, Jenkins, etc.
  - **Management Platforms**: Jira, Metasphere (Project Progress, Test Case, Bug).

---

## EDUCATION (Highest: Master)

### **Master of Applied Science, Software Engineering**

> Concordia University, Montreal, Canada (August 2023 – Present)

- **Research-Based Program**([Supervisor](https://petertsehsun.github.io/)): Focused on combining LLMs and advanced testing techniques to enhance code generation quality.

- **Publications**: 2 Accepted at ICSE 2025 (47th IEEE International Conference), 1 Under Review
  - **[ICSE 2025](https://conf.researchr.org/track/icse-2025/icse-2025-research-track#Accepted-papers-First-and-Second-Cycle) (1st Author, Cited 27 Times)**: [`SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents`](https://arxiv.org/abs/2403.15852)  
  - **[ICSE 2025](https://conf.researchr.org/track/icse-2025/icse-2025-software-engineering-in-practice#Accepted-Papers) (2nd Author)**: *GUIWatcher: Automatically Detecting GUI Lags by Analyzing Mobile Application Screencasts*  
  - **Under Review (1st Author)**: Study on how LLM API updates affect code generation performance.   

- **Courses (CGPA: 4.15/4.30)**:
  - *McGill ECSE 688*: Automated Software Testing and Analysis (Java-based projects)  
  - *Concordia SOEN 691*: Generative AI for Software Engineering (Python-based projects)  
  - *Concordia SOEN 7481*: Software Verification & Testing (Python-based projects)  
  - *Concordia SOEN 6491*: Software Refactoring (Java-based projects)  

### Bachelor of Information Security

> Xidian University, Xi’an, China (August 2013 – July 2017)

- **GPA**: 3.7/4.0  
- **Key Courses**:  
  - Programming (C/C++, Data Structures, Algorithm Analysis)  
  - Cybersecurity (Cryptography, Software Reverse Engineering, Network Security)  
  - Systems (Operating Systems, Database Principles, Computer Networks) 
  
---

## WORK 

Total 5.5 years experience, mostly in Software Engineering In Test(SDET)

### Huawei (0.4 years)

> Waterloo Centre for Software Excellence(2012 Laboratories), Canada - Intern, 2024.4 - present

My major duty is to study the state-of-the-art testing technology and apply it to offer test ability for qa team, to support huawei products testing. Some algorithms we offered to the testing teams are listed below:

* `Mobile operate system Jank/Issue Detection`: Based on testing mobile system operation recordings, automatic detect any jank moments(or other issues like screen shuttering) happens while tester operating. This technical service is offered by combining SSIM and yolo.
* `Abnormal Version Change Detection`: Based on historical testing metrics data(e.g., response time in each operation), monitor version change to see if performance has been increasement or decreasement, and automatic detect any abnormal version change(decrease the perofmrance). This technical service is offered by multiple outlier data point detection techniques(e.g., iForest).
* `Video-Application jank detection`: Based on testing recordings, Automatic detect whether if video application(like tiktok) would have performance issues(can't load video/slowly load/etc...). This alogirthm is supported by ssim and some diff compare algorithm.

### Alibaba (0.5 years)

> Local Life Service, Shanghai China - SDET, 2023.1 - 2023.7

My major duty is to ensure the quality of cloud service. Our cloud service serves different apps
and has different functions, such as showing the list of restaurants in the map app, showing the
list of menus in each restaurant and showing some promotions related to them, offering online
orders service, tracking delivery status, etc. Some tasks are listed below:

* `API testing`: use built-in test tools to trigger interface data and modify values to verify different test cases, record the correct dataflow as the regression test scripts
* `Write automation test scripts`: write Java test scripts to simulate how a user uses the apps by combining different API invokes in a specific order. 
* `Performance testing`: write Java test scripts to trigger multiple interface requests in a short time, monitor(memory/CPU/IO), and analyze the servers’ performance(QPS/…)

### TCL (3 years)

> Internet of Things, Shenzhen China - SDET & Team Leader, 2019.7 - 2022.6

My major duty is to design and implement different quality assurance solutions in a smart home
scene(IoT). We need to test 4+ endpoints(voice control/app/cloud/TV). For example, user can
power on the TV using their voice or apps on their phone. The command will then be sent to
the cloud server and processed inside the TV device. Thus we need to ensure the software
quality across four endpoints at this simple scene, test if the command is successfully
conveyed, and if the TV rightly responds, and so on. Some tasks are listed below:

* `Team Management`: import Agile/DevOps to the team, build CI/CD testing workflow, improve 230% the team’s efficacy and cut down 19% test period in 20+ versions
* `IoT Test Framework`: create a test framework(Python) based on the ‘keyword/data drive test’ theory, and offer 44+ automation test methods for the IoT Test Scene
* `Scene Automation Test Scripts`: based on the framework, autotest IoT scene (i.e. Control door locks by robot arms and then invoke APIs to check these devices’ cloud status)

### Sangfor (1.6 years)

> Security Products, Shenzhen China - Automation/Security Test Engineer, 2017.7 - 2019.2

My major duty is to write automated scripts to collect datasets and test our security
products(network Firewall/Virus detection engine, etc.). For example, to test the firewall, we
need to imitate the network attack via scripts and check whether the firewall can block this data
packet. Meanwhile, Sangfor uses some machine learning(AI) technology in the products, such
as judging if a file is a virus or a normal file. So as test engineers we need to collect lots of files
from online open sources and do some file fuzzing, to support AI training and analyze the
Accuracy and False Positive Rate of this AI. Some tasks are listed below:

* `Collect Test Datasets`: use Python+requests to collect URLs for testing(i.e. collect all URLs from websites and then invoke BlackChain API to check if they contain threat info)
* `Web Automation Test Scripts`: write Python+Selenium+unittest test scripts to automation click the network firewall web configure buttons and check the pages’ display
* `Develop Statistics Platform`: write shell scripts to collect test devices’ configurations/usage, display status on a Python Django website for other testers

# AWARDS

| Organization         | Title                                                   | Year      |
|:---------------------|:--------------------------------------------------------|:----------|
| Concordia University | Concordia Merit Scholarship                             | 2025      |
| Concordia University | Concordia Merit Scholarship                             | 2024      |
| Alibaba              | 228th Newcomer Learning Star (Top 15%)                  | 2023      |
| TCL                  | Excellent Employee of the Year 2020 (Top 5%)            | 2021      |
| TCL                  | Patent Expert in Test Engineering (16 Accepted Patents) | 2019-2022 |
| Sangfor              | Excellent Employee of the Year 2018                     | 2019      |
| Sangfor              | Excellent Newcomer of the Year 2017                     | 2018      |
| Sangfor              | Innovative Gold Coin Prize 2018 (Top 20 Annually)       | 2018      |
| Sangfor              | Innovative Team Award 2018 (Top 5 Annually)             | 2018      |
| Sangfor              | Quarterly Excellence Award (8-Time Recipient)           | 2017-2019 |
| Xidian University    | National Encouragement Scholarship                      | 2016      |
| Xidian University    | First Prize Scholarship                                 | 2015      |
| Xidian University    | Outstanding Student Award                               | 2015      |
| Xidian University    | Special & National Scholarship                          | 2014      |
| Xidian University    | Outstanding Student Model                               | 2014      |
