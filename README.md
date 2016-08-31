JS Pluggin:
<script src="http://suite.peoplelogic.com.au/scripts/production/iframe-resizer/js/iframeResizer.min.js"></script>
iFrame code: (replace src) 
<iframe id="iframeCalendar" scrolling="no" src="//suitetalking.swiftdigital.com.au/scripts/SuiteTalking/calendar/testCalendar/calendar.html?calendar=Quick%20Test%20Calendar" style="border:0" width="100%"></iframe></p>
<script>iFrameResize({log:true,autoResize:true})</script>

please make sure 
https://suitetalking.swiftdigital.com.au/scripts/SuiteTalking/calendar/testCalendar/js/iframeResizer.contentWindow.min.js
file is present in iframe source file
