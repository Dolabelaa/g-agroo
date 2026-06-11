# 🤝 Guia de Contribuição — G-Agro

Obrigado pelo interesse em contribuir com o **G-Agro**!

## 📋 Padrão de Commits (Conventional Commits)

```
feat: adiciona funcionalidade de alerta de geada
fix: corrige cálculo de produtividade por hectare
docs: atualiza README com instruções de deploy
refactor: reorganiza serviço de insumos
test: adiciona testes para SafraService
chore: atualiza dependências do Maven
```

## 🌿 Padrão de Branches

- `main` — produção estável
- `develop` — integração contínua
- `feature/nome-da-feature` — novas funcionalidades
- `fix/nome-do-bug` — correções

## ✅ Checklist do Pull Request

- [ ] Código segue os padrões do projeto
- [ ] Testes unitários escritos e passando
- [ ] Documentação atualizada (se aplicável)
- [ ] Commit segue Conventional Commits

## 🧪 Como Rodar os Testes

```bash
# Back-end
cd backend && ./mvnw test

# Front-end
cd frontend && npm run test
```
