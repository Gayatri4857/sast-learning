docker build -t dnyanyog.org/gitleaks:latest -f dockerfile .

Go to root folder of repo (command must run at .git folder level)
    docker run -it --rm -v "$(pwd)":/path dnyanyog.org/gitleaks:latest detect -v
