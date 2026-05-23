# System-level PBX Email HTML Templates

This package contains customer-friendly HTML filenames. Use the mapping below to connect each file to the system template enum.

| File name | Template name | Description | Email subject |
|---|---|---|---|
| `2fa-verification-code-notification.html` | `2FA_VERIFICATION` | 2FA verification code notification | Your verification code |
| `cpu-usage-threshold-exceeded-notification.html` | `CPU_EXCEEDED` | CPU usage threshold exceeded notification | [WARNING] High CPU usage on %%PBX_WEB_DOMAIN%% |
| `low-disk-space-warning-notification.html` | `HARD_DISK_EXCEEDED` | Low disk space warning notification | [WARNING] Low disk space on %%PBX_WEB_DOMAIN%% |
| `blocked-ip-address-notification.html` | `IP_BLOCKED` | Blocked IP address notification | [SECURITY] IP address blocked: %%IP_ADDRESS%% |
| `license-limit-reached-notification.html` | `LICENSE_LIMIT` | License limit reached notification | [WARNING] %%LICENSE_TYPE%% limit reached on %%PBX_WEB_DOMAIN%% |
| `memory-usage-threshold-exceeded-notification.html` | `MEMORY_EXCEEDED` | Memory usage threshold exceeded notification | [WARNING] Low system memory on %%PBX_WEB_DOMAIN%% |
| `password-reset-notification.html` | `RESET_PASSWORD` | Password reset notification | Reset your password |
| `service-connected-notification.html` | `SERVICE_CONNECTED` | Service connected notification | Service connected: %%SERVICE_NAME%% |
| `service-disconnected-notification.html` | `SERVICE_DISCONNECTED` | Service disconnected notification | [CRITICAL] Service disconnected: %%SERVICE_NAME%% on %%PBX_WEB_DOMAIN%% |
| `tenant-disk-quota-limit-reached-notification.html` | `TENANT_DISK_QUOTA_LIMIT_REACHED` | Tenant disk quota limit reached notification | [WARNING] Tenant disk quota limit reached on %%PBX_WEB_DOMAIN%% |
| `trunk-concurrent-call-limit-reached-notification.html` | `TRUNK_CALL_LIMIT_REACHED` | Trunk concurrent call limit reached notification | [WARNING] Trunk call limit reached: %%TRUNK_NAME%% |
| `sip-trunk-connected-notification.html` | `TRUNK_CONNECTED` | SIP trunk connected notification | SIP trunk connected: %%TRUNK_NAME%% |
| `sip-trunk-disconnected-notification.html` | `TRUNK_DISCONNECTED` | SIP trunk disconnected notification | [CRITICAL] SIP trunk disconnected: %%TRUNK_NAME%% on %%PBX_WEB_DOMAIN%% |
| `push-certificate-update-failed-notification.html` | `UPDATE_PUSH_CERTS_FAILED` | Push certificate update failed notification | [FAILED] Push certificate update failed on %%PBX_WEB_DOMAIN%% |
| `webhook-queue-size-exceeded-notification.html` | `WEBHOOK_QUEUE_TOO_LARGE` | Webhook queue size exceeded notification | [WARNING] Webhook queue size exceeded on %%PBX_WEB_DOMAIN%% |
