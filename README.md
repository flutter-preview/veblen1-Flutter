# Flutter

https://www.youtube.com/watch?v=mLQ-ehf3d6Y&list=PLfLgtT94nNq1izG4R2WDN517iPX4WXH3C&index=2

기초위젯 4

<br><br>

# 기본

Flutter의 사이즈는 "LP" 기준

'<div>' 와 같이 위젯안에 위젯으로 child식으로!

<br><br>


# Lint 끄기

Lint : 린트 또는 린터는 소스 코드를 분석하여 프로그램 오류, 버그, 스타일 오류, 의심스러운 구조체에 표시를 달아놓기 위한 도구들을 가리킨다.
=> 좋은 관습같은거 잡아줌. 개발자 코드 스타일 통일

  rules: <br>
    prefer_typing_uninitialized_variables: false <br>
    prefer_const_constructors: false <br>
    prefer_const_constructors_in_immutables: false <br>
    avoid_print: false

<br><br>

# pubspec.yaml

이름, 설명, 버전 등과 같은 메타데이터와 함께 프로젝트의 의존성(dependencies)을 선언합

name: Flutter 프로젝트의 이름입니다.

description: Flutter 프로젝트의 간략한 설명입니다. 이것은 보통 프로젝트가 무엇인지 간략하게 설명하는 한 두 문장으로 이루어집니다.

version: 프로젝트의 버전입니다. 일반적으로 이는 Semantic Versioning 규칙을 따릅니다.

environment: 프로젝트가 호환되는 Dart SDK의 버전 범위를 지정합니다.

dependencies: 프로젝트에서 사용하는 외부 패키지의 목록과 각 패키지의 버전 정보를 포함합니다. 예를 들어, Flutter 프레임워크 자체와 Cupertino Icons 패키지는 기본적으로 여기에 포함되어 있습니다.

dev_dependencies: 개발 과정에서만 필요한 의존성을 나열합니다. 예를 들어, 단위 테스트 라이브러리는 이 곳에 위치합니다. 이러한 의존성은 프로덕션 앱에는 포함되지 않습니다.

flutter: Flutter 관련 설정을 포함합니다. 예를 들어, 여기에는 사용하는 asset(이미지, 폰트 등)이나 기본 Android, iOS 타겟 설정 등이 포함됩니다.



