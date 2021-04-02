# Tips

## SSH from local to server through a middleware bastion

```bash
ssh-agent bash
ssh-add /path/to/pemfile
ssh -A -i /path/to/pemfile username@bastion-ip
ssh username@server-ip
```
