- š Hi, Iām @Bk129o
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Bk129o/Bk129o is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.

You can click the Preview link to take a look at your changes.
--->@@ -247,7 +247,7 @@ public void onOpen(WebSocket arg0, ClientHandshake arg1) {
			String s = arg1.getFieldValue(info.getForwardedIPHeader());
			if(s != null) {
				try {
					addr = InetAddress.getByName(s);
					addr = InetAddress.getByName(s.split(",", 2)[0]);
				}catch(UnknownHostException e) {
					System.out.println("invalid '" + info.getForwardedIPHeader() + "' header - " + e.toString());
					arg0.close();
 BIN +30 Bytes (100%) 
stable-download/java/bungee_command/bungee-dist.jar
Binary file not shown.

