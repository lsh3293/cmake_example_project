cmake_minimum_required(VERSION 3.13) #cmake minimum version

# PROJECT_NAME = "cmake_project_exmaple"
set(PROJECT_NAME cmake_project_example)
# CMAKE로 시작하는 변수는 글로벌 변수들
# C++ 17 사용한다는 의미
set(CMAKE_CXX_STANDARD 17) # CMAKE_CXX_STANDARD = 17

project(${PROJECT_NAME}) # 프로젝트 선언
add_executable(${PROJECT_NAME} src/main.cpp) # 실행파일을 만들 때 컴파일할 파일

