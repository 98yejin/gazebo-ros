# gazebo-ros
gazebo에서 model움직이게 하기

>> cd ~
>> mkdir -p .gazebo/models/test
>> cd .gazebo/models/test

model

>> gedit ~/.gazebo/models/model.config
>> gedit ~/.gazebo/models/model.sdf

world

>> cd ~
>> mkdir test01
>> cd test01
>> gedit test01.world

plugin

>> cd ~/test01
>> gedit test_spin.cc
>> gedit CMakeLists.txt

compile

>> mkdir build
>> cd build
>> cmkae ../
>> make

execute

>> cd ..
>> gazebo -u test01.world







참고 및 출처 ros 오로카 카페의 김성준님 게시글 간장공장공장장 vol.3 링크 두 개와 조인트 하나 https://cafe.naver.com/openrt/8610

