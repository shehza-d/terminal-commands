# Linux

### Change swap file

Turn off default swap

```bash
sudo swapoff /swapfile
```

To access the root account in Ubuntu

```bash
sudo -s
```

Once you’ve got root access in the terminal, use the rm command to delete the default Ubuntu swap file from your computer.

```bash
cd / && rm swapfile
```

#### Create a new swap file

Now that the default Ubuntu swap file has been deleted from your system, it is time to create a new one. To make a new swap file, you’ll need to use the dd command. The dd command is handy and will be able to create a new swap file as big or as small as you like.

To create a new swap file, you must first determine the size in Megabytes, as that’s what dd uses. For example, to make an 8 GB swap file, you’d do 8 x 1024, which calculates to 8192 MB.

```bash
dd if=/dev/zero of=/swapfile bs=1M count=YOUR_MEGABYTE_NUMBER_HERE
```

The dd command will take a bit of time to complete. When it is done, your new swap file will be in the / directory, where the old swap file was.

After creating the new swap file, use the chmod command to update the swap file to the correct permissions.

```bash
chmod 600 /swapfile
```

#### Enable new swap

```bash
mkswap /swapfile
```

```bash
swapon /swapfile
```
