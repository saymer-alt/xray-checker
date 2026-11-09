## How to contribute to Xray Checker

#### **Did you find a bug?**

- **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/kutovoys/xray-checker/issues).

- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/kutovoys/xray-checker/issues/new?template=%F0%9F%90%9E-bug-report.md). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

#### **Did you write a patch that fixes a bug?**

- Open a new GitHub pull request with the patch.

- Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

#### **Do you intend to add a new feature or change an existing one?**

- Suggest your change in the [Github Discussions](https://github.com/kutovoys/xray-checker/discussions) and start writing code.

- Do not open an issue on GitHub until you have collected positive feedback about the change. GitHub issues are primarily intended for bug reports and fixes.

Thanks! ❤️ ❤️ ❤️

## Стандарт небольших и проверяемых изменений

Для всех проектов `saymer-alt` действует [общий инженерный стандарт ревью](https://github.com/saymer-alt/saymer-infrastructure/blob/main/docs/engineering-change-review-standard.md). Это правило для **людей и ИИ**, а не файл инструкций агенту.

**Одна проблема → минимальное смысловое исправление → необходимые тесты → один обозримый PR → подтверждение результата.** Не смешивайте hotfix с рефакторингом, переименованиями и посторонними функциями. Если найден другой независимый дефект — отдельное Issue/PR. Размер изменений определяется не количеством строк, а возможностью доказать и проверить их; не отрывайте обязательные тесты и миграции от исправления. Большой неделимый diff требует отдельного обоснования и review. В описании PR указывайте границы, проверки и `NOT_TESTED`; CI PASS не означает field/runtime PASS. Проектные правила безопасности, веток и выпуска сохраняются.
