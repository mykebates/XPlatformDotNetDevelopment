
# Cross-Platform .NET Development
![fit, original](http://www.thepowerbase.com/wp-content/uploads/2015/04/vso.png)

---

# [fit]BIG DEAL

---

![filtered](balmer.gif)

---

# Pff, Macs and Linux.  Why should we care?

---

- New workflows and technologies
- New market opportunities
- Platform diversification
- Server consolidation(less of $$$)
- New developers
- New era

---

![left, original](https://i3-vso.sec.s-msft.com/dynimg/IC794090.png)

## Open Source
## Cross-Platform
## Simmed Down
## Extra Awesome

---

![fit](stack.png)

---

# .NET Core
- Modular runtime and library implementation
- Includes a subset of the .NET Framework
- OS X and Linux still in progress
- Distributed via NuGet
- Portable

---

# Open Source
- Unprecedented early access
- Help provide direction
- Transparency

---

# [fit] BETA
#### Seriously

---

# Running Windows?
## Install latest and done
### It just works
![inline](balmerrun.gif)

---

# On a Mac?
## It just wor... n/m.
![inline](apple.png)

---

![left, original](https://cldup.com/_H9Pr3YaeC-3000x3000.png)
## File -> New Project
### ...Not so fast
![inline, 75%](terminal.png)

---

![original, fit](https://cldup.com/nuoYqvUaut-3000x3000.png)

---

# Command Line Tools
- Homebrew
- Node.js + NPM
- Yeoman
- DNVM
- DNX
- DNU
- Hipster Cred

---

# Homebrew
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

---

# Node.js
![original, inline](https://cldup.com/s6U8npTpCd-3000x3000.png)

---

## OR
## `brew install node`

---

# Yeoman

`npm install -g yo`

![original, right](http://mjt01.github.io/slides-yeoman/images/yeoman6.png)

---

# Brew Tap

```bash
brew tap aspnet/dnx
brew update
brew install dnvm
```
<br>

Add dnvm to your bash profile<br>(./bash_profile)
`source dnvm.sh`

![right autoplay mute loop](tappy.mp4)

---

![autoplay fit](dnvm.mp4)

---

# DNVM
## .NET Version Manager
- Download versions of .NET Execution Environment(DNX)
- Easily switch between DNX versions

---

# DNX
## .NET Execution Environment
- Contains the code required to bootstrap and run an application - `dnx . kestrel`
- If installed with DNVM, DNX is in your path
- No more "design time" (blur the lines between compilation and loading)...
- Run custom commands

---

# DNU
## DNX Utility
- Responsible for all operations involved with packages in your application.
- Restore, Install, Publish, Build, List, etc