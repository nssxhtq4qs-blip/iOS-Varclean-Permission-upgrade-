# iOS-Varclean-Permission-upgrade-
Clearing jailbreak leftovers from older versions in iOS，And add permission escalation (with filza）
Features:
1.Clean up leftover traces from an older version of jailbreak before upgrading to a newer version of jailbreaonly
2. have installed filzaDS to provide read and write access to the var directory. But note that I didn't Grant permissions to other directories permito give users who have installed filzaDS read and write access to the var directory. But note that I didn't add permission changes to any other subfolders besides mobile (which could have been done), but doing so would have caused countless issu，Like starting a loop
3.If you didn't catch what I said, here's the gist: You can put stuff in /var, but directories like /var/db aren't supported. That could cause a startup loop, but I haven't changed anything in /var/mobile/
4.This software only provides basic file management and permission "upgrades." If you need to do more with directories, you must use Filza. I won't provide any compensation for any losses caused by this software
