---
title: 4.2 Ubuntu 환경 세팅
---







# 1. 네트워크 연결
1. 우측 상단의 와이파이 아이콘 클릭
2. 연결할 와이파이 클릭
3. Address(IP), Netmask, Gateway, DNS 정보를 각각 입력 후 저장

<img width="597" height="309" alt="image" src="https://github.com/user-attachments/assets/14fc71e0-321e-4df3-9f34-b97f8eea3bab" />
<img width="598" height="459" alt="image" src="https://github.com/user-attachments/assets/2ee2a92e-33fc-4c01-9537-d81f0fe28640" />

<br><br>

# 2. 한글 입력기 설치
```
sudo apt update
sudo apt install -y ibus-hangul
```

<br>

- **윈도우키 - Settings - Keyboard - Input Sources에서 Korean (Hangul) 추가**
- **그 외 언어 전부 삭제**
- **오른쪽 점 3개 - Preferences**

![image](https://github.com/user-attachments/assets/fc9dbdfe-9a5a-45bf-a8e8-72ca247cc1a2){width=896 height=600}

<br>

- **Remove(R)로 모두 삭제**
- **Add(A) 누르고 한/영 키 누르기**
- **Apply(A) - OK(O)**

![image](https://github.com/user-attachments/assets/4b611dbc-1535-4058-856c-124b8136c05c){width=708 height=600}

<br><br>

# 3. GPU 설치 방법


<br><br>

# 4. Gitlab 계정 저장
```
git config --global credential.helper store
```
```
git config --global user.name "이름"
git config --global user.email "메일 
```