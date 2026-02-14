# HiDPI

**Non-Retina 2K 모니터에서 HiDPI(Retina) 해상도를 활성화하는 macOS 메뉴바 앱**

macOS는 기본적으로 4K 이상의 디스플레이에서만 HiDPI 모드를 지원합니다.
2K(QHD, 1440p) 모니터를 사용하면 텍스트와 UI가 거칠게 보이는 문제가 있습니다.

HiDPI는 이 제한을 해제하여, **2K 모니터에서도 Retina 품질의 선명한 화면**을 사용할 수 있게 해줍니다.


## Screenshot

<img width="360" alt="HiDPI" src="screenshot_v030.png">

## Download

[**Latest Release**](https://github.com/mgang4u-dev/HiDPI-releases/releases/latest)에서 DMG 파일을 다운로드하세요.

## Install

1. DMG 파일을 열고 `HiDPI.app`을 `/Applications`로 드래그
2. 앱 실행 후 메뉴바에서 모니터 아이콘 클릭
3. 설정(톱니바퀴)에서 관리할 모니터 선택
4. HiDPI 슬라이더로 원하는 해상도 설정

## Requirements

- macOS 13.0 (Ventura) 이상
- Apple Silicon (arm64)

## Why HiDPI?

| | Standard (1x) | HiDPI (2x) |
|---|---|---|
| 2560x1440 모니터 | 텍스트가 작고 거친 렌더링 | 1280x720 논리 해상도, Retina 품질 |
| 픽셀 밀도 활용 | 1:1 매핑 | 4픽셀을 1논리 픽셀로 사용 |
| 결과 | 선명하지 않음 | 텍스트, UI가 매끄럽고 선명 |

macOS에서 2K 모니터는 기본적으로 Standard 모드만 제공합니다.
HiDPI 앱을 사용하면 숨겨진 HiDPI 해상도를 활성화하여 Retina 디스플레이와 동일한 렌더링 품질을 얻을 수 있습니다.
