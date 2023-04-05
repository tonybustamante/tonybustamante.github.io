# Configuring windows git w/ SSH

- Install ssh-agent in powershell, start service and add keys
```
Get-Service ssh-agent | Set-Service -StartupType Automatic -PassThru | Start-Service
start-ssh-agent.cmd
ssh-add path/to/ssh/private/key
```

- Make sure keys are in ~/.ssh or specify 

