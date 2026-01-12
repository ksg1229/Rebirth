# Rebirth (리버스)

## ♻️ 프로젝트 소개
Rebirth는 중고 거래와 기부를 통해 자원 순환을 촉진하는 친환경 플랫폼입니다.
사용자는 옷장(Wardrobe) 기능을 통해 보유한 의류를 관리하고, OOTD를 공유하며, 안 입는 옷을 판매하거나 기부할 수 있습니다.
AI 분석 기능을 활용하여 의류를 효율적으로 관리하고 추천받을 수 있습니다.

## 🛠 기술 스택 (Tech Stack)
- **Backend**: Java 17, Spring Boot, Spring Security, OAuth2, MyBatis, JPA
- **Database**: Oracle, Milvus (Vector DB for AI)
- **Frontend**: Thymeleaf, HTML/CSS/JS
- **Communication**: WebSocket (Chat)
- **Deployment**: Cloudflare Tunnel

## 🌟 주요 기능 (Key Features)
- **Market (중고 거래)**: 개인 간 중고 의류 거래
- **Donation (기부)**: 의류 기부 및 자원 순환 참여
- **Wardrobe (나만의 옷장)**: 디지털 옷장 관리 및 분류
- **OOTD (Outfit Of The Day)**: 스타일 공유 및 커뮤니티
- **Chat (채팅)**: 실시간 거래 채팅
- **AI Analysis**: 의류 분석 및 추천 (Milvus 활용)

## ⚠️ 주의사항
`config.yml`, `cloudflared.exe` 및 API 키가 포함된 민감한 파일은 저장소에 포함되지 않습니다.
프로젝트 실행 시 해당 파일들이 필요할 수 있습니다.
