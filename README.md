# embeddedLINUX

교재
[임베디드 리눅스 프로그래밍 완전정복](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791161752549&orderClick=LEa&Kc=)

## 삽질 모음

[p.61 crosstool-NG 설치](https://852completed.tistory.com/99)
[p.102 U-Boot 빌드](https://852completed.tistory.com/100)
[p.106 format-sdcard.sh 실행 error](https://852completed.tistory.com/101)

## 명령어 모음

* 61 Page
---

```bash
$ sudo apt-get install automake bison chrpath flex g++ git gperf gawk libexpat1-dev libncurses5-dev libsdl1.2-dev libtool python2.7-dev texinfo
```

```bash
$ sudo apt install help2man 
$ sudo apt install libtool-bin 
$ git clone https://github.com/crosstool-ng/crosstool-ng.git 
$ cd crosstool-ng/ 
$ ./bootstrap 
$ ./configure --enable-local 
$ make 
$ sudo make install
```

* 62 Page

```bash
$ ./ct-ng show-arm-cortex_a8-linux-gnueabi
```

```bash
$ ./ct-ng arm-cortex_a8-linux-gnueabi
```

* 62 Page

```bash
$ PATH=~/x-tools/arm-cortex_a8-linux-gnueabihf/bin:$PATH
```