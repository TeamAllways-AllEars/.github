## 👂All Ears, an WearOS app for kids with hearing impairment in inclusive education environment

<img width="1920" alt="All Ears" src="https://github.com/TeamAllways-AllEars/.github/assets/89632139/4c44a3ac-062b-487d-b064-203dec66124d">

## 🪧 Project Overview
> When you lose your vision, you lose contact with things.\
When you lose your hearing, you lose contact with people.\
Helen Keler

<img width="1920" alt="Project Overview of All Ears" src="https://github.com/TeamAllways-AllEars/.github/assets/89632139/01be16b4-a78d-4d07-a598-dfdc02dcf9d4">

In **South Korea**, changes to the health insurance criteria in 2009 expanded **cochlear implant surgery** and enabled more kids with hearing impairments to study in **inclusive education environments**.<a href="https://www.e-asr.org/m/journal/view.php?number=498">[1]</a> However, despite many receiving inclusive education, there aren't enough services for kids with hearing impairments in inclusive education classrooms in South Korea. These kids mostly communicate with kids without disabilities **through speech**. Therefore, we need a service for kids with hearing impairments who need to engage in everyday communication in inclusive educational settings.

**Team Allways** build "All Ears", an WearOS app that provides real-time Voice Ratio Visualization, Live Captioning, and Past Captioning Rewatch for kids with hearing impairment. We aim to build an additional ear through visualization of speech and help kids with disabilities build camaraderie with their friends.

## 🚀 Features


## ⚙️ Architecture
<div>
  <img alt="Wear OS" src ="https://img.shields.io/badge/wearos-4285F4.svg?&style=for-the-badge&logo=wearos&logoColor=white"/>
  <img alt="Tensorflow Lite" src ="https://img.shields.io/badge/tensorflow lite-FF6F00.svg?&style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img alt="Spring Boot" src ="https://img.shields.io/badge/spring boot-6DB33F.svg?&style=for-the-badge&logo=springboot&logoColor=white"/>
  <img alt="GCP STT" src ="https://img.shields.io/badge/GCP STT-4285F4.svg?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img alt="GCP VM" src ="https://img.shields.io/badge/GCP VM-4285F4.svg?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img alt="GCP Cloud SQL" src ="https://img.shields.io/badge/GCP Cloud SQL-4285F4.svg?style=for-the-badge&logo=googlecloud&logoColor=white"/>
</div>

<img width="1920" alt="Architecture of All Ears" src="https://github.com/TeamAllways-AllEars/.github/assets/89632139/48539296-03cb-4267-af0c-338a55ebe4c8">

To achieve Voice Ratio Visualization, we utilized `TensorFlow Lite's AudioClassifier` model, an on-device AI for edge devices. We also implemented Live Captioning using `GCP's STT API`. For Past Captioning Rewatch, we created a `Spring Boot (Java 17)` backend server that uses `GCP Cloud SQL (MySQL 8.0 engine)` and hosted it on a `GCP VM instance`.

These features are visualized through an app built on `WearOS (Kotlin 1.7 & Java 8)`, making it possible for users to access it in everyday situations at school.

## 🪧 Guidance
This project has two repository: [All-Ears_Android](https://github.com/TeamAllways-AllEars/All-Ears_Android) for `WearOS` client application and [All-Ears_Server](https://github.com/TeamAllways-AllEars/All-Ears_Server) for `SpringBoot` backend server. The guidance on how to run the code is in each repository's GitHub `README.md` file.

## 📄 Related study
[1]<a href="https://www.e-asr.org/m/journal/view.php?number=498">Cho, Soo Jin, Mi Sook Lee, and Yu Ri Lee. "Analysis of the Current Status and Characteristics of the Hearing Impaired Using Data from the Actual Survey for the Disabled." Audiology and Speech Research 18.1 (2022): 9-19.</a>

## 📧 Contact us
[![allways](https://img.shields.io/badge/team%20allways-71A1FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:team.allways.gdsc@gmail.com)
