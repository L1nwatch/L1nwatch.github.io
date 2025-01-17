---
layout: default
---

# Resume

## SKILLS

- `Languages`: English (TOEFL 97, IELTS 7.5), Chinese (Native)
* `Program`: Python(familiar), know others like Shell/Java/JavaScript/C/C++/Ruby
* `Quality Assurance`: Test Solution Design/Functionality/Automation/Performance/Security
* `Area Experience`: Cloud Service(Delivery/Map/IoT/Safe-Monitor backend platform), Internet of Things(Smart TV/locker/AC/...), Security Products(Network Firewall/Endpoint Protection/etc.)
* `Work Tools`: Selenium/Appium/Jmeter/Postman/Docker/Git/Kali/IDA/Jira/OpenaiAPI/…

# EXPERIENCE

## EDUCATION (Highest: Master Degree)

### Concordia University (Master Degree)

> Montreal, Canada, Master of Applied Science Software Engineering, August 2023 - present

`Research-Based`([Supervisor](https://petertsehsun.github.io/)): Combine LLM, Test Techniques to improve the quality of code generation

commit 3 papers(2 accepted, 1 under processing):

* ICSE 2025 accepted(1st author): `SOEN-101: Code Generation by Emulating Software Process Models Using Large Language Model Agents`
* ICSE 2025 accepted(2nd author): `GUIWatcher: Automatically Detecting GUI Lags by Analyzing Mobile Application Screencasts`
* under precessing(1st author): Study how LLM api updates affect code generation performance

`Courses`(CGPA 4.15/4.30): 

* McGill-ECSE688-Automated Software Testing and Analysis(Java projects)
* Concordia-SOEN 691-Generative AI for Software Eng(Python projects)
* Concordia-SOEN 7481-SOFTWARE VERIFICAT N/TESTING(Python projects)
* Concordia-SOEN 6491-SOFTWARE REFACTORING(Java projects)

### Xidian University (bechlor degree)

> Xi’An, China, Bachelor of Information Security, August 2013 - July 2017

`Courses`(GPA 3.7/4.0):

C/C++, Data Structure Algorithm Analysis, Cryptography, Computer Networks,
Software Reverse Engineering, Operating System Principles, Principles of Database, etc...

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

| Organization        | Title          | Year      |
|:-------------|:------------------|:----------|
| Concordia           | Concordia Merit Scholarship | 2025      |
| Concordia           | Concordia Merit Scholarship | 2024      |
| Alibaba | 228th newcomer Learning Star (top 15%)   | 2023      |
| TCL           | Excellent employee of year-2020 (top5%)      | 2021      |
| TCL           | Patent Expert in Test Engineering (16 patents)      | 2019-2022 |
| TCL           | multiple S (KPI Performance Level) | 2019-2022 |
| Sangfor           | Excellent employee of year-2018 | 2019      |
| Sangfor           | Excellent newcomer of year-2017 | 2018      |
| Sangfor           | Innovative gold coin prize of 2018 (20 quotas per year) | 2018      |
| Sangfor           | The innovative team of 2018 (5 quotas per year) | 2018      |
| Sangfor           | 8 times Quarterly Excellence Rewards | 2017-2019 |
| Xidian University           | National Encouragement scholarship | 2016      |
| Xidian University           | The First Prize Scholarship | 2015      |
| Xidian University           | Outstanding Student | 2015      |
| Xidian University           | Special Scholarship/National Scholarship | 2014      |
| Xidian University           | Outstanding Student Mode | 2014      |
