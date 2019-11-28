# 2019-Fall-Autonomous-navigation-of-UAV
항법시스템 공유 자료실입니다.

우리의 목적은 무인항공기 특히 드론을 자율적으로 운행하는데 필요한 학문적 배경과 구현기술을 습득하는데 있습니다.

- 드론 자율 항법을 위한 기초 배경 지식
- 드론 시뮬레이터를 통한 자율 항법 기술 
- 자율 비행을 위한 프로그래밍 환경 지식
- 자율 비행 프로그램 개발 환경 지식

(알림) 아래의 자료가 인용되었음을 알려드립니다. 공개자료 및 공개강의를 해주신 분들께 감사드립니다. 

# 참고 교제
- https://www.slideshare.net/corradosantoro/quadcopter-31045379?from_action=save ***
- Reception & Navigation: http://www.kmooc.kr/courses/course-v1:SEOULTECHk+SMOOC04k+2019_T4/course/ ****
- Robotics: http://www.kmooc.kr/courses/course-v1:SEOULTECHk+SMOOC01k+2019_T1/course/ ****
- ROS 프로그래밍 : https://community.robotsource.org/t/download-the-ros-robot-programming-book-for-free/51 ***
- ROS 세미나(한글) : https://github.com/robotpilot/ros-seminar
- ROS 자료 : https://www.slideshare.net/yoonseokpyo/20160420-ros-3-for *****

# 참고 사이트
- px4 flight controller - https://docs.px4.io/v1.9.0/en/
- PX4: https://learn.subak.io/px4-workbook/%EB%93%9C%EB%A1%A0-%EC%88%98%ED%95%99%EA%B3%BC-%EB%AC%BC%EB%A6%AC.html **
- PID: https://kr.mathworks.com/videos/understanding-pid-control-part-1-what-is-pid-control--1527089264373.html

- ROS Academy: https://www.robotigniteacademy.com/en/course/programming-drones-with-ros_24_0/

- A* : https://deliorange.tistory.com/110

- MAVROS : https://drive.google.com/open?id=1CY8M92fLx-RCFTX_ebZ9koqYdyfQjFEU

# 발표 자료
- 제1강 : https://docs.google.com/presentation/d/1H3LbR9sGhbTsfxKWClXYj89ZIbDb8IHu9kcY1DyOrUU/edit#slide=id.g5fb61c6c87_0_657
- 제2강 : https://docs.google.com/presentation/d/1YGXdEjplx9lHwzKUGY19pDHiHzNqxJs4riiaLrYcbkA/edit?usp=sharing
- 제3강 : https://docs.google.com/presentation/d/1G1nGTSBL6nk6_cV4LaZAPIzfJ0H0azpPFDm36gyVjQE/edit?usp=sharing
- 제4강 : https://docs.google.com/presentation/d/1_ZfR2plHk_H76AuPWox4AGdTTE_pExbx_sevQwWoYfo/edit?usp=sharing
- 제5강 : https://docs.google.com/presentation/d/1nF69hRlfswlPcYl4WTn1v_JqXWywFSosjYgmmuzTHr4/edit?usp=sharing
- 제6강 : https://docs.google.com/presentation/d/1XxN0bKQSqL7yZthRuMkJLcrl9-Lqc2vmJPsue1uLdOs/edit?usp=sharing
- 제7강 : https://docs.google.com/presentation/d/18bwfqdML26kkkvBxnmeah_I3qVO48oKBnPJ_r-nuDQo/edit?usp=sharing
- 제8강 : https://docs.google.com/presentation/d/1X8rLXU4qwRsQ8K5ZtzVHzmsAFfTPLrPvxT9m8P7h3Y4/edit?usp=sharing
- 제9강 : https://docs.google.com/presentation/d/1BRJv8CadqPi58Z-uOiAogoO7vdLgjcNgqgtU152oCQ0/edit?usp=sharing
- 제10강: https://docs.google.com/presentation/d/13iw9kzgyPlVepM5bEGxS_LrlqSrN-oYq6HhZscQh4lQ/edit?usp=sharing
- 제11강: https://docs.google.com/presentation/d/1xCHbou5WN-mZJFO9a6bwsyu3iESSshbrvMpL9ulx5AI/edit?usp=sharing
- 제12강: https://docs.google.com/presentation/d/16X5bDge_7onF6eeB5rD9ymjprqWrfnuAUG9EFSrbyzk/edit?usp=sharing
- 제13강: https://docs.google.com/presentation/d/1E_B1I7a5KaBt0MBvfhpHXYU2k7CD_WSzR3v6htn9Aiw/edit?usp=sharing


- *발표 : https://docs.google.com/presentation/d/1E_B1I7a5KaBt0MBvfhpHXYU2k7CD_WSzR3v6htn9Aiw/edit?usp=sharing
- *과제 : Google Teachable Machine 실습 - 위 발표자료에 결과( 서비스주소, 서비스실행결과사진 ) 등록요망. 참고자료 -  https://teachablemachine.withgoogle.com/ , https://www.youtube.com/watch?v=USQGTW34lO8
  

* 실습용 도커 이미지 : https://cloud.docker.com/u/dsyou20/repository/docker/dsyou20/afdev
  
 
# 기초 수학
- 삼각함수 : https://j1w2k3.tistory.com/879
- 회전변환 : https://suhak.tistory.com/387
- 벡터 : https://hyner.tistory.com/131
- 행렬연산 : https://ratsgo.github.io/linear%20algebra/2017/03/14/operations/
- 조건부확률 : https://www.mathfactory.net/11235
- 머신러닝확률 : https://taeoh-kim.github.io/blog/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%97%90%EC%84%9C%EC%9D%98-%ED%99%95%EB%A5%A0-%EB%B6%84%ED%8F%AC-%EB%9E%9C%EB%8D%A4-%EB%B3%80%EC%88%98-%EA%B7%B8%EB%A6%AC%EA%B3%A0-maximum-likelihood/


