When using MAC, especially whgen using Google Drive ._ files are continuously generated.
To avoid this, do as follow.

>> Open Terminal
>> Type following command
defaults write com.apple.desktopservices DSDontWriteNetworkStores -bool TRUE
