# devops-hw8

### Ansible tasks
1. Build an artifact on the One Node (*builder*)
2. Copy the artifact to the Local Machine to the dir */root*
3. Backup the new artifact on the Local Machine at the same dir
4. Deploy the new artifact on the Second Node (*web*)

```
ansible-playbook build_and_deploy.yml
```
