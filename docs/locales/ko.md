# 조효준 (Hyojun Jo)

| [KR 한국어](./ko.md) | [US English](../../README.md) | [JP 日本語](./ja.md) | [CN 简体中文](./zh-CN.md) | [ES Español](./es.md) |
| :---: | :---: | :---: | :---: | :---: |
| [FR Français](./fr.md) | [DE Deutsch](./de.md) | [RU Русский](./ru.md) | [SA العربية](./ar.md) | [IN हिन्दी](./hi.md) |

---

### 시스템 및 보안 소프트웨어 엔지니어

대한민국 서울 | Independent Systems Lab

저수준 런타임 아키텍처, 결정론적 검증 시스템, 무오버헤드(Zero-Overhead) 도구 제작, 네이티브 보안 감사를 중점적으로 연구 및 개발합니다. 예측 가능성, 하드웨어 친화적 설계(Mechanical Sympathy), 엄밀한 기계적 검증이 필수적인 고신뢰성 시스템을 구축합니다.

---

### 핵심 엔지니어링 철학

- **결정론적 정확성 (Deterministic Correctness)**: 엄격한 타입 시스템, 정형적 단언문, 재현 가능한 테스트 스위트를 통해 정의되지 않은 동작(UB)과 메모리 결함을 원천 차단합니다.
- **제로 비용 추상화 (Zero-Cost Abstractions)**: 컴파일러 최적화, 직접적 메모리 레이아웃 제어, 캐시 친화적 구조를 통해 런타임 간접 비용을 최소화합니다.
- **최소 공격 표면 (Minimal Attack Surface)**: 격리된 보안 경계, 최소 권한 원칙, 제로 트러스트 검증 메커니즘을 네트워크, 프로세스, 메모리 영역 전반에 적용합니다.
- **정공법 엔지니어링 (Orthodox Craftsmanship)**: 불필요한 서드파티 의존성과 비결정론적 휴리스틱을 배제하고, 유지보수 가능하고 투명하게 감사 가능한 코드를 작성합니다.

---

### 전문 기술 영역 및 아키텍처

| 영역 | 주요 기술 스택 | 방법론 및 표준 |
| :--- | :--- | :--- |
| **시스템 및 런타임** | Rust, Modern C++ (C++20/23), C11, Go, Assembly (x86_64, ARM64) | 메모리 관리, 비동기 실행기, 락프리 동시성 제어, 커스텀 메모리 할당자 |
| **보안 및 포렌식** | 바이너리 정찰/분석, 정적/동적 역분석, 퍼징(Fuzzing) | LLVM Sanitizers (ASan, MSan, UBSan), AFL++, 심볼 및 제어 흐름 복원 |
| **OS 및 커널 인터페이스** | Linux (eBPF, POSIX, io_uring), Windows Internals (Win32, NT API) | 시스템 콜 가로채기, 메모리 보호 정책, 저수준 프로세스 가상화 |
| **도구 및 인프라** | Clang/LLVM 툴체인, Make/CMake, Git, Docker | 엄격한 CI 빌드 검증, 결정론적 빌드, 크로스 컴파일 파이프라인 |

---

### 공식 에코시스템 및 미러 저장소

본 저장소와 활성 브랜치는 주요 개발자 플랫폼에 동기화되어 유지됩니다:

- **GitHub**: [github.com/hyojunjo59-svg](https://github.com/hyojunjo59-svg)
- **GitLab**: [gitlab.com/hyojunjo59](https://gitlab.com/hyojunjo59)
- **Hugging Face**: [huggingface.co/fsalfpdlsa](https://huggingface.co/fsalfpdlsa)
