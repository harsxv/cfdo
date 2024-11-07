# Usage

```
cfdo - Cloudflare DNS Operator

Usage:
  cfdo show-zone                                                Show zone information
  cfdo add-record <name> <content> [<type>]                     Add a new DNS record
  cfdo update-record <record_id> [<type>] <name> <content>      Update an existing DNS record
  cfdo list-records [--full]                                    List all DNS records (use --full to show full content)

Examples:
  cfdo add-record A example.com 192.0.2.1
  cfdo update-record <record_id> A example.com 192.0.2.3
```

# Demo
![image](https://github.com/user-attachments/assets/c120d965-4dd5-4bd5-acfa-b63a8047b639)
![image](https://github.com/user-attachments/assets/2ec8c643-9e2b-4f2f-b6c4-2ac375c3b8ad)







