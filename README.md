



[00:00:00] Build started
[00:00:01] git clone -q --branch=master https://github.com/EleonoraPopushoi/CI-api.git /home/appveyor/projects/ci-api
[00:00:02] git checkout -qf d200ef83c1b7f2db49b392ebc3d5970d82f064f2
[00:00:02] Configuring 'stack'
[00:00:02] Enabling JDK 11
[00:00:02] Running "install" scripts
[00:00:02] java -jar ./artifacts/app-mbank.jar &
[00:00:02] Picked up JAVA_TOOL_OPTIONS: -Dfile.encoding=UTF8
[00:00:02] Running "build_script" scripts
[00:00:02] ./gradlew test --info
[00:00:02] /opt/appveyor/build-agent/bash-shell.sh: line 51: ./gradlew: Permission denied
[00:00:02] Command exited with code 126
[00:00:02] Build failed
