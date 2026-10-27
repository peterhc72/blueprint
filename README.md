# blueprint 스킬 (Claude Code)

16:9 zoom 방식의 single-canvas / multi-sheet HTML blueprint를 만드는 Claude Code 스킬입니다.

## 설치

이 저장소를 Claude Code 스킬 폴더에 바로 clone합니다.

```bash
git clone https://github.com/peterhc72/blueprint.git ~/.claude/skills/blueprint
```

Windows에서도 Git Bash나 PowerShell에서 같은 명령을 쓰면 됩니다(`~`는 `C:\Users\<사용자명>`). clone한 뒤 Claude Code를 다시 시작하고 "blueprint 만들어줘"처럼 요청하면 스킬이 자동으로 사용됩니다.

업데이트:

```bash
git -C ~/.claude/skills/blueprint pull
```

git 없이 쓰려면 GitHub에서 **Code → Download ZIP**으로 받아, 압축을 푼 폴더를 `~/.claude/skills/blueprint/`로 이름을 맞춰 넣습니다. 설치 후 `SKILL.md`는 `~/.claude/skills/blueprint/SKILL.md` 위치에 있어야 합니다.

## 구성

- `SKILL.md`: 스킬 규칙
- `references/`: Claude가 구조와 스타일을 재사용하는 참조 구현 (브라우저로 바로 열 수 있음)
  - `SG-Innovation-Ecosystem-V1.0_EXT.html`: 표지, 여러 시트, 확대 화면 (공개판: 공식 로고와 제3자 사진 제외)
  - `manifests/`: 위 파일의 manifest JSON

함께 쓰면 좋은 스킬: `frontend-slides`(https://github.com/zarazhangrui/frontend-slides)
