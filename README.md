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
