`JRE(Java Runtime Environment)`는 컴퓨터의 운영체제 소프트웨어 상에서 실행되고 클래스 라이브러리 및 특정 Java 프로그램이 실행해야 하는 기타 리소스를 제공합니다. Java 프로그램을 개발하기 위해선 필요한 세 개의 상호 연관된 컴포넌트가 있는데, 그중 하나가 JRE입니다. 그 외에는 JDK, JVM이 있습니다.

JRE는 모든 운영체제에서 `Java 기반 애플리케이션의 실행을 가능하게 하는 런타임 환경을 구축`합니다. 

JRE 아키텍처의 구성 요소로는 클래스로더, 바이트코드 검증기, 인터프리터가 있습니다.

- 클래스로더: Java 클래스로더는 Java 프로그램의 실행에 필요한 모든 클래스를 동적으로 로드합니다. Java 클래스는 필요 시에만 메모리에 로드되기 때문에, JRE는 클래스로더를 사용해서 요청 시에 이 프로세스를 자동화합니다.

- 바이트코드 검증기: 바이트코드 검증기는 인터프리터에 전달되기 전에 Java 코드의 형식과 정확성을 보장합니다. 코드가 시스템 무결성 또는 액세스 권한을 위반하는 경우엔 클래스가 손상된 것으로 간주되어 로드되지 않습니다.

- 인터프리터: 바이트코드의 로드에 성공한 후, 인터프리터는 Java 프로그램이 기본 시스템에서 기본적으로 실행될 수 있도록 해주는 JVM의 인스턴스를 작성합니다.