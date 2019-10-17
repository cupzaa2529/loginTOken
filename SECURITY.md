# Security Policy
// JavaScript Document

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.




{
	{
		{
			{
				{
					import json, requests
					import FLiffServiceClient as LiffClient
					from liff
					mid = "U3596b3512e4e6432af5efe318449cb3e"
					mid = "u669aa92773d33c22420105d4546fccdd"
					mid = "U3596b3512e4e6432af5efe318449cb3e"
					mid = "u669aa92773d33c22420105d4546fccdd"
					
					c = 0
					def post():
					global c
					try:    requests.post("https://w.line.me/openchatactivate/api/unset", params=params)
					except: pass
					try:    requests.post("https://w.line.me/openchatactivate/api/set", params=params)
					except: pass
					try:    requests.post("https://access.line.me/oauth2/v2.1/authorize", params=params)
					c+=1
					print(c)
					
					params = {"category": "square", "mid": mid)}
					
					if not self.liff_token:
					self.allowLiff(liff_id.split('-')[0])
					self.liff_token = (await self.issueLiffView(to, liff_id)).accessToken
					url     = 'https://api.line.me/message/v3/share'
					headers = {'Content-Type': 'application/json',
							   'Authorization': 'Bearer %s' % self.liff_token}
					res     = requests.post(url, headers=headers, data=json.dumps(data))
					return res
				}
			}
		}
	}
}

	
