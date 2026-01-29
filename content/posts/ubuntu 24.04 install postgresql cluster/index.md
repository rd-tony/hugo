---
date: '2026-01-29T14:13:38+08:00'
draft: false
title: 'Ubuntu 24.04 Install Postgresql Cluster'
---

### 虛擬機

{{< rawhtml >}}
<table>
    <tr align="center">
        <th>HostName</th>
        <th>IP Address</th>
        <th>安裝項目</th>
        <th>Virtual IP</th>
    </tr>
    <tr align="center">
        <td>pgha-01</td>
        <td>172.30.1.211</td>
        <td rowspan="3" align="left">
            <ul>
                <li>HAProxy</li>
                <li>Keepalived</li>
            </ul>
        </td>
        <td rowspan="3" align="center">Virtual IP: 172.30.1.220</td>
    </tr>
    <tr align="center">
        <td>pgha-02</td>
        <td>172.30.1.212</td>
    </tr>
    <tr align="center">
        <td>pgha-03</td>
        <td>172.30.1.213</td>
    </tr>
</table>

<table>
    <tr align="center">
        <th>HostName</th>
        <th>IP Address</th>
        <th>安裝項目</th>
        <th>Virtual IP</th>
    </tr>
    <tr align="center">
        <td>pgsql-01</td>
        <td>172.30.1.221</td>
        <td rowspan="3" align="left">
            <ul>
                <li>etcd</li>
                <li>Patroni</li>
                <li>PostgresSQL</li>
            </ul>
        </td>
        <td rowspan="3" align="center">
            Virtual IP: 172.30.1.221
            </td>
    </tr>
    <tr align="center">
        <td>pgsql-02</td>
        <td>172.30.1.222</td>
    </tr>
    <tr align="center">
        <td>pgsql-03</td>
        <td>172.30.1.223</td>
    </tr>
</table>
{{< /rawhtml >}}

---

### PostgresSQL

---

### etcd

---

### Patroni

---

### HAProxy

---

### Keepalived
