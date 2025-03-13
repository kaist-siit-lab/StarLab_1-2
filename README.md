본 연구는 2024년도 정부(과학기술정보통신부)의 재원으로 정보통신기획평가원의 지원을 받아 수행된 연구임

(RS-2024-00439020, 지속가능한 실시간 멀티모달 인터렉티브 생성 AI 개발, SW컴퓨팅산업원천기술개발사업 (SW스타랩))

# Abstract here

# Official Code Implementation of StablePrompt

To reproduce the experiments in the paper, follow the sequences below:

## Setting Up the Environment
```bash
docker run pytorch:latest
pip install -r requirements.txt
git clone https://github.com/keirp/automatic_prompt_engineer.git
```
## Experiment 4.1: Few-shot Text Classification
```bash
./run_fewshot.sh
```

## Experiment 4.2: Induction Task
```bash
./run_BBII.sh
./run_II.sh
```

## Experiment 4.3: Question Answering
```bash
./run_QA.sh
```
