# Mycopsychosys-UnOfficial_Korean_Translation
마이코사이코시스(Mycopsychosys:Remastered) 게임의 비공식 한글 번역입니다.
> Note: 해당 레포지터리는 한글/기능 패치를 포함하지 않은 오직 번역된 스크립트 파일만을 포함하고 있습니다.  
  인게임 적용을 위한 한글/자막기능 패치 적용은 다음 레포지터리를 참고해주세요.  
  [MuteJack/Mycopsychosys-UnOfficial-Patch](https://github.com/MuteJack/Mycopsychosys-UnOfficial-Patch)

## 적용 방법 (테스트용):
> Note: 원본 게임은 한글 폰트를 지원하지 않으므로 폰트 깨짐 문제가 발생할 수 있습니다. 해당 사항에 대해서는 5번을 참고해주세요.
- 1. 게임의 `/game/tl/russian` 폴더에 .rpy파일들을 넣어주세요
- 2. 각 .rpy파일들을 열고, `translate korean` 부분을 모두 `translate russian`으로 일괄 변경합니다.
- 3. 게임을 켜고, `russian`을 선택해주세요.
- 4. russian외에도, 게임에서 지원하는 언어면 모두 적용 가능합니다.
- 5. `options.rpy`에 한글 폰트에 대한 설정이 추가적으로 작성되어있습니다.  
  - 1. 게임의 `/game/fonts/` 폴더에 `/NanumGothic` 폴더를 생성해주세요  
  - 2. `/game/fonts/NanumGothic/`에 `NanumGothic.ttf` 폰트 파일을 추가합니다. [나눔 고딕 폰트 다운로드](https://hangeul.naver.com/font)  
  - 3. 원하신다면 `options.rpy`파일을 수정하여 나눔고딕이 아닌 원하시는 다른 폰트를 사용하실 수 있습니다.  
  - 4. Error Handling에 대해 번역 추가 시, options.rpy에 추가된 코드만으로는 폰트 문제가 발생할 수 있습니다. Error Handling에 대한 부분은 오류 발생에 관한 부분으로 게임 플레이와는 무관하니 이 부분에 대해서는 번역하지 않으시는 것을 추천드립니다.  

## 추가 사항:
본 레포지터리는 [비공식 번역/기능 패치](https://github.com/MuteJack/Mycopsychosys-UnOfficial-Patch)의 번역 스크립트만을 포함하고 있습니다.  
- 본래 한국어 옵션을 추가하기 위해서는 실제 게임 내 원본 renpy스크립트 파일들을 직접 수정해야합니다.
- 하지만 이를 위해서 수정된 코드를 함께 배포 시, 게임의 원본 코드가 다수 노출(포함)되어 저작권 등의 문제가 있으므로, 번역파일만을 첨부했습니다.
- 따라서, 버튼 ui 이미지 등은 덮어쓴 언어로 보이거나 게임을 직접 수정할 필요가 있습니다.
- 번역 내용 확인/참고가 아닌 실제 게임에 적용하려는 목적이라면 해당 레포지터리가 아닌 비공식 번역/기능 패치를 참고해주세요.

## 게임/번역 정보
게임 개발: [DeltaCatStudio](https://www.deltacatstudio.com/)
- [Mycopsychosys Remastered (Steam)](https://store.steampowered.com/app/3807550/Mycopsychosys_Remastered/)
- [Mycopsychosys Remastered (itch.io)](https://delta-cat-studio.itch.io/mycopsychosys)

비공식 번역/패치 개발: MuteJack
- 비공식 패치(한글 패치 포함): [MuteJack/Mycopsychosys-UnOfficial-Patch](https://github.com/MuteJack/Mycopsychosys-UnOfficial-Patch)
- 비공식 번역(Script Only): [MuteJack/Mycopsychosys-UnOfficial_Korean_Translation](https://github.com/MuteJack/Mycopsychosys-UnOfficial_Korean_Translation)

게임 버전 지원:
- 게임 이름: Mycopsychosys Remastered
- 게임 버전: Mycopsychosys v2.0 (2026.01.06)
- 번역 버전: v1.0.2 (2026.02.02)
 
## 주의사항
- 해당 번역은 비공식 팬메이드이며, DeltaCat Studio와 관련이 없습니다.
  - 게임 "Mycopsychosys: Remastered"의 모든 저작권은 DeltaCat Studio에 있습니다.
  - 본 번역 파일은 어떠한 보증 없이 제공되며, 사용/무단 재배포로 인해 문제에 발생하는 문제에 대해 제작자는 책임지지 않습니다.
  - 본 번역 제작자는 DeltaCat Studio와 그들의 저작물을 존중하며, 원본 게임의 권리를 침해할 의도가 없음을 밝힙니다.
- 적용 대상 버전(게임)은 **Mycopsychosys Remastered v2.0 (2026.01.26 Update)**입니다. 게임이 업데이트되었을 경우, 일부 번역이 적용되지 않는 등의 문제가 발생할 수 있습니다.
  - 위 문제는 주로 원본 게임에서 Ren'Py의 번역 해시가 수정되었을 경우 발생될 수 있습니다.


