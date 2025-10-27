# ROBOSTEP-SHARE

## Coding rules
### Naming rules

| 対象 | 命名規則 | 例 |
|------|---------|-----|
| Directory | kebab-case | `linear-belt`, `board-io` |
| File | snake_case | `linear_belt.hpp`, `board_io.cpp` |
| Class | PascalCase | `LinearBelt`, `BoardIO` |
| Function | camelCase | `calculateSpeed`, `initializeDevice` |
| Variable | snake_case | `motor_speed`, `sensor_value` |

### Git branch naming
* フォーマット: `{feature, bugfix or refactor}/{issue number}-{変更内容をケバブケースで簡潔に}`
* 例: `feature/12-add-vector`, `bugfix/23-fix-sensor-reading`
