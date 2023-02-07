# Electron 빠른시작

**Electron이 어떻게 실행되는지 빠르게 확인하려면 복제하고 실행 하십시오.**

이것 Electron 문서화에 포함된, 작은 [빠른 시작 가이드](https://electronjs.org/docs/latest/tutorial/quick-start)에 기반  Electron 작은 애플리케이션이다. 

Electron 기본 어플리케이션은 아래 파일들을 필요로 한다.:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.
- `preload.js` - A content script that runs before the renderer process loads.

각 컴포넌트에 대해서 좀 더 깊이 있게 살펴보려면 [Tutorial](https://electronjs.org/docs/latest/tutorial/tutorial-prerequisites) 을 참조 하십시오.

## 사용하기

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

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
