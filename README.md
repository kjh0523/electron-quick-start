# Electron 빠른시작

**Electron이 어떻게 실행되는지 빠르게 확인하려면 복제하고 실행 하십시오.**

이것 Electron 문서화에 포함된, 작은 [빠른 시작 가이드](https://electronjs.org/docs/latest/tutorial/quick-start)에 기반  Electron 작은 애플리케이션이다. 

Electron 기본 어플리케이션은 아래 파일들을 필요로 한다.:

- `package.json` - 앱의 main 파일을 설정하고 상세한내용을 정의하고, 의존성 패키지들을 설정한다.
- `main.js` - HTML파일을 표현하기 위해서 앱을 시작하고, 브라우저를 만든다. 이것은 앱의 **main 프로세스**이다.
- `index.html` - 웹페이지를 표현하기 위한 프로그램 이것은 프로그램의 **renderer 프로세스**이다.
- `preload.js` - **renderer 프로세스**가 로드 되기 전에 실행되는 콘텐츠 스크립트.

각 컴포넌트에 대해서 좀 더 깊이 있게 살펴보려면 [Tutorial](https://electronjs.org/docs/latest/tutorial/tutorial-prerequisites) 을 참조 하십시오.

## 사용하기

이 레파지토리를 복제하고 실행하기 위해서 [Git](https://git-scm.com)과 [Node.js](https://nodejs.org/en/download/) ([npm](http://npmjs.com)과 함께)가 컴퓨터에 설치 되어 있어야 한다. 실행하기 위한 커맨드는 아래와 같다.:

```bash
# 이 레포지토리를 복제 하십시오
git clone https://github.com/kjh0523/electron-quick-start
# 레포지토리로 이동 하십시오.
cd electron-quick-start
# 의존성 관련 라이브래리를 설치하십시오.
npm install
# 앱을 실행 하십시오.
npm start
```

Note: 만약 윈도우즈에서 리눅스 Bash를 사용하기를 원한다면 , [이가이드를 보거나](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) 도는 커맨드프롬프트에서 npm을 사용하십시오.

## Electron을 공부하는데 필요한 자료들

- [electronjs.org/docs](https://electronjs.org/docs) - Electron 문서화의 모든 것
- [Electron Fiddle](https://electronjs.org/fiddle) - 작은 애플리케이션들을 실행해 볼 수 있는 Electron Fiddle


## 라이센스

[CC0 1.0 (Public Domain)](LICENSE.md)
