# Parking Kiosk Updates

공개 주차 인증 키오스크 업데이트 배포 저장소입니다.

이 저장소에는 고객 계정, 관리자 PIN, 영수증 기록, iParking 로그인 프로필이
포함되지 않습니다. 설치 패키지는 GitHub Releases에서 배포되며 키오스크는
`latest.json`과 SHA-256 체크섬을 확인한 뒤에만 업데이트를 적용합니다.

## Current release

- Version: `0.9.9`
- Asset: `parking-kiosk-installer.zip`
- Manifest: `latest.json`

## Manual verification

```powershell
Get-FileHash .\parking-kiosk-installer.zip -Algorithm SHA256
```

출력된 해시가 릴리스의 `SHA256SUMS.txt`와 일치해야 합니다.
