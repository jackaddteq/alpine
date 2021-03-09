# alpine

Command	Usage	Example
apk update	Update the package list	apk update
apk upgrade	Upgrade the system	apk update
apt ugrade
apk add pkg	Add a package	apk add apache
apk del pkg	Delete a package	apk del nginx
apk search -v	Search for packages	apk search -v
apk search -v -d ‘nginx*’
apk search -v ‘apache*’
apk info	List all installed pacakges	apk info
apk fix	Repair package or upgrade it without modifying main dependencies	apk fix
apk policy pkg	Show repository policy for packages	apk policy bash
apk stats	Show statistics about repositories and installations	apk stats
