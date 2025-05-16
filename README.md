# Backup

<details>
  <summary>Click for Creating Backup</summary>

## Root Access

```
sudo -i
```

## Change Directory

```
cd /
```

## Downloading Script

```
git clone https://github.com/praveenkarunarathne/Backup && cd Backup && mv creatingbackup.sh / && cd .. && rm -r Backup
```

## Create Screen

```
screen
```

## Starting Creating Backup

```
bash creatingbackup.sh
```

## Reconnect To Screen

```
screen -r
```

## Terminate Screen

```
exit
```

## File Size

```
ls -lh
```

## Storage Usage

```
df -h /dev/sda1
```

## Delete Files

```
rm creatingbackup.sh backup.tar.gz fileslist.txt
```

</details>

<details>
  <summary>Click for Restoring Backup</summary>

## Root Access

```
sudo -i
```

## Change Directory

```
cd /
```

## Downloading Script

```
git clone https://github.com/praveenkarunarathne/Backup && cd Backup && mv restoringbackup.sh / && cd .. && rm -r Backup
```

## Backup Files

<details>
  <summary>Click for AMD Micro</summary>

Ubuntu 18.04  :-  https://www.mediafire.com/file/es3xlz6zazhjyxc/AMD_Micro_Ubuntu_18.04.tar.gz/file

Ubuntu 20.04  :-  https://www.mediafire.com/file/5zqute8mlwic1vf/AMD_Micro_Ubuntu_20.04.tar.gz/file

Ubuntu 22.04  :-  https://www.mediafire.com/file/ry0zkfji4q5jh90/AMD_Micro_Ubuntu_22.04.tar.gz/file

</details>

<details>
  <summary>Click for Ampere</summary>

Ubuntu 18.04  :-  https://www.mediafire.com/file/40wvza20w9ty8zk/Ampere_Ubuntu_18.04.tar.gz/file

Ubuntu 20.04  :-  https://www.mediafire.com/file/w598oyd40c3ueta/Ampere_Ubuntu_20.04.tar.gz/file

Ubuntu 22.04  :-  https://www.mediafire.com/file/0js8wn9zhlc1rdf/Ampere_Ubuntu_22.04.tar.gz/file

</details>

## Downloading Backup Files

```
wget URL -O backupfiles.tar.gz && tar -xzvf backupfiles.tar.gz && rm backupfiles.tar.gz
```

## Create Screen

```
screen
```

## Starting Restoring Backup

```
bash restoringbackup.sh
```

## Username

```
ubuntu
```

## Updating Packages

```
apt update && apt upgrade -y
```

## Fixing Error

```
echo nameserver 8.8.8.8 > /etc/resolv.conf && systemctl daemon-reload
```

## Editing Ssh Public Key

```
rm /home/ubuntu/.ssh/authorized_keys && nano /home/ubuntu/.ssh/authorized_keys
```

## Delete Backup Files

```
rm /restoringbackup.sh /backup.tar.gz /fileslist.txt
```

## Rebooting VPS

```
reboot
```

</details>
