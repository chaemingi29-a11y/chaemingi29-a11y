# 채민기 | Mingi Chae

`AI & Software Developer` · `Hanbat National University`

> 모델이 왜 실패하는지 분석하고, 실험을 통해 개선 방법을 찾습니다.

[![Portfolio](https://img.shields.io/badge/Personal_Portfolio-158C9C?style=for-the-badge&logo=githubpages&logoColor=white)](https://chaemingi29-a11y.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chaemingi29-a11y)

## 01 — Research focus

| Area | Interests |
| :--- | :--- |
| Reinforcement Learning | 정책 학습, 행동 선택, 실패 분석 |
| Computer Vision | 딥러닝 기반 영상 분석 및 모델 해석 |
| 3D Geometry | 점군 이상치 제거, 형상 피팅, 법선 추정 |

## 02 — Selected research

### [Craftax · Resource-Aware Skill](https://github.com/Gyeometry/Craftax-Resource-Aware-Skill)

**Collaborative research** · Reinforcement Learning

Craftax 환경에서 철 도구 제작에 필요한 자원을 가지고도 제작 가능한 상태를 구성하지 못하는 정책의 한계를 분석한 공동 연구입니다. 기존 PPO-RNN을 다시 학습하지 않고, 필요한 순간에만 별도의 상태 구성 Skill을 개입시키는 방법을 다룹니다.

**Approach**

- Invalid Action Masking을 적용한 PPO-RNN을 기본 정책으로 사용
- Planner 시연을 활용한 CNN-GRU Skill 학습
- 보유 자원과 설비 설치 비용을 고려해 Skill 개입 여부 결정

**Team experiment highlights**

<table>
<tr><th>Mean Raw Return</th><th>Iron Pickaxe</th><th>Iron Sword</th></tr>
<tr><td><b>14.27 → 14.50</b></td><td><b>158 → 569</b></td><td><b>151 → 653</b></td></tr>
</table>

조건당 4,096게임에서 평가된 팀 전체의 결과입니다.

[Source code](https://github.com/Gyeometry/Craftax-Resource-Aware-Skill) · [Architecture](https://github.com/Gyeometry/Craftax-Resource-Aware-Skill/blob/main/docs/ARCHITECTURE.md) · [Experiment results](https://github.com/Gyeometry/Craftax-Resource-Aware-Skill/blob/main/docs/RESULTS.md)

<sub>공동 연구 결과를 소개하며, 개인 단독 성과나 논문 게재 확정을 의미하지 않습니다. 코드와 연구 자료의 이용 조건은 원본 저장소의 라이선스를 따릅니다.</sub>

## 03 — Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**AI & Development**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)

---

Learning through research, one experiment at a time.
