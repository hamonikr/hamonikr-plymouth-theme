## hamonikr-plymouth

하모니카 plymouth Theme

![screenshot](./screenshot.png)

### Install

```
sudo ./install
```

### Test
```
sudo ./test.sh
```

### License
[LICENSE](LICENSE)

### FAQ

#### 새로 바꾼 테마가 적용되지 않을 때
아래 명령으로 커널 이미지를 새로 생성한다.
```
sudo update-initramfs -u -k all
```

