# iSEE

<img src=https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-Server/assets/55953815/f35fbb8a-286d-47f4-806a-d990493aadcc>

## 🔍 Table of contents
- [iSEE](#isee)
  - [🔍 Table of contents](#-table-of-contents)
  - [🗒️ Introduction](#️-introduction)
  - [⚒️ Features](#️-features)
    - [1. Bus Scan](#1-bus-scan)
    - [2. Bus arrival Notification](#2-bus-arrival-notification)
  - [🧭 Project Architecture](#-project-architecture)
  - [🎥 Demo Video](#-demo-video)
  - [💻 How to Run the Code](#-how-to-run-the-code)
  - [🧑🏻‍💻 Team](#-team)


## 🗒️ Introduction

**iSEE** is a visual assistance application designed specifically for visually impaired individuals to navigate bus services with ease and independence. There are many developments in public transportation for the visually impaired, but in reality, it is actually difficult for them to use public transportation. 

iSEE participates in the [Google Solution Challenge 2024](https://developers.google.com/community/gdsc-solution-challenge), aim to contribute to [UN Sustainable Development Goals](https://www.un.org/sustainabledevelopment/sustainable-development-goals/), Goal 3: Good Health and Well-being, Target 10: Reduced Inequalities. By promoting accessibility and inclusivity in public transportation for visually impaired individuals, we strive to reduce inequalities in transportation access and improve overall well-being and health.

**Notice: Currently supports buses within SouthKorea/Seoul, we aim to extend further**

## ⚒️ Features

<img src=https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-Server/assets/55953815/4344dc13-a2ee-413a-8b1f-579311157393>


### 1. Bus Scan

Detects the bus from the camera streaming image. If the user takes a picture, it finds and reads the bus number from the picture.

<p align="center">
<img src=https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-Server/assets/55953815/21e5f2bf-ddfa-47fe-8638-90a28a76f8b7 width=60% height=60%>
</p>
   
### 2. Bus arrival Notification
    
The user can set the bus number to ride. Then a notification is made to the user when the bus arrives nearby. After setting the bus to ride the user can use the bus scan feature to check if the bus has arrived.

<p align="center">
<img src=https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-Server/assets/55953815/3a55f3c1-2919-4bb8-8dd6-de4f2b3c5b3d width=60% height=60%>    
</p>




## 🧭 Project Architecture

<img src=https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-Server/assets/55953815/8fc43788-7c05-4b57-b71a-9b14767946b9>

## 🎥 Demo Video

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/x6i3_LfeTjY/0.jpg)](https://www.youtube.com/watch?v=x6i3_LfeTjY)


## 💻 How to Run the Code
**0. Notice**
- This repository is the project repo to provide overall information about the project
- For each componenet, please download the git submodule repository
  ```bash
  git clone --recursive https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE.git
  ```

**1. Android device (Recomended)**

- Download the app-release.apk file from the [Download Link](https://drive.google.com/drive/folders/1LC_3fcneMIYdz-0ECHatkOIweCWOaB-j?usp=drive_link)
   

**2. iOS device**

- Requirements
  - iOS device
  - Flutter setup required
  - XCode IDE (MacOS)

```bash
# 1. Clone the git repository.
git clone https://github.com/GDSC-KU-SolutionChallenge-iSEE/iSEE-application.git

# 2. Connect the ios device & run
flutter clean && flutter pub get
flutter run --release
```

## 🧑🏻‍💻 Team
**South Korea 🇰🇷 Korea Univ. Seoul Campus**<img src="https://upload.wikimedia.org/wikipedia/ko/thumb/3/34/%EA%B3%A0%EB%A0%A4%EB%8C%80%ED%95%99%EA%B5%90_%EB%A1%9C%EA%B3%A0.svg/400px-%EA%B3%A0%EB%A0%A4%EB%8C%80%ED%95%99%EA%B5%90_%EB%A1%9C%EA%B3%A0.svg.png?20201002132654" width="18" />

- Yerin Choi

  [![EmailBadge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yerinchoi99@gmail.com)

- Kyumin Kim
  
  [![GitHub Badge](https://img.shields.io/badge/GitHub-181717?&logo=GitHub&logoColor=white&style=for-the-badge&link=https://github.com/KY00KIM)](https://github.com/KY00KIM)

- Minsuh Jo

  [![GitHub Badge](https://img.shields.io/badge/GitHub-181717?&logo=GitHub&logoColor=white&style=for-the-badge&link=https://github.com/jjminsuh)](https://github.com/jjminsuh)

- Jeongbin Lee

  [![GitHub Badge](https://img.shields.io/badge/GitHub-181717?&logo=GitHub&logoColor=white&style=for-the-badge&link=https://github.com/joungbinlee)](https://github.com/joungbinlee)