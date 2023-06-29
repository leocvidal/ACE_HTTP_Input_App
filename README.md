# ACE_HTTP_Input_App
BAR file used to test an HTTP Input flow

How to thrown an exception:
  Access http://<ACE_Server>:7800/testleovidal
  Send this POST payload: {"Action":"Any message","throw_exception":"Y"}

How to receive a response payload back:
  Access http://<ACE_Server>:7800/testleovidal
  Send this POST payload: {"Action":"Any message","throw_exception":"N"}
