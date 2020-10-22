# What is?

OpenShift client plugin that finds and uses `kubeconfig` and `kubeadmin-password` file to login to a OpenShift 4 cluster.

# Install

Install somewhere on your `$PATH`:

```
# sudo wget -P /usr/local/bin https://raw.githubusercontent.com/bostrt/oc-flogin/master/oc-flogin
# sudo chmod +x /usr/local/bin/oc-flogin
```


# Usage

```
# oc flogin ~/installations/test-cluster
Using /home/user/installations/test-cluster/auth/kubeconfig
Login successful.

You have access to 60 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "openshift-operators".

```

That's about it, nothing real special. 
