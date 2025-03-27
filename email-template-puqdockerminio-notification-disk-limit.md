# Email Template (puqDockerMinIO Notification disk limit)

### Docker MinIO module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-minio.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-MinIO/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerMinIO Notification disk limit

[![image-1741976318226.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1741976318226.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1741976318226.png)

**Subject:**

```
Disk space usage {$disk_used_percentage}%
```

**Body:**

```
Dear {$client_name},

We want to inform you that your MinIO service is running low on disk space. 
Please take action to prevent service interruptions.

Service Details:

Product/Service: {$service_product_name}
Domain: {$service_domain}
Total Disk Space: {$disk_total}
Used Disk Space: {$disk_used} ({$disk_used_percentage}%)
Consider freeing up space or upgrading your plan if needed.

{$signature}
```

[![image-1741976380740.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1741976380740.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1741976380740.png)