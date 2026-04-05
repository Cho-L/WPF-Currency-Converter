#  WPF Currency Converter

MS SQL 데이터베이스를 연동하여 통화 정보를 관리하고 환율을 계산하는 WPF 데스크톱 애플리케이션입니다.

## 주요 기능
* **환율 변환:** DB에 저장된 환율 데이터를 바탕으로 입력한 금액을 즉시 변환
* **데이터 관리:** ADO.NET을 활용하여 MS SQL 데이터베이스와 연동 (조회 및 업데이트)
* **예외 처리:** 금액 입력 시 유효성 검사 및 DB 연결 상태 확인

## 🛠 Tech Stack
* **Language:** C#
* **Framework:** .NET WPF
* **Database:** Microsoft SQL Server (LocalDB)
* **Data Access:** ADO.NET (SqlConnection, SqlCommand)

## 실행 화면
<img width="1090" height="613" alt="스크린샷(636)" src="https://github.com/user-attachments/assets/b6384823-07d0-4430-83ac-55dba5252233" />

## 설정 방법
1. 프로젝트 내 `DataBase` 폴더의 `.mdf` 파일이 정상적으로 포함되어 있는지 확인합니다.
2. `App.config` 파일의 `ConnectionString` 경로가 본인의 환경에 맞는지 확인합니다.
3. Visual Studio에서 솔루션을 빌드하고 실행합니다.
