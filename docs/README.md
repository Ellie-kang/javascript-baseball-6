## 구현 기능 목록 ## 

# 게임 시작
* 게임 시작 문구 출력 : "숫자 야구 게임을 시작합니다."

# 랜덤 숫자 생성
* 1~9까지 랜덤으로 서로 다른 3개의 수를 생성

# 유저에게 숫자 입력받음
* 입력 문구 출력 : "숫자를 입력해주세요 :"
* 입력한 숫자 유효성 검사
* 형식이 잘못되었을 경우, 에러 문구 출력 : "[ERROR] 숫자가 잘못된 형식입니다."

# 비교
* 입력한 수에 대한 결과를 볼, 스트라이크, 낫싱 개수로 반환
* 맞는게 하나도 없는 경우 : 낫싱
* 3개 모두 맞힐 경우 문구 출력 : "3개의 숫자를 모두 맞히셨습니다! 게임 종료"

# 재시작 or 종료
* 선택 문구 출력 : "게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요."
* 1 입력 시, 재시작
* 2 입력 시, 종료
* 1 or 2 가 아닐 경우, 에러 문구 출력 : "[ERROR] 숫자가 잘못된 형식입니다."