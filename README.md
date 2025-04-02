# Best Praticals Commits

## 🚀 Main Commit Types
Type |	When to Use |	Example
| -- | -- | -- |
| feat | 	When adding a new feature or functionality	| feat(payment): add support for Pix |
| fix	| When fixing a bug	| fix(cart): fix error when removing item | 
| refactor | When improving code structure without changing behavior	| refactor(user): improve authentication module organization |
| chore	| For minor tasks that don’t affect production code (configs, scripts, etc.)	| chore(linter): add ESLint rules |
| docs | For documentation updates |	docs(readme): add installation instructions |
| test	| When adding or modifying tests	| test(auth): add unit tests for login |
| style	| For formatting changes (spacing, indentation, etc.) |	style(button): remove unnecessary whitespace |
| perf	| When improving performance | perf(api): optimize request response time |
| ci	| For CI/CD-related changes (GitHub Actions, pipelines, etc.) |	ci(deploy): add build step to GitHub Actions |
| build	| For changes affecting the build system or dependencies |	build(deps): update project dependencies |
| revert|	When reverting a previous commit |	revert: undo authentication feature |

## 📌 Best Practices
- ✔ Use short, imperative phrases ("Add feature X", not "Adding feature X")
- ✔ Include a scope when relevant (feat(auth):, fix(cart):)
- ✔ Avoid vague commits like fix bug or update
- ✔ Break large changes into smaller, more descriptive commits
