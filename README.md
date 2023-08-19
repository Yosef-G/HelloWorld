# HelloWorld
Started by user Yosef Gessese
Running as SYSTEM
Building on the built-in node in workspace /var/lib/jenkins/workspace/GithubExample
The recommended git tool is: NONE
No credentials specified
Cloning the remote Git repository
Cloning repository https://github.com/Yosef-G/HelloWorld.git
 > git init /var/lib/jenkins/workspace/GithubExample # timeout=10
ERROR: Error cloning remote repo 'origin'
hudson.plugins.git.GitException: Could not init /var/lib/jenkins/workspace/GithubExample
	at org.jenkinsci.plugins.gitclient.CliGitAPIImpl$5.execute(CliGitAPIImpl.java:1073)
	at org.jenkinsci.plugins.gitclient.CliGitAPIImpl$2.execute(CliGitAPIImpl.java:819)
	at hudson.plugins.git.GitSCM.retrieveChanges(GitSCM.java:1222)
	at hudson.plugins.git.GitSCM.checkout(GitSCM.java:1305)
	at hudson.scm.SCM.checkout(SCM.java:540)
	at hudson.model.AbstractProject.checkout(AbstractProject.java:1240)


Started by user Yosef Gessese
Running as SYSTEM
Building on the built-in node in workspace /var/lib/jenkins/workspace/GithubExample
The recommended git tool is: NONE
using credential 005
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/GithubExample/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/Yosef-G/HelloWorld.git # timeout=10
Fetching upstream changes from https://github.com/Yosef-G/HelloWorld.git
 > git --version # timeout=10
 > git --version # 'git version 1.8.3.1'
using GIT_SSH to set credentials Github
[INFO] Currently running in a labeled security context
[INFO] Currently SELinux is 'enforcing' on the host
 > /usr/bin/chcon --type=ssh_home_t /var/lib/jenkins/workspace/GithubExample@tmp/jenkins-gitclient-ssh4726555950524913084.key
Verifying host key using known hosts file
 > git fetch --tags --progress https://github.com/Yosef-G/HelloWorld.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse refs/remotes/origin/master^{commit} # timeout=10
 > git rev-parse origin/master^{commit} # timeout=10
ERROR: Couldn't find any revision to build. Verify the repository and branch configuration for this job.
Finished: FAILURE
