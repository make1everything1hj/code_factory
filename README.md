# Smart Trash Can 만들기 프로젝트
AI MAKERS KIT을 이용하여 발화로 쓰레기통을 움직이는 프로젝트입니다.

![Title_image](https://github.com/make1everything1hj/code_factory/blob/master/smart_trash_can.png)
## 1. 필요 재료
> 미니 휴지통 1개
> 마이크로 서보모터 SG90 1개
> PCA9685 서보모터 컨트롤러 1개
Step-down DC-DC 컨버터 모듈 1개
18650 규격 배터리 홀더 (18650 * 2) 1개
18650 규격 배터리 1개

###
GiGA Genie AI Makers Kit 은 Raspberry Pi 와 동일한 GPIO Pinout을 제공한다.


이중 Audio Board에서 몇몇 핀을 이용하기 다음 그림의 파란색 부분은 이용 불가능한 Pin 이다. 
![usedpin](https://user-images.githubusercontent.com/16068060/42006135-02b58aaa-7ab3-11e8-94cc-da21eab6b841.png)

이중 제공되는 버튼의 제어 Pin 은 물리 Pin 의 29번(GPIO번호로는 GPIO05)이고 버튼의 LED 제어 Pin은 물리Pin의 31번(GPIO번호로는 GPIO06)이다.
