{
  "proxies": [
    {
      "name": "Trojan 节点",
      "type": "trojan",
      "server": "your-server.com",
      "port": 443,
      "password": "yourpassword",
      "sni": "www.microsoft.com",
      "udp": true
    }
  ],
  "proxy-groups": [
    {
      "name": "Proxy",
      "type": "select",
      "proxies": [
        "Trojan 节点"
      ]
    }
  ]
}
