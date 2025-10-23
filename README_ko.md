# Linux 권한 상승 기법

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Linux 권한 상승 기법](https://cover-creator.labex.io/privilege-escalation-techniques-on-linux.png?lang=ko)](https://labex.io/ko/courses/privilege-escalation-techniques-on-linux)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/privilege-escalation-techniques-on-linux)

본 과정에서는 Linux 시스템에서 권한을 상승시키는 다양한 기법에 대해 배우게 됩니다. 초급 수준의 과정으로, Linux 시스템에서 권한을 상승시키는 여러 가지 기술을 다룹니다.

![Pen-Testing](https://img.shields.io/badge/Pen-Testing-whitesmoke?style=for-the-badge&logo=pen-testing)


## 연습

|   인덱스 | 이름                                                                | 난이도   | 연습                                                                                                                                                                                             |
|----------|---------------------------------------------------------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🧩  Nmap 에서 단순 셸을 인터랙티브 셸로 업그레이드                  | 초급     | <a target='_blank' href='https://labex.io/ko/labs/upgrade-simple-shell-to-interactive-shell-in-nmap-416148?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                        |
|       02 | 🧩  Nmap 을 이용한 /etc/passwd 파일 권한 상승 탐구                  | 중급     | <a target='_blank' href='https://labex.io/ko/labs/explore-privilege-escalation-via-etc-passwd-file-in-nmap-416141?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                 |
|       03 | 🧩  Linux 에서 /etc/shadow 파일을 이용한 권한 상승                  | 초급     | <a target='_blank' href='https://labex.io/ko/labs/escalate-privileges-using-etc-shadow-file-in-linux-416142?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                       |
|       04 | 🧩  Linux 에서 SUID 바이너리 악용하여 권한 상승                     | 초급     | <a target='_blank' href='https://labex.io/ko/labs/nmap-exploit-suid-binaries-for-privilege-escalation-in-linux-416147?course=privilege-escalation-techniques-on-linux'>실습 시작</a>             |
|       05 | 🧩  Nmap 에서 Cron Job 및 권한 상승 학습                            | 초급     | <a target='_blank' href='https://labex.io/ko/labs/learn-cron-jobs-and-privilege-escalation-in-nmap-416140?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                         |
|       06 | 🧩  Nmap 와일드카드 인젝션을 이용한 권한 상승 실습                  | 초급     | <a target='_blank' href='https://labex.io/ko/labs/perform-wildcard-injection-in-nmap-for-privilege-escalation-416144?course=privilege-escalation-techniques-on-linux'>실습 시작</a>              |
|       07 | 🧩  Nmap 환경에서 Sudo 권한 상승 방법 배우기                        | 초급     | <a target='_blank' href='https://labex.io/ko/labs/learn-sudo-privilege-escalation-methods-in-nmap-416145?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                          |
|       08 | 🧩  Nmap 에서 민감한 설정 파일 찾기 및 악용을 통한 권한 상승        | 초급     | <a target='_blank' href='https://labex.io/ko/labs/find-and-exploit-sensitive-config-files-for-privilege-escalation-in-nmap-416138?course=privilege-escalation-techniques-on-linux'>실습 시작</a> |
|       09 | 🧩  Nmap 을 이용한 중간 사용자 경유 Root 권한 상승                  | 초급     | <a target='_blank' href='https://labex.io/ko/labs/nmap-escalate-privileges-to-root-via-intermediate-user-in-nmap-416146?course=privilege-escalation-techniques-on-linux'>실습 시작</a>           |
|       10 | 🧩  Sucrack 및 Hydra 를 사용한 Linux Root 비밀번호 무차별 대입 공격 | 초급     | <a target='_blank' href='https://labex.io/ko/labs/brute-force-root-password-in-linux-with-sucrack-and-hydra-416139?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                |
|       11 | 🧩  Nmap 을 활용한 Linux 권한 상승 도구 탐구                        | 초급     | <a target='_blank' href='https://labex.io/ko/labs/explore-linux-privilege-escalation-tools-in-nmap-416143?course=privilege-escalation-techniques-on-linux'>실습 시작</a>                         |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

## 더 보기

- 🔗 [Cybersecurity 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [Cybersecurity 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Cybersecurity 무료 튜토리얼](https://github.com/labex-labs/cybersecurity-free-tutorials)

