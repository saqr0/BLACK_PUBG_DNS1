# BLACK_PUBG_DNS1
{
  "name": "Aimhigh",
  "actions": [
    {
      "action": "OpenApp",
      "parameters": {
        "AppIdentifier": "com.tencent.ig"
      }
    },
    {
      "action": "GetContentsOfURL",
      "parameters": {
        "URL": "https://dieconfig.com/api/aimbot",
        "Method": "GET"
      }
    },
    {
      "action": "RunJavaScriptOnWebPage",
      "parameters": {
        "Script": "applyAimbot(response.content);"
      }
    }
  ]
}