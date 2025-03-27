# Email Template (puqDockerMinIO Welcome Email)

### Docker MinIO module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-minio.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-MinIO/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerMinIO Welcome Email

[![image-1741975587251.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1741975587251.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1741975587251.png)

**Subject:**

```
MinIO Order Information
```

**Body:**

```
Dear {$client_name},

Your order has been accepted for implementation.

Product/Service: {$service_product_name}
Payment Method: {$service_payment_method}
Amount: {$service_recurring_amount}
Billing Cycle: {$service_billing_cycle}
Next Due Date: {$service_next_due_date}


The installation and setup of your MinIO instance is in progress.
Within the next 4 minutes, you will be able to use your MinIO instance.

Upon your first login, you will need to create an account.

Here is the link to your MinIO server.

https://console.{$service_domain}/
Thank you for choosing us.

{$signature}
```

[![image-1741975774630.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1741975774630.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1741975774630.png)