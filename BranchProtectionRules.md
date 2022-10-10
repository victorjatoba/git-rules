# Check Branch Protection Rules

Check how PRs works with checking the rules below:

## Rule 1

- [x] Require a pull request before merging
  - [x] Dismiss stale pull request approvals when new commits are pushed

- Criar PR com user A
- Aprovar PR com o user B

![Before](./images/rule1.0.png)

- Fazer commit
![After](./images/rule1-1.png)

## Rule 2

- [x] Require status checks to pass before merging
  - [x] Require branches to be up to date before merging

- criar branch A
- Fazer commits na A
- Fazer PR
- Fazer commits na main

Tentar aprovar o PR

Sugestões de mais marcações:

- Require conversation resolution before merging
- Require signed commits
