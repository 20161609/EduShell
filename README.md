# EduShell

이 프로젝트는 엑셀 파일로부터 데이터를 읽어와 사용자와 상호작용할 수 있는 교육 도구입니다. 사용자는 커맨드 기반 쉘 인터페이스를 통해 질문을 조회하고, 퀴즈 형식으로 학습할 수 있습니다.

## 주요 기능

- **정보 조회**: `CONTENTS` 디렉토리에 저장된 엑셀 파일에서 데이터를 로드하여 질문과 답변 형식으로 제공합니다.
- **쉘 인터페이스**: 사용자는 `cd`, `ls`, `quiz` 등의 명령어를 사용하여 데이터를 탐색하고 질문에 답할 수 있습니다.
- **퀴즈 모드**: 사용자는 퀴즈 모드에서 무작위로 선택된 질문에 답할 수 있으며, 학습 효과를 극대화할 수 있습니다.

## 설치 방법

이 애플리케이션을 사용하기 위해 다음 단계를 따르세요:

1. **레포지토리 클론**:
   ```bash
   git clone https://github.com/20161609/EduShell.git
   ```
2. **애플리케이션 실행**:
   ```bash
   main.exe
   ```

## 사용 방법

### 명령어

- `cd <directory>`: 현재 경로를 변경합니다.
- `ls`: 현재 경로의 내용을 리스트업합니다.
- `quiz <number>`: 지정된 수의 질문으로 퀴즈를 시작합니다.
- `q!, Q!, quit, QUIT`: 애플리케이션을 종료합니다.

### 예시

1. **컨텐츠 유형 보기**:
   ```
   [$/Home/]>> ls
   ```

2. **특정 컨텐츠 유형으로 이동**:
   ```
   [$/Home/]>> cd 1
   ```

3. **퀴즈 시작**:
   ```
   [$/Home/OS/]>> quiz 5
   ```

이 문서는 프로젝트의 시작점으로 사용될 수 있으며, 필요에 따라 추가 섹션과 내용을 확장할 수 있습니다. 사용자의 요구와 프로젝트의 발전에 따라 README는 계속 업데이트되어야 합니다.