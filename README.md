SCLog
======

SCLog is an OpenSource logging class intended to be used with the Oracle Service Cloud product.  

### Highlights
- Easy Install 
- Configurable via Service Cloud console
- Output logs to database or file system
- Display file system logs via web browser


### Custom Object File
scLog_object.zip is included with this repository to be imported into your Service Cloud Instance
    
### Sample Code - C# #
    using ServiceVentures;
    ...
    scLog logger = new scLog();
    logger.initializeLogger(this._globalContext);
    logger.log("A notice message to be logged", null, null, scLog.logLevel.Notice);
    
### Support
	This add-in was developed by Service Ventures LLC (servicecloudedge.com) 
	For more information email us info@servicecloudedge.com