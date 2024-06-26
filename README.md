1 특징 정의


이 프로그램은 OpenCV를 이용하여 그래픽 사용자 인터페이스(GUI)를 제공하며, 사용자가 그림을 그릴 수 있는 캔버스와 다양한 기능 버튼을 제공합니다. 주요 기능은 다음과 같습니다.


● 그림 그리기: 마우스를 이용해 캔버스에 자유롭게 그림을 그릴 수 있습니다.

● 저장(Save): 현재 캔버스의 그림을 파일로 저장합니다.

● 불러오기(Load): 저장된 그림 파일을 캔버스로 불러옵니다.

● 지우기(Clear): 캔버스를 초기 상태로 되돌립니다.

● 실행(Run): 그림의 외곽선을 감지하고, 숫자를 인식하여 결과를 출력합니다.

● 종료(Exit): 프로그램을 종료합니다.

● 외곽선(contour): 그림의 외곽선을 감지하여 개수를 출력합니다.

● 바운딩 박스(bound): 외곽선의 바운딩 박스를 표시해 결과를 출력합니다.

● 중심 찾기(center): 외곽선의 중심 좌표를 찾아 표시합니다.


2 알고리즘 순서도


1. 프로그램 시작

2. OpenCV 윈도우 및 캔버스 초기화

3. 마우스 콜백 함수 설정

4. 사용자 입력 대기 (저장, 불러오기, 지우기, 실행, 종료, 외곽선, 숫자 인식, 중심 찾기 기능)

5. 기능 실행

6. 결과 출력

7. 프로그램 종료


3 결과 분석


● 저장(Save): 사용자가 입력한 파일명으로 현재 캔버스 상태를 저장합니다. 저장 후, "파일이 저장됨" 메시지가 출력됩니다.

● 불러오기(Load): 사용자가 입력한 파일명을 읽어와 캔버스에 표시합니다. 불러오기 성공 시, "파일을 불러옴" 메시지가 출력됩니다. 실패 시, "파일을 불러올 수 없습니다." 메시지가 출력됩니다.

● 지우기(Clear): 캔버스를 초기 상태로 되돌리고, "입력창 삭제됨" 메시지가 출력됩니다.

● 실행(Run): 그림의 외곽선을 감지하고, 인식된 숫자를 출력합니다. 인식된 숫자가 없을 경우, "인식된 숫자가 없습니다." 메시지가 출력됩니다.

● 외곽선(contour): 그림의 외곽선을 감지하고, 외곽선의 개수를 출력합니다.

● 바운딩 박스(bound): 외곽선의 무게 중심을 이용해 바운딩 박스를 표시하고, 결과를 출력합니다.

● 중심 찾기(center): 외곽선의 중심 좌표를 찾아 표시하고, 각 숫자 영역의 중심 좌표를 출력합니다.
