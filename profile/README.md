## 👂 All Ears: A Voice Visualizing WearOS App for Kids with Hearing Impairments in Inclusive Educational Environments

<img width="1920" alt="All Ears" src="https://github.com/TeamAllways-AllEars/.github/assets/89632139/06290039-c5fd-4185-8754-c8cb1e3133a3">

## 🪧 Project Overview
> When you lose your vision, you lose contact with things.\
When you lose your hearing, you lose contact with people.\
Helen Keler

<img width="1920" alt="Project Overview of All Ears" src="https://github.com/TeamAllways-AllEars/.github/assets/89632139/b15815ec-3759-4240-a23f-a728790ad009">

In **South Korea**, changes to the health insurance criteria in 2009 expanded **cochlear implant surgery** and enabled more kids with hearing impairments to study in **inclusive education environments**.<a href="https://www.e-asr.org/m/journal/view.php?number=498">[1]</a> However, despite many receiving inclusive education, there aren't enough services for kids with hearing impairments in inclusive education classrooms in South Korea. These kids mostly communicate with kids without disabilities **through speech**.

This environment causes a lot of discomfort for children with hearing impairments. According to Ms. A, a person who has a hearing impairment, one of the difficulties in regular school was not being able to check her own voice's volume and content, which made her continuously ask friends to check them. Therefore, we need a service for kids with hearing impairments who need to engage in everyday communication in inclusive educational settings.

**Team Allways** build "All Ears", an WearOS app that provides real-time Voice-Noise Ratio Visualization, Live Captioning, and Past Captioning Rewatch for kids with hearing impairment. We aim to build an additional ear through visualization of speech and help kids with disabilities build camaraderie with their friends. With "All Ears" we can achieve 3 UN SDGs goals—the **quality of education**, **promote peace**, and **reduce inequalities**.

## ⚙️ Architecture & Tech
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
This project has two repositories: [All-Ears_Android](https://github.com/TeamAllways-AllEars/All-Ears_Android) for `WearOS` client application and [All-Ears_Server](https://github.com/TeamAllways-AllEars/All-Ears_Server) for `SpringBoot` backend server. The guidance on how to run the code is in each repository's GitHub `README.md` file. If you want to run the code, please follow the instructions of each repositories.

## 📽 Demo Video Link
[![AllEars Demo Video](https://github.com/TeamAllways-AllEars/.github/blob/e6287f8a64ee65ddc17d2511bce4015429ef808d/images/all%20ears%20youtube%20video.png)](https://www.youtube.com/watch?v=8hec7ohdeOA)

## ⚙️ Release Note
### 2023-02-26
> v1.0.0 release
- Added Voice-Noise Ratio Feature(Tenserflow lite)
- Added Speech-to-Text Featrue(GCP STT API)
- Added Past Captioning Rewatch Feature(GCP Cloud SQL & VM instance)

## 👩‍💻 Contributors

|                                  Android                                   |                                    Android                                    |                                   Backend                                    |                                    Design                                     |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/87654809?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/91647696?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/89632139?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/144984293?v=4" width=150px> |
|                     [노원희/Wonhui Roh](https://github.com/neoseurae12)                     |                     [정예지/Yeji Jeong](https://github.com/yeji0214)                      |                   [전혜승/Haeseung Jeon](https://github.com/JeonHaeseung)                   |                   [김수연/Suyeon Kim](https://github.com/mmaybei)                    |

## 📄 Related study
[1]<a href="https://www.e-asr.org/m/journal/view.php?number=498">Cho, Soo Jin, Mi Sook Lee, and Yu Ri Lee. "Analysis of the Current Status and Characteristics of the Hearing Impaired Using Data from the Actual Survey for the Disabled." Audiology and Speech Research 18.1 (2022): 9-19.</a>

## 📧 Contact us
[![allways](https://img.shields.io/badge/team%20allways-71A1FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:team.allways.gdsc@gmail.com)
