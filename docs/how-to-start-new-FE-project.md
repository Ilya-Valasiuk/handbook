# Checklist 

- [ ] setup eslint/prettier in repository
- [ ] setup tests in repository (if it's needed)
- [ ] run eslint/prettier on pre-commit phase
- [ ] run typescript check in pre-push phase
- [ ] setup PR checks (code quality) - run eslint/prettier & typescript on each PR
- [ ] setup PR checks (unit/e2e/... tests) - run tests (if it make sense to run during PR phase)
- [ ] setup branch restrictions - (at least 1 approve, update main branch only via PR)
- [ ] define where the FE will be deployeed (vercel, amplify, dev azure)
- [ ] setup pipelines for staging + branch previews (if possible)
- [ ] add PR template ([Github](https://raw.githubusercontent.com/Ilya-Valasiuk/handbook/main/.github/pull_request_template.md))
- [ ] add README.md. Should cover how to start locally
- [ ] add .env.example (describe all needed variables)
