## 📄 GraphQL Mutation Examples

This repository contains three example GraphQL mutation requests for creating custom QL rules using a GraphQL API.

## 🚀 Getting Started

To use any of the examples provided in this repository, make sure to include the following HTTP header in your requests:

`x-tenant-context: 12345`

Replace `12345` with your actual **tenant ID**.

This header is **required** by the API to properly route and authorize your requests based on your tenant context.

---

## 📸 Example Setup in Postman

Below is a screenshot showing how to configure your Postman request with the required `x-tenant-context` header:

<img width="510" alt="Screenshot 2025-05-30 at 13 58 59" src="https://github.com/user-attachments/assets/8c4f4618-8344-4028-b8d7-cac6a2ac629c" />

---

## 📂 Contents

- [`Alerts Custom Rule Mutation`](https://docs.taegis.secureworks.com/manage/custom_alerting_rules/) – A complete mutation for creating **Taegis XDR Custom Rules**.
- [`Alerts Suppression Rule Mutation`](https://docs.taegis.secureworks.com/manage/alert_suppression/) – A complete mutation for creating **Taegis XDR Suppression Rules**.
- [`Alerts Tuning Rule Mutation`](https://support.ctpx.secureworks.com/hc/en-us/articles/31307972521115-How-To-Alert-Severity-Tuning-Rules) – A complete mutation for creating **Taegis XDR Tuning Rules**.

