# UnixCommands
important Unix Commands

#Update and install a YUM package
sudo yum update \
#check if package is available
sudo yum search docker 
#Get version information:
sudo yum info docker

#find a file contain a specific text 
grep -Rnw . -e 'ccttest'

#find the matching files end with .tf and replace with new value
find . -type f -name "*.tf" -exec sed -i 's/mnd-owneremail/mnd-owner/g' {} 
