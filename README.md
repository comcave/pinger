filepath for the actual, original jar file: /updater/getClient (take the first part from Pingable module).

u can start it in debug mode (-libagent:jdwp ...) OR decompile that jar file.
most important stuff is in da login_body, look at tha image...

start the pinger lyke this:
ruby main.rb username:password

works perfectly on a smartphone(e.g termux on android)
