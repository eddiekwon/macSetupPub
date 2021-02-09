## Brew설치법

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

m1 arm인 경우  에러가 나오면 아래처럼 타이핑하면 됨

echo "export PATH=/opt/homebrew/bin:$PATH" >> ~/.zshrc

## oh-my-zsh 설치
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

## theme 설정하기
agnoster설정함

## 폰트깨짐 수정 
D2CodingLigature 등의 폰트를 설치함

## color preset 설정하기
https://iterm2colorschemes.com
scheme 폴더에 있느 파일들 import시키면 됨

## 맥 터미널 커맨드라인 단축키
ctrl + A : 라인 맨 앞으로 커서 이동
ctrl + E : 라인 맨 뒤로 커서 이동
ctrl + L : clear.
ctrl + d : delete.
ctrl + k : 현재 커서부터 해당 라인 끝까지 텍스트 삭제

