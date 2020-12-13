# hello world



## table of contents
- [homebrew setting](#homebrew-setting)
- [project setting](#project-setting)
- [project project](#project-project)
- [init project](#init-project)

- 아이폰 375px에 대한 css layout 미리 잡아놓기
- scss 파일로 UI 부품 미리 만들어놓기


## homebrew setting
1. [기본 shell을 zsh shell로 변경](#zsh-shell-setting)
1. [homebrew 설치](#homebrew-setting)
1. [nodejs 설치](#nodejs-setting)

### zsh shell setting
현재 사용 중인 `shell` 확인 명령어를 통해 `zsh shell`로 확인되면 이 부분은 skip

```bash
echo $SHELL
bin/zsh
```

출처 
- [배워서 남주자](https://countryxide.tistory.com/135 )
- [zsh 설치](https://tutorialpost.apptilus.com/code/posts/tools/mac-cli-with-iterm2-zsh/)


### homebrew setting

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### nodejs setting

```bash
brew install node

# nodejs 설치 확인
node -v
npm -v
```

```bash
brew install yarn

# yarn 설치 확인
yarn -v

# homebrew 최신 버전 업데이트
brew update

# brew를 통해 node와 yarn 업데이트 하기
brew upgrade node brew upgrade
```


## project setting
`@vue/cli`의 버전을 `v4.5.0`로 업데이트 해야 `Vue3`를 사용할 수 있다고 하는 것 같은데, 대신 npx를 사용하면 최신 패키지를 사용할 수 있습니다. 

```
npx @vue/cli create hello-world
```

### 설치할 패키지

```bash
yarn add -D @vue/cli-plugin-babel @vue/cli-plugin-eslint @vue/cli-plugin-unit-jest @vue/cli-service @vue/eslint-config-prettier @vue/test-utils babel-eslint eslint eslint-plugin-prettier eslint-plugin-vue prettier vue-template-compiler
```


## init project

```bash
git clone https://github.com/imseongtae/vue3-todo-app.git
```

출처
- [vue3 init project setting](#https://github.com/imseongtae/vue3-todo-app.git)




