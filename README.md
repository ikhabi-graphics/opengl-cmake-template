# Learn OpneGL

[Learn OpenGL](https://learnopengl.com/) 사이트에서 보고, 듣고, 느끼고, 배우는 것들을 기록

위 사이트를 기반으로 OpenGL을 바로 시작하기 위한 CMake template.


# Prerequisite

| Library | Version |
|:--------|--------:|
| GLAD    |     3.3 |
| GLFW    |   3.3.8 |
| GLM     | 0.9.9.8 |


# Build

JesBrains의 CLion에서 빌드

- Clone OpenGL project
```commandline
$ git clone git@github.com:ikhabi-graphics/opengl-cmake-template.git
$ git submodule update --init --recursive --remote
```

- Update Libraries Tag
```commandline
# GLFW
$ cd external/glfw
$ git checkout tags/3.3.8

# GLM
$ cd external/glm
$ git checkout tags/0.9.9.8
```

- CLion에서 프로젝트 폴더 열기
- Run Project
