# brew-back

# java 11 버전 설치 
- 자바 버전확인 : Java --version
- brew install openjdk@11

설치 완료 후 배치 등록
sudo ln -sfn /opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk
echo 'export PATH="/opt/homebrew/opt/openjdk@11/bin:$PATH"' >> ~/.zshrc
export CPPFLAGS="-I/opt/homebrew/opt/openjdk@11/include"

# fork 설치 : 다운로드 후 설치
github 사이트 연동 시 토큰생성 후 사용
