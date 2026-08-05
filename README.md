# Hi, I'm limccw 👋

![banner](./banner_pixel.png)

![Profile Views](https://komarev.com/ghpvc/?username=limccw&color=blue&style=flat)

**Plant BPI Engineer / 3D CAD Automation Developer**
I work on 3D CAD system operations, automation, and data engineering for Plant EPC projects. (~8 years of experience)

---

## 🛠 Core Focus Areas

- **3D CAD Administration & Automation**: Managing AVEVA E3D, Smart3D, and Navisworks; building in-house add-ins and automation tools
- **IM Data Management**: Tag/Property Register QC, large-scale plant data integrity validation
- **IT Lead**: Server infrastructure operations, IDC migration, license monitoring system development
- **Data Engineering & AI/ML**: SQL/Python-based pipelines, Palantir Foundry, Clash Prediction modeling

---

## 💻 Tech Stack

**Languages & DB**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)

**Plant 3D CAD / BIM**

![AVEVA E3D](https://img.shields.io/badge/AVEVA_E3D-005EB8?style=flat)
![Smart3D](https://img.shields.io/badge/Smart3D-0072C6?style=flat)
![Navisworks](https://img.shields.io/badge/Navisworks-2C2C2C?style=flat)
![AVEVA UE](https://img.shields.io/badge/AVEVA_UE-005EB8?style=flat)

**Data & AI / ML**

![ko-sroberta](https://img.shields.io/badge/ko--sroberta-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![XGBoost](https://img.shields.io/badge/XGBoost-EB0028?style=flat)
![Palantir Foundry](https://img.shields.io/badge/Palantir_Foundry-000000?style=flat)

**Infra & Automation**

![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-742774?style=flat)
![ECS](https://img.shields.io/badge/ECS-FF9900?style=flat&logo=amazonecs&logoColor=white)

---

## 📊 GitHub Stats

![Stats Board](./stats_board.png)

---

## 🚀 Featured Projects

### 🔹 AI-based Clash / QC Auto Prediction
A machine learning pipeline that embeds design data text attributes with ko-sroberta and classifies clash (interference) results using LightGBM/XGBoost. Integrated with a QC system that automatically validates large-scale missing/inconsistent data in Tag/Property Registers.

<a href="https://github.com/limccw/clash-prediction-ml">
  <img src="./sign_clash_prediction_ml.png" alt="clash-prediction-ml"/>
</a>

### 🔹 Navisworks Clash Batch Automation
An add-in that batches clash test execution via the Navisworks API and automatically applies NWD publish options and distribution security policies (End Date, re-save restrictions). Automates a clash review process that used to be done manually.

<a href="https://github.com/limccw/navisworks-clash-batch-automation">
  <img src="./sign_navisworks_clash_batch_automation.png" alt="navisworks-clash-batch-automation"/>
</a>

### 🔹 Palantir Foundry Pipeline → SQL Migration
Migrated a Python/ETL-based Foundry data pipeline to SQL-based transformations. Built a dataset integrity validation and API-based batch scheduling system using Pipeline Builder, Contour, and Data Lineage.

<a href="https://github.com/limccw/foundry-to-sql-pipeline">
  <img src="./sign_foundry_to_sql_pipeline.png" alt="foundry-to-sql-pipeline"/>
</a>

### 🔹 License / Session Monitoring
A lightweight monitoring utility that detects idle sessions in EPC-domain tools (S3D, E3D, Navisworks, etc.) and cleans them up automatically.

<a href="https://github.com/limccw/license-session-monitor">
  <img src="./sign_license_session_monitor.png" alt="license-session-monitor"/>
</a>

---

## 📫 Contact

- Location: Seoul, South Korea

---

<sub>*"Solving real-world problems through automation."*</sub>

<br>

<details>
<summary>🇰🇷 한국어로 보기</summary>

<br>

**Plant BPI Engineer / 3D CAD Automation Developer**
Plant EPC 프로젝트의 3D CAD 시스템 운영·자동화와 데이터 엔지니어링을 담당하고 있습니다. (약 8년 경력)

---

### 🛠 주요 업무 영역

- **3D CAD Administration & Automation**: AVEVA E3D, Smart3D, Navisworks 관리 및 Add-in/자동화 도구 개발
- **IM Data Management**: Tag/Property Register QC, 대규모 플랜트 데이터 정합성 검증
- **IT Lead**: 서버 인프라 운영, IDC 마이그레이션, 라이선스 모니터링 시스템 구축
- **Data Engineering & AI/ML**: SQL/Python 기반 파이프라인, Palantir Foundry, Clash Prediction 모델링

---

### 🚀 대표 프로젝트

**🔹 AI 기반 Clash / QC 자동 예측**
설계 데이터의 텍스트 속성을 ko-sroberta로 임베딩하고, LightGBM/XGBoost로 클래시(간섭) 결과를 분류하는 머신러닝 파이프라인. Tag/Property Register의 대규모 결측치·정합성 오류를 자동 검증하는 QC 시스템과 연동.
→ [clash-prediction-ml](https://github.com/limccw/clash-prediction-ml)

**🔹 Navisworks Clash Batch Automation**
Navisworks API를 활용해 클래시 테스트 실행을 배치화하고, NWD 게시 옵션·배포 보안 정책(End Date, 재저장 제한)을 자동 적용하는 애드인. 수작업으로 반복되던 클래시 검토 프로세스를 자동화.
→ [navisworks-clash-batch-automation](https://github.com/limccw/navisworks-clash-batch-automation)

**🔹 Palantir Foundry 파이프라인 → SQL 전환**
Python/ETL 기반으로 운영되던 Foundry 데이터 파이프라인을 SQL 기반 트랜스포메이션으로 전환. Pipeline Builder, Contour, Data Lineage를 활용한 데이터셋 정합성 검증 및 API 기반 배치 스케줄링 체계 구축.
→ [foundry-to-sql-pipeline](https://github.com/limccw/foundry-to-sql-pipeline)

**🔹 License / Session Monitoring**
EPC 계열(S3D, E3D, Navisworks 등) 툴의 유휴 세션을 감지해 자동 정리하는 경량 모니터링 유틸리티.
→ [license-session-monitor](https://github.com/limccw/license-session-monitor)

---

### 📫 Contact

- Location: Seoul, South Korea

---

<sub>*"현장의 문제를 자동화로 해결합니다."*</sub>

</details>
