# Preliminary steps


## Install Git for Windows
If you have Git already installed, please uninstall it and install the newest version. Go to this link: https://gitforwindows.org/ download and install Git for Windows. Note that if you are not able to install 3rd party software, make sure permissions are granted to you. During installation, use default settings offered to you by the installer, with
exception for these steps:

- Override the default branch

![Git install](images/git_install/git_branch.png?raw=true "Git default branch")

- Choose MinTTY as terminal emulator (should be default)

![Git install](images/git_install/git_terminal.PNG?raw=true "Git rebase")

- Change git pull strategy to 'rebase'

![Git install](images/git_install/git_rebase.png?raw=true "Git rebase")

- Choose default Credential Manager Core (should be default).

![Git install](images/git_install/git_credential_default.png?raw=true "GitCredential default")

If you cannot install software on your machine, ask your leader to give you rights for that.

## Clone this repository to your laptop
In order to speed up our work with git, you should have cloned this repository on to your PC prior the course. Don't worry, we will explain cloning during the course.
So in order to clone a repo do:

- Go to the (C:) SYSTEM disk --> Users --> your gIdent and create a new folder, call it repositories
- Go to repositories folder, right click and start `Git Bash Here`

![Git bash](images/git_bash/git_bash_start.png?raw=true "Git bash")
- Copy url address of this git repository (HTTPS). This can be found at the top of the this repo site.

![GitHub url](images/git_github_settings/github_clone_https.png?raw=true "GitHub url")
- In Git Bash write "git clone https://github.com/vychiokas/analysts-training.git" by first writing git clone and then CTRL+Insert to insert url (or right click + Paste). Press Enter to execute.
- Since this is the first time you try to communicate with GitHub from your laptop, a pop-up window will occur.

![Git cred](images/git_credentials/github_popup_clone_default_credential.png?raw=true "GitCredential default")

- In case you used the default Credential manager, a web browser (your default) should open asking you to Authorize GitCredentialManager. Write your GitHub password.

![Git cred](images/git_credentials/github_popup_clone_default_credential_browser.png?raw=true "GitCredential auth") ![Git cred](images/git_credentials/github_popup_clone_default_credential_browser_password.png?raw=true "GitCredential password") ![Git cred](images/git_credentials/github_popup_clone_default_credential_browser_success.png?raw=true "GitCredential success")

- Note that in case you haven't changed your default browser and still using IE or Edge, you might not be able to click on green button `Authorize GitCredentialManager`. Either change your default browser (as advised above) or copy the url to other browser to be able to finish authorization.

- After successful authorization, you should get email from GitHub about GitHub OAuth application added to your account. Also if you navigate on GitHub to Settings --> Applications --> Authorized OAuth Apps you should see Git Credential Manager. Last if you check Credential Manager on your Windows, Credential Manager --> Windows Credentials, GitHub credentials should be stored there (It is called Legitimasjonsbehandling if you have Norwegian Windows).

![GitHub setting](images/git_github_settings/github_settings.png?raw=true "GitHub setting") ![GitHub setting](images/git_github_settings/github_settings_applicatins_oauth.png?raw=true "GitHub OAuth") ![Git cred](images/git_credentials/win_cred_manager_github.png?raw=true "GitCredential success")

- Now the repository has been successfully cloned.

![GitBash clone](images/git_bash/git_clone_successful.png?raw=true "GitBash clone")
