# Contributing

## Workflow

1. Create feature branch
```bash
   git checkout develop
   git checkout -b feature/your-feature
```

2. Make changes in `src/`

3. Test thoroughly

4. Commit
```bash
   git add .
   git commit -m "Add: what you added"
```

5. Push and create Pull Request
```bash
   git push origin feature/your-feature
```

## Branches

- `main` — Stable releases only
- `develop` — Active development
- `feature/*` — Feature branches

## Before You Commit

- Test on your machine
- Kinect detects properly
- No build errors
- Update CHANGELOG.md if adding features