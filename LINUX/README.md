
ls	List files	See files in current folder
ls -l	Long listing with permissions	Check file size, date, owner
ls -a	Show hidden files	View .env, .gitignore
pwd	Show current directory path	Know where you are
cd foldername	Change directory	Navigate into folder
cd ..	Go up 1 directory	Move backward
cd /path/to/folder	Go to custom location	Jump to any folder
mkdir foldername	Create folder	Make new project folder
rmdir foldername	Remove empty folder	Delete unused directory
rm -r foldername	Remove directory with files	Delete folder safely
touch filename	Create empty file	Create app.js, .env, etc.
cat filename	View file content	Quickly read a file
nano filename	Edit file in terminal	Edit config files easily
cp file1 file2	Copy file	Make backup copy
cp -r folder1 folder2	Copy entire folder	Duplicate project folder
mv file1 file2	Move or rename file	Rename files
rm filename	Delete file	Remove logs, temp files
rm -f filename	Force delete	Delete without confirmation



find /path -name "file.txt"	Search a file anywhere
find . -type f -name "*.js"	List all JS files
grep "text" filename	Find text inside a file
grep -R "function" .	Find text recursively in folder
grep -i "error" log.txt	Case-insensitive search




chmod 755 file	Change file permissions
chmod +x file.sh	Make script executable
chown user:user file	Change owner of file
chown -R user:user folder	Change owner recursively


uname -a	Full system info
hostname	Shows machine name
top	Display running processes
htop	Improved process manager
df -h	Disk memory usage
du -sh folder	Size of a folder
free -h	RAM usage
uptime	How long system has been running



ifconfig / ip a	View IP address
ping google.com	Test network connection
curl url	Fetch data from server
wget url	Download files
netstat -tulpn	Check open ports
ss -tulpn	Modern replacement for netstat