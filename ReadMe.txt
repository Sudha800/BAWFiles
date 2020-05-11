Use the below commands to add dependency jars to the Maven Repository:
--------------------------------------------------------------------------
C:\IBM\FileNet\ContentEngine\lib>mvn install:install-file -Dfile=xlxpScannerUtils.jar -DgroupId=com.ecm 
-DartifactId=xlxpScannerUtils -Dversion=5.3.2 -Dpackaging=jar



Static Template Configuration in ACCE:
-------------------------------------
1). Create document class with "RequestQuotation"
2). Add the static template to RequestQuotation document class and the Document Title should be "RequestQuotation.pdf"
