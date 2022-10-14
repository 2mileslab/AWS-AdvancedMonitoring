아래 파일 4개에서 EKS_FluentBit_Dashboard 수정 -> user*-EKS_FluentBit_Dashboard
```
cdk.out/Services.template.json:5810:    "DashboardName": "EKS_FluentBit_Dashboard"
cdk.out/tree.json:9670:                "dashboardName": "EKS_FluentBit_Dashboard"
lib/services.ts:613:            dashboardName: "EKS_FluentBit_Dashboard",
resources/destroy_stack.sh:34:aws cloudwatch delete-dashboards --dashboard-names "EKS_FluentBit_Dashboard"
```
