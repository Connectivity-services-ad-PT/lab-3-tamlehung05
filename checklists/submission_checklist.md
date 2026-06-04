# Submission Checklist — Lab 03

Trước khi nộp, repo nhóm cần có:

- [x] contracts/iot-ingestion.openapi.yaml
- [x] contracts/ai-vision.openapi.yaml
- [x] postman/collections/FIT4110_lab03_iot_ingestion.postman_collection.json
- [x] postman/environments/FIT4110_lab03_mock.postman_environment.json
- [x] postman/environments/FIT4110_lab03_local.postman_environment.json
- [x] reports/newman-report.xml
- [x] reports/newman-report.html
- [x] reports/contract-lint-report.txt
- [x] checklists/reliability_checklist.md
- [x] templates/test-case-matrix.csv
- [x] templates/consumer-provider-handshake.md

## Ghi chú

- Mock environment test đã chạy thành công bằng `npm run test:mock`.
- Contract lint đã chạy thành công bằng `npm run lint:contracts`.
- Local environment file đã có sẵn; test local có thể chạy bằng `npm run test:local` khi service thật sẵn sàng.

## Quy ước commit

Gợi ý commit cuối:

```bash
git add .
git commit -m "lab03: complete postman mock tests, reports, and submission artifacts"
git push
```

## Link nộp LMS

Nộp link GitHub repo, không nộp file rời.
