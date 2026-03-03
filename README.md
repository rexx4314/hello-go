# Hello Go

Go 언어의 기본적인 문법과 기능을 학습하기 위한 간단한 프로젝트입니다.

## 프로젝트 설명

이 프로젝트는 Go 언어의 기본 기능을 보여주는 간단한 예제 프로그램입니다:
- 변수 선언 및 사용
- 문자열 포맷팅
- 반복문(for loop) 사용
- 기본 산술 연산

## 요구사항

- Go 1.26 이상

## 설치 방법

1. <a href="https://go.dev/doc/install" target="_blank">Go 공식 설치 페이지</a>에서 Go를 다운로드하세요
2. 설치 후 저장소 클론 또는 다운로드
2. Go가 설치되어 있는지 확인:
```bash
go version

go env GOPATH GOROOT

go env GOMODCACHE
```

## 실행 방법

프로젝트 디렉토리에서 다음 명령어를 실행하세요:

```bash
go run main.go
```

또는 빌드 후 실행:

```bash
go build
./hello-go     # Linux/macOS
.\hello-go.exe # Windows
```

## 예상 출력

```
Hello and welcome, gopher!
i = 100
i = 50
i = 33
i = 25
i = 20
```

## 프로젝트 구조

```
hello-go/
├── main.go    # 메인 프로그램 파일
├── go.mod     # Go 모듈 정의 파일
└── README.md  # 프로젝트 설명 파일
```

## 코드 설명

`main.go` 파일은 다음과 같은 기능을 구현합니다:
- `fmt` 패키지를 사용한 콘솔 출력
- 문자열 변수 선언 및 사용
- 1부터 5까지 반복하면서 100을 각 숫자로 나눈 결과 출력

## 개발 환경

- GoLand IDE를 사용하여 개발 권장
- 코드 디버깅 및 실행을 위한 IDE 기능 활용 가능

## 라이선스

이 프로젝트는 학습 목적으로 작성되었습니다.

## 유용한 명령어

```
- 실행: go run .
- 빌드: go build .
- 테스트: go test ./...
- 의존성 정리: go mod tidy
- 포맷: go fmt ./...
- 정적 체크(기본): go vet ./...
```