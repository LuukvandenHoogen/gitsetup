# Git setup

TortoiseGit vervangen door SourceTree

## Chocolatey (packagemanager)

1. Volg https://chocolatey.org/install
1. Voer uit ```choco install chocolateygui```
1. Open 'Chocolatey Gui' in start menu
1. Klik in linker menu op 'chocolatey'
1. installeer:
	* putty
	* git
	* sourcetree
	* dbeaver
	
## Putty key setup

1. Maak keys directory aan en zet encryptie aan
2. Open puttygen
3. Maak nieuwe sleutel aan
	* Parameters: ED25519
	* Klik 'Generate' en beweeg met muis over het vlak
	* Key comment luuk_thuis
	* Klick 'Save private key' (in zojuist aangemaakte keys dir)
4. Ga naar github.com en copy/paste public key in het add SSH gebeuren

## Git setup

1. Sla '.gitconfig' op in %USERPROFILE%
2. Omgevingsvariabele instellen zodat git pageagent gebruikt
	* Toets WIN + PAUSE
	* Geavanceerde systeeminstellingen
	* Omgevingsvariablelen
	* Nieuw: Naam - 'GIT_SSH' Waarde: 'C:\Program Files\PuTTY\plink.exe' (zonder quotes)
