# SION CARE — CRM LMS THÁNH ĐỒ V1

Web pilot for managing Thánh đồ intake, care, education and reassessment.

## V1 scope

- Dashboard
- Thánh đồ + MSSS
- Hồ sơ 360°
- Khảo sát
- Baseline
- GAP
- Việc cần tìm hiểu
- Kho giáo dục
- Kế hoạch & nhiệm vụ
- Đánh giá lại
- Settings / system principles

## Current storage

V1 uses browser `localStorage` for pilot testing. It is **not** a multi-user production database.

## Deploy

The repository includes `.github/workflows/deploy-pages.yml`. Push `main` to GitHub, enable GitHub Pages with **GitHub Actions** as the source, and each push to `main` will deploy the site.

## Development process

Read:

1. `docs/ARCHITECTURE.md`
2. `docs/WORKFLOW.md`
3. `docs/EDITING.md`
4. `docs/TESTING.md`
5. `docs/RELEASE.md`

## Important boundary

**System locked:** Stage, workflow, permissions, KPI, assessment logic.

**Content open:** modules, lessons, educational text, videos, materials, questions, assignments and practice guidance.

## Project status

Version `1.0.0` — pilot-ready static web app.