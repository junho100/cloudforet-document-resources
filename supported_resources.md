# Markdown

<br>

| Group               | Category                    | Service                 |
| ------------------- | --------------------------- | ----------------------- |
| Compute             | Instance                    | Instance                |
|                     |                             | Key Pair                |
|                     |                             | Availability Zone       |
|                     | Image                       | Image                   |
| Container           | NHN Kubernetes Service(NKS) | Cluster                 |
|                     |                             | Node Group              |
| Network             | VPC                         | VPC                     |
|                     |                             | Subnet                  |
|                     |                             | Routing Table           |
|                     | Floating IP                 | Floating IP             |
|                     | Network ACL                 | Network ACL             |
|                     |                             | Network ACL Binding     |
|                     |                             | Network ACL Rule        |
|                     | Security Group              | Security Group          |
|                     |                             | Security Rule           |
|                     | Load Balancer               | Load Balancer           |
|                     |                             | Health Monitor          |
|                     |                             | IP ACL                  |
|                     |                             | IP ACL Target           |
|                     |                             | L7 Policy               |
|                     |                             | L7 Rule                 |
|                     |                             | Listener                |
|                     |                             | Member                  |
|                     |                             | Pool                    |
|                     |                             | Secret                  |
|                     | Transit Hub                 | Transit Hub             |
|                     |                             | Attachment              |
|                     |                             | Multicast Domain        |
|                     |                             | Routing Table           |
|                     |                             | Shared Multicast Domain |
|                     |                             | Shared Transit Hub      |
|                     | Service Gateway             | Service Gateway         |
|                     |                             | Service Endpoint        |
|                     | DNS Plus                    | DNS Zone                |
|                     |                             | Health Check            |
|                     |                             | GSLB                    |
|                     |                             | Pool                    |
| Storage             | Block Storage               | Block Storage           |
|                     |                             | Block Storage Snapshot  |
|                     |                             | Block Storage Type      |
| Database            | RDS For MySQL               | DB Instance             |
|                     |                             | DB Instance Group       |
|                     |                             | Backup                  |
|                     |                             | DB Security Group       |
|                     |                             | Notification Group      |
|                     |                             | Parameter Group         |
|                     |                             | User Group              |
|                     | RDS For MariaDB             | DB Instance             |
|                     |                             | DB Instance Group       |
|                     |                             | Backup                  |
|                     |                             | DB Security Group       |
|                     |                             | Notification Group      |
|                     |                             | Parameter Group         |
|                     |                             | User Group              |
| Notification        | Push                        | Tag                     |
|                     |                             | Token                   |
|                     | Email                       | Tag                     |
|                     |                             | Category                |
|                     |                             | Template                |
| Application Service | API Gateway                 | Service                 |
|                     |                             | API Key                 |
|                     |                             | Usage Plan              |
| Management          | Certificate Manager         | Certificate             |

# HTML

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cloud Services Table</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Group</th>
                <th>Category</th>
                <th>Service</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="4">Compute</td>
                <td rowspan="3">Instance</td>
                <td>Instance</td>
            </tr>
            <tr>
                <td>Key Pair</td>
            </tr>
            <tr>
                <td>Availability Zone</td>
            </tr>
            <tr>
                <td>Image</td>
                <td>Image</td>
            </tr>
            <tr>
                <td rowspan="2">Container</td>
                <td rowspan="2">NHN Kubernetes Service(NKS)</td>
                <td>Cluster</td>
            </tr>
            <tr>
                <td>Node Group</td>
            </tr>
            <tr>
                <td rowspan="31">Network</td>
                <td rowspan="3">VPC</td>
                <td>VPC</td>
            </tr>
            <tr>
                <td>Subnet</td>
            </tr>
            <tr>
                <td>Routing Table</td>
            </tr>
            <tr>
                <td>Floating IP</td>
                <td>Floating IP</td>
            </tr>
            <tr>
                <td rowspan="3">Network ACL</td>
                <td>Network ACL</td>
            </tr>
            <tr>
                <td>Network ACL Binding</td>
            </tr>
            <tr>
                <td>Network ACL Rule</td>
            </tr>
            <tr>
                <td rowspan="2">Security Group</td>
                <td>Security Group</td>
            </tr>
            <tr>
                <td>Security Rule</td>
            </tr>
            <tr>
                <td rowspan="10">Load Balancer</td>
                <td>Load Balancer</td>
            </tr>
            <tr>
                <td>Health Monitor</td>
            </tr>
            <tr>
                <td>IP ACL</td>
            </tr>
            <tr>
                <td>IP ACL Target</td>
            </tr>
            <tr>
                <td>L7 Policy</td>
            </tr>
            <tr>
                <td>L7 Rule</td>
            </tr>
            <tr>
                <td>Listener</td>
            </tr>
            <tr>
                <td>Member</td>
            </tr>
            <tr>
                <td>Pool</td>
            </tr>
            <tr>
                <td>Secret</td>
            </tr>
            <tr>
                <td rowspan="6">Transit Hub</td>
                <td>Transit Hub</td>
            </tr>
            <tr>
                <td>Attachment</td>
            </tr>
            <tr>
                <td>Multicast Domain</td>
            </tr>
            <tr>
                <td>Routing Table</td>
            </tr>
            <tr>
                <td>Shared Multicast Domain</td>
            </tr>
            <tr>
                <td>Shared Transit Hub</td>
            </tr>
            <tr>
                <td rowspan="2">Service Gateway</td>
                <td>Service Gateway</td>
            </tr>
            <tr>
                <td>Service Endpoint</td>
            </tr>
            <tr>
                <td rowspan="4">DNS Plus</td>
                <td>DNS Zone</td>
            </tr>
            <tr>
                <td>Health Check</td>
            </tr>
            <tr>
                <td>GSLB</td>
            </tr>
            <tr>
                <td>Pool</td>
            </tr>
            <tr>
                <td rowspan="4">Storage</td>
                <td rowspan="3">Block Storage</td>
                <td>Block Storage</td>
            </tr>
            <tr>
                <td>Block Storage Snapshot</td>
            </tr>
            <tr>
                <td>Block Storage Type</td>
            </tr>
            <tr>
                <td>Object Storage</td>
                <td>Container</td>
            </tr>
            <tr>
                <td rowspan="14">Database</td>
                <td rowspan="7">RDS For MySQL</td>
                <td>DB Instance</td>
            </tr>
            <tr>
                <td>DB Instance Group</td>
            </tr>
            <tr>
                <td>Backup</td>
            </tr>
            <tr>
                <td>DB Security Group</td>
            </tr>
            <tr>
                <td>Notification Group</td>
            </tr>
            <tr>
                <td>Parameter Group</td>
            </tr>
            <tr>
                <td>User Group</td>
            </tr>
            <tr>
                <td rowspan="7">RDS For MariaDB</td>
                <td>DB Instance</td>
            </tr>
            <tr>
                <td>DB Instance Group</td>
            </tr>
            <tr>
                <td>Backup</td>
            </tr>
            <tr>
                <td>DB Security Group</td>
            </tr>
            <tr>
                <td>Notification Group</td>
            </tr>
            <tr>
                <td>Parameter Group</td>
            </tr>
            <tr>
                <td>User Group</td>
            </tr>
            <tr>
                <td rowspan="5">Notification</td>
                <td rowspan="2">Push</td>
                <td>Tag</td>
            </tr>
            <tr>
                <td>Token</td>
            </tr>
            <tr>
                <td rowspan="3">Email</td>
                <td>Tag</td>
            </tr>
            <tr>
                <td>Category</td>
            </tr>
            <tr>
                <td>Template</td>
            </tr>
            <tr>
                <td rowspan="3">Application Service</td>
                <td rowspan="3">API Gateway</td>
                <td>Service</td>
            </tr>
            <tr>
                <td>API Key</td>
            </tr>
            <tr>
                <td>Usage Plan</td>
            </tr>
            <tr>
                <td>Management</td>
                <td>Certificate Manager</td>
                <td>Certificate</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
