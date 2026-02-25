SonarQube Korean Language Pack / SonarQube 한국어 언어 팩
==========================================================

[![Build Status](https://github.com/sonar-l10n-ko/sonar-l10n-ko/actions/workflows/build.yml/badge.svg)](https://github.com/sonar-l10n-ko/sonar-l10n-ko/actions/workflows/build.yml)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

[English](#english) | [한국어](#한국어)

---

## English

This is the Korean language pack for [SonarQube](https://www.sonarqube.org/).

### Compatibility Matrix

| **SonarQube** | **25.12** |
|---------------|-----------|
| sonar-l10n-ko | 25.12     |

### Installation

1. Download the latest JAR from the [Releases](https://github.com/sonar-l10n-ko/sonar-l10n-ko/releases) page.
2. Copy the JAR file to the `extensions/plugins` folder of your SonarQube installation.
3. Restart SonarQube.

### Build

Requirements: JDK 17, Maven 3.x

```bash
mvn clean package
```

The built plugin JAR will be located in the `target/` directory:
`target/sonar-l10n-ko-plugin-25.12-SNAPSHOT.jar`

### Contributing

Contributions are welcome! Please open an [issue](https://github.com/sonar-l10n-ko/sonar-l10n-ko/issues) or pull request.

Translation strings are in `src/main/resources/org/sonar/l10n/core_ko.properties`.

### Credits

This project is inspired by and based on:
- [sonar-l10n-zh](https://github.com/xuhuisheng/sonar-l10n-zh) — Chinese Language Pack by Xu Huisheng
- [sonar-l10n-ja](https://github.com/cresco-sonar/sonar-l10n-ja) — Japanese Language Pack

### License

This project is licensed under the [GNU Lesser General Public License v3.0](LICENSE).

---

## 한국어

[SonarQube](https://www.sonarqube.org/) 한국어 언어 팩입니다.

### 호환성 매트릭스

| **SonarQube** | **25.12** |
|---------------|-----------|
| sonar-l10n-ko | 25.12     |

### 설치 방법

1. [Releases](https://github.com/sonar-l10n-ko/sonar-l10n-ko/releases) 페이지에서 최신 JAR 파일을 다운로드합니다.
2. JAR 파일을 SonarQube 설치 디렉토리의 `extensions/plugins` 폴더에 복사합니다.
3. SonarQube를 재시작합니다.

### 빌드 방법

요구사항: JDK 17, Maven 3.x

```bash
mvn clean package
```

빌드된 플러그인 JAR 파일은 `target/` 디렉토리에 생성됩니다:
`target/sonar-l10n-ko-plugin-25.12-SNAPSHOT.jar`

### 기여 안내

이슈 또는 풀 리퀘스트를 통해 기여해 주세요.

번역 문자열은 `src/main/resources/org/sonar/l10n/core_ko.properties` 파일에 있습니다.

### 감사의 말

이 프로젝트는 다음 프로젝트를 참고하여 제작되었습니다:
- [sonar-l10n-zh](https://github.com/xuhuisheng/sonar-l10n-zh) — Xu Huisheng의 중국어 언어 팩
- [sonar-l10n-ja](https://github.com/Blackmorse/sonar-l10n-ja) — 일본어 언어 팩

### 라이선스

이 프로젝트는 [GNU Lesser General Public License v3.0](LICENSE) 라이선스 하에 배포됩니다.
