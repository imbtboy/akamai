# akamai
This api can solve the annoying akamai, generate the sensor_data required for behavior verification through the background AI simulation, and then post it to the target server to pass the verification.

1. This sensor_data is automatically generated by AI
2. We provide two sensor_data versions of akamai, 1.75 and 2.0 respectively
3. sensor_data can be generated quickly, no need to poll to get it, a http link is done, it takes about 0.05 seconds
4. The returned format is as follows, you only need to extract the captcha_key parameter to use

{"success":true,"message":"success","data":null,"sensor_data":"7a7423hkswf4sjf2031.75-1,2,-94,-100,Mozilla/5.0 (.............bd4080573cec113453452223545433223,33-1,2,-94,-121,;24;16;2","ua":"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.2355.93 Safari/537.36"}

contact me: https://t.me/shineho

update: 2023-11-29
