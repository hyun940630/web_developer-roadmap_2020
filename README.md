# Web Developer - Roadmap 2020 따라가기

> [Web Developer Roadmap 2020](https://github.com/kamranahmedse/developer-roadmap)를 따라 공부합니다.



# Introduction
😎 Front-end Developer

 - Git - version control
  > Using Git - 자주 사용하는 Git 명령어 모음
  구조
  코드는 아래 세 단계에 걸쳐 저장된다.
  staging >> commit >> remote repository
  1. `git add {file name}`으로 파일을 staging 상태에 놓는다.
  2. `git commit -m "{commit message}"`으로 staging에 있는 모든 변경사항을 commit 한다.
  3. `git push`로 커밋된 저장소를 remote repository로 밀어 넣는다.
  
  기본 명령어
  Git 저장소 초기화 세팅
  `git init`
  
  원격 저장소로부터 복제
  `git clone {repo url}`
  
  변경 사항 체크(git add 이후 이전 snapshot과의 변경 사항을 보여줌)
  `git status`
  
  특정 파일 스테이징
  `git add {file name}`
  
  변경된 모든 파일 스테이징
  `git add .`
  `git add *`
  
  커밋
  `git commit -m "{commit message}"`
  
  Remote Repository에 update하기(원격 저장소로 올리기)
  `git push origin master`
  
  원격저장소 추가
  `git remote add origin {remote repo url}`
  
  
  Commit
  
  커밋 합치기
  `git rebase -i HEAD~4` // 최신 4개의 커밋을 하나로 합칩니다.
  
  커밋 메세지 수정
  `git commit --amend` // 마지막 커밋 메세지 수정(ref)
  
  간단한 commit 방법
  `git add {changed file name}`
  `git commit -m "{commit message}"`
  
  커밋 이력 확인
  `git log` // 모든 커밋 로그 확인
  `git log -3` // 최근 3개 커밋로그 확인
  `git log --pretty=oneline` // 각 커밋을 한 줄로 표시
  `git reflog` // reset 혹은 rebase로 없어진 과걱의 커밋 이력 확인
  
   커밋 취소
   `git reset HEAD^` // 마지막 커밋 삭제
   
  
  
  
  
  
 - Basic Terminal Usage
 - Data Structures & Algorithms
 - Github
 - Licenses
 - Semantic Versioning
 - SSH
 - HTTP/HTTPS and APIs
 - Design Patterns
 - Character Encordings



# Front-end Roadmap

## 1. Internet
 - How does the internet work?
 - What is HTTP?
 - Browsers and how they work?
 - DNS and how it works?
 - What is Domain Name?
 - What is hosting?
 
## 2. HTML / CSS / JavaScript
 
### HTML 
 - Learn the basics
 - Forms Semantic HTML
 - Conventions and Best Practices
 - SEO 
  
### CSS
 - Learn the basics
 - Making Layouts
 > Floats / Positioning / Box Model / CSS Grid / Flex Box
 - Responsive design and Media Queries
 
### JavaScript
 - Syntax and Basic Constructs
 - Learn DOM Manipulation
 - Learn Fetch API / Ajax(XHR)
 - ES6+ and modular JavaScript
 - Understand the concepts Hositing, Event Bubbling, Scope, Prototype, Shadow DOM, strict, ...
 
 
## Version Control Systems
 - Basic Usage of Git
 - Repo hosting Services : Create account and Learn to use GitHub
 > GitHub
 

## Web Security Knowledge
 - Get at least a basic knowledge of all of these
 > HTTPS / Content Security Policy / CORS / OWASP Security Ricks
 
 
## Package Managers
 - npm
 - yarn
 
 
## CSS Architecture
 > With modern frameworks and CSS-in-JS you don't have to worry about these anymore but still it would be a good idea to get familiarized with BEM at least.
 - BEM
 

## CSS Preprocessors
 > With how the mordern frameworks there has been more push towards CSS-in-JS so you may not need these but still a good idea to familiarize yourself.
 - Sass
 

## Build Tools
 - Task Runners
 > npm scripts
 - Module Bundlers
 > Webpack
 - Linters and Formatters
 > Prettier / ESLint
 
 
## Pick a Framework
 - React.js
 > Redux
 
 
## Modern CSS
 - Styled Component
 - CSS Module
 - styled JSX
 
 
## Web Component
 > PASS
 
 
## CSS Frameworks
 > JS based and better to use with framework based JavaScript applications.
 - Reactstrap
 - Material UI
 
 > CSS first frameworks which don't come with JavaScript components by default.
 - Bootstrap
 
 
 ## Testing your App
  > Learn th difference between Unit, Integration, and Functional tests and learn how to write them with the tools listed on the left.
  
  - Jest
  - react-testing-library
  - Cypress
  - Enzyme
  > You can fill all your testing needs with just these.
  
  
 ## Type Checkers
  - TypeScript ***
  
  
 ## Progressive Web Apps
  - ...
  
 
 ## Server Side Rendering(SSR)
  - Next.js(based React.js)
  
  
 ## GraphQL
  - Apollo
  - Relay Morden
  
  
 ## Static Site Generators
  - Next.js
  - Gatsby JS
  
 
 ## Mobile Applications
  - React Native
  
  
 ## Desktop Applications
  - Electron
