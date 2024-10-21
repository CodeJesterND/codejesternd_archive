## iTerm2 설치

```
$ brew install iterm2
```

<br/>

## Oh-My-Zhs 설치

```
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

<br/>

## 커스터마이징

### 테마 변경

- [테마 목록](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)

```
$ vi ~/.zshrc
```

- 글쓴이는 powerlevel10k 테마 선택.

```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

### 테마 설정

```
Prompt Style : Rainbow Character
Set : (1) Unicode
Show current time? : 24-hour format
Prompt Separators : Angled Prompt
Heads : Sharp Prompt
Tails : Flat
Prompt Height : One line
Prompt Spacing : Sparse
Icons : Many icons
Prompt Flow : Concise
Enable Transient Prompt? : N
Instant Prompt Mode : Verbose
Apply changes to ~/.zshrc? : y
```

### 상태바 활성화

- iTerm2 > Preferences > Profiles > Session > Status bar enabled

- Preferences > Appearance > Status bar location > Bottom

<br/>

## 플러그인 설치

### 자동 완성 기능

- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

```
$ git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```
$ vi ~/.zshrc
```

```
plugins=(
		# other plugins...
		zsh-autosuggestions
)
```

### 명령어 하이라이트 기능

- [zsh-syntax highlighter](https://github.com/zsh-users/zsh-syntax-highlighting)

```
$ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

```
$ vi ~/.zshrc
```

```
plugins=(
		# other plugins...
		zsh-syntax-highlighting
)
```

### 터미널 프로필 기능

- [neofetch](https://github.com/dylanaraps/neofetch)

```
$ brew install neofetch
```
