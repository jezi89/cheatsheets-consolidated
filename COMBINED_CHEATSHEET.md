# 📚 Combined Technology Cheatsheet

## 📖 Inleiding

Dit is een uitgebreide gecombineerde cheatsheet voor moderne webontwikkeling technologieën. De content is zorgvuldig verzameld uit drie bronnen binnen het devhints.io project:

1. **Root directory** - De hoofdmap met originele markdown cheatsheets
2. **Reference cheat sheets copy** - Aanvullende referentie cheatsheets met extra details
3. **Awesome cheatsheets copy** - Praktische code voorbeelden uit .js, .sh, .css en andere formaten

Voor elke technologie wordt:
- Een korte introductie gegeven over wat je ermee kunt doen
- De learning curve aangegeven (🟢 Makkelijk | 🟡 Gemiddeld | 🔴 Moeilijk)
- Content uit alle drie de bronnen gecombineerd waar beschikbaar

## 📑 Inhoudsopgave

### 🛠️ Build Tools & Development Environment
- [Node.js & NPM](#nodejs--npm)
- [Bash/Shell Commands](#bashshell-commands)
- [Linux Shell Tools](#linux-shell-tools)
- [Git Version Control](#git-version-control)
- [GitHub Platform](#github-platform)
- [Docker Containers](#docker-containers)
- [SSH & Remote Access](#ssh--remote-access)
- [Vim Editor](#vim-editor)
- [WebStorm IDE](#webstorm-ide)
- [Visual Studio Code](#visual-studio-code)

### ⚛️ Frontend Framework & Core Libraries
- [React](#react)
- [React Router](#react-router)
- [JavaScript ES6+/ESNext](#javascript-es6esnext)
- [TypeScript](#typescript)
- [Express.js](#expressjs)

### 🎨 Styling & Design
- [CSS3 & Modern CSS](#css3--modern-css)
- [SCSS/Sass](#scsssass)
- [Tailwind CSS](#tailwind-css)
- [Figma](#figma)
- [Adobe Tools](#adobe-tools)
- [GIMP](#gimp---gnu-image-manipulation-program)
- [Sketch/SketchUp](#-sketchsketchup---design-tools)

### 🎯 Canvas & Visualization
- [HTML5 Canvas API](#html5-canvas-api)
- [SVG Graphics](#svg-graphics)
- [Framer Motion](#framer-motion)

### 🗄️ Backend & Database
- [PostgreSQL](#postgresql)
- [SQL Queries](#sql-queries)
- [Heroku Platform](#heroku-platform)
- [Nginx Web Server](#nginx-web-server)

### 📡 HTTP & API Integration
- [REST APIs](#rest-apis)
- [JSON Data Format](#json-data-format)
- [cURL Commands](#curl-commands)
- [HTTP Status Codes](#http-status-codes)

### 💾 Data Storage & Management
- [localStorage & sessionStorage](#localstorage--sessionstorage)

### 🧪 Testing & Quality Assurance
- [Puppeteer](#-puppeteer---browser-automation)
- [Vitest](#-vitest---modern-testing-framework)
- [Playwright](#-playwright---end-to-end-testing)
- [Jest](#-jest---javascript-testing-framework)

### 🔧 Development Tools
- [Chrome DevTools](#chrome-devtools)
- [Google Chrome](#google-chrome)
- [FFmpeg Media Tool](#ffmpeg-media-tool)
- [OpenSSL](#openssl)
- [RegExp/Regex](#regexpregex)

### 🌐 Web Technologies & APIs
- [HTML5](#-html5---modern-web-markup)
- [DOM API](#-dom-api---document-object-model)
- [Fetch API](#-fetch-api---modern-http-requests)
- [Emmet](#-emmet---htmlcss-abbreviations)

### 📝 Documentation & Content
- [Markdown](#-markdown---lightweight-markup-language)
- [JSDoc](#-jsdoc---javascript-documentation)
- [YAML](#-yaml---yaml-aint-markup-language)
- [TOML](#-toml---toms-obvious-minimal-language)
- [XML](#-xml---extensible-markup-language)

### 🎭 UI Components & Icons
- [Emoji Reference](#-emoji-reference)
- [ASCII Codes](#-ascii-codes)
- [HTML Character Entities](#-html-character-entities)

### 🔐 Security & Authentication
- [CORS](#-cors---cross-origin-resource-sharing)
- [File Permissions (chmod)](#-file-permissions-chmod)
- [Conventional Commits](#-conventional-commits)

### 📦 Package Management & Deployment
- [package.json](#-packagejson)

### 🗂️ Project Structure & Architecture
- [JavaScript Patterns](#-javascript-patterns)
- [Aspect Ratios](#-aspect-ratios)
- [Screen Resolutions](#-screen-resolutions)

### 🖥️ Operating Systems & Tools
- [Windows Shortcuts](#-windows-shortcuts)
- [PowerShell](#-powershell)
- [Ubuntu Commands](#-ubuntu-commands)
- [Cron Jobs](#-cron-jobs)


### 🔍 Search & Navigation
- [XPath](#xpath)
- [Find Command](#find-command)

### 🤖 AI & Automation
- [AI Tools](#ai-tools)

### 📱 Mobile Development
- [ADB (Android Debug Bridge)](#adb-android-debug-bridge)

### 🌍 Internationalization
- [ISO 639-1 Language Codes](#iso-639-1-language-codes)
- [MIME Types](#mime-types)

### 💼 Collaboration & Productivity
- [Microsoft Teams](#microsoft-teams)
- [Notion](#notion)
- [Outlook](#outlook)
- [Airtable](#airtable)
- [1Password](#1password)

### 🎵 Media & Entertainment
- [YouTube](#youtube)
- [Spotify](#spotify)
- [SoundCloud](#soundcloud)
- [VLC Media Player](#vlc-media-player)

## 🚫 Technologieën NIET gevonden

De volgende moderne technologieën konden niet worden gevonden in de cheatsheet collectie:
- **Vite** - Lightning fast build tool
- **ESLint** - JavaScript linter
- **JSX** - React syntax extension
- **Konva.js** - 2D canvas library
- **Pixi.js** - WebGL renderer
- **Three.js** - 3D graphics library
- **Supabase** - Open source Firebase alternative
- **Axios** - Promise based HTTP client
- **Vitest** - Blazing fast unit testing
- **Playwright** - Modern E2E testing
- **Storybook** - Component documentation
- **Lodash** - JavaScript utility library
- **Chart.js / D3.js** - Data visualization
- **IndexedDB / Dexie.js** - Client-side storage
- **Lucide React** - Modern icon library
- **JWT / OAuth** - Authentication standards
- **Papaparse** - CSV parsing
- **MathJS** - Math library
- **Recharts / Plotly** - React charting
- **React Testing Library** - Component testing
- **Postman** - API testing (alleen genoemd, geen cheatsheet)
- **Claude AI / GitHub Copilot** - AI assistants
- **Web Audio API** - Audio processing
- **WaveSurfer.js** - Audio waveforms
- **Tone.js** - Web audio framework
- **p5.js** - Creative coding
- **MediaStream Recording API** - Media recording
- **File API / Blob API** - File handling
- **FormData API** - Form handling

---

# 🛠️ BUILD TOOLS & DEVELOPMENT ENVIRONMENT

## Node.js & NPM

**Wat is het?** Node.js is een JavaScript runtime voor server-side development. NPM is de package manager voor JavaScript.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Backend APIs, build tools, command-line tools, real-time applicaties

### 📁 Bron: Root directory - nodejs.md

#### Globals
```javascript
__filename  // Absolute path van huidige file
__dirname   // Absolute path van huidige directory
```

#### Child Process - Exec
```javascript
var exec = require('child_process').exec;

var child = exec('cat *.js bad_file | wc -l',
  function (error, stdout, stderr) {
    console.log('stdout: ' + stdout);
    console.log('stderr: ' + stderr);
    if (error !== null) {
      console.log('exec error: ' + error);
    }
});
```

#### Child Process - Spawn (passthru I/O)
```javascript
var spawn = require('child_process').spawn;
var proc = spawn(bin, argv, { stdio: 'inherit' });

proc.on('error', function(err) {
  if (err.code == "ENOENT") { /* does not exist */ }
  if (err.code == "EACCES") { /* not executable */ }
});

proc.on('exit', function(code) { 
  // Process exited with code
});
```

### 📁 Bron: Awesome cheatsheets - backend/node.js

#### Basic Web Server
```javascript
var http = require('http');

http.createServer(function (request, response) {
  response.writeHead(200, {'Content-Type': 'text/plain'});
  response.end('Hello World\n');
}).listen(8124);

console.log('Server running at http://127.0.0.1:8124/');
```

#### Global Objects
```javascript
__filename;  // The filename of the code being executed (absolute path)
__dirname;   // Directory name of currently executing script (absolute path)
module;      // Reference to current module
exports;     // Shorthand for module.exports
process;     // Global process object (EventEmitter instance)
Buffer;      // Global type for binary data
```

#### Console Methods
```javascript
console.log([data], [...]);             // Print to stdout with newline
console.info([data], [...]);            // Same as console.log
console.error([data], [...]);           // Print to stderr
console.warn([data], [...]);            // Same as console.error
console.dir(obj);                       // Inspect object
console.time(label);                    // Start timer
console.timeEnd(label);                 // End timer
console.trace(label);                   // Print stack trace
console.assert(expression, [message]);  // Assert expression is true
```

#### Timers
```javascript
setTimeout(callback, delay, [arg], [...]);   // One-time delayed execution
clearTimeout(t);                             // Cancel setTimeout
setInterval(callback, delay, [arg], [...]);  // Repeated execution
clearInterval(t);                            // Cancel setInterval
setImmediate(callback, [arg], [...]);        // Execute after I/O events
clearImmediate(immediateObject);             // Cancel setImmediate
```

#### Modules
```javascript
// Loading modules
var module = require('./module.js');
module.require('./another_module.js');

// Module properties
module.id;        // Module identifier (filename)
module.filename;  // Fully resolved filename
module.loaded;    // Loading status
module.parent;    // Parent module
module.children;  // Child modules

// Exporting
exports.area = function (r) {
  return Math.PI * r * r;
};

// Export constructor or complete object
module.exports = function(width) {
  return {
    area: function() {
      return width * width;
    }
  };
}
```

### 📁 Bron: Root directory - npm.md 

#### Package Management
| Command | Description |
| --- | --- |
| `npm i` | Alias for `npm install` |
| `npm install` | Install everything in package.json |
| `npm install --production` | Install everything except devDependencies |

#### Adding Packages
| Command | Description |
| --- | --- |  
| `npm install lodash` | Install a package |
| `npm install --save-dev lodash` | Install as devDependency |
| `npm install --save-exact lodash` | Install with exact version |

#### Listing & Info
| Command | Description |
| --- | --- |
| `npm list` | List installed versions of all dependencies | 
| `npm list -g --depth 0` | List globally installed packages | 
| `npm view` | List latest versions of all dependencies | 
| `npm outdated` | List outdated dependencies |

#### Updating & Removing
| Command | Description |
| --- | --- |
| `npm update` | Update production packages |
| `npm update --dev` | Update dev packages |
| `npm update -g` | Update global packages |
| `npm update lodash` | Update specific package |
| `npm rm lodash` | Remove package |

#### Version Management
| Command | Description |
| --- | --- |
| `npm version 1.2.3` | Bump to specific version |
| `npm version major` | Bump major version (1.2.3 → 2.0.0) |
| `npm version minor` | Bump minor version (1.2.3 → 1.3.0) |
| `npm version patch` | Bump patch version (1.2.3 → 1.2.4) |

---

## Bash/Shell Commands

**Wat is het?** Bash is de standaard command-line shell op Linux/macOS voor scripting en automatisering.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** System automation, file manipulation, build scripts, server management

### 📁 Bron: Root directory - bash.md

#### Getting Started
```bash
#!/usr/bin/env bash

name="John"
echo "Hello $name!"
```

#### Variables
```bash
name="John"
echo $name       # Risky - unquoted
echo "$name"     # Safe - quoted
echo "${name}!"  # Safe - with text concatenation

# Variables with wildcards/options
wildcard="*.txt"
options="iv"
cp -$options $wildcard /tmp
```

#### String Quotes
```bash
name="John"
echo "Hi $name"  #=> Hi John (variables expand)
echo 'Hi $name'  #=> Hi $name (literal)
```

#### Command Substitution
```bash
echo "I'm in $(pwd)"
echo "I'm in `pwd`"  # Old style - avoid
```

#### Conditional Execution
```bash
git commit && git push        # Run if previous succeeds
git commit || echo "Failed"   # Run if previous fails
```

#### Functions
```bash
get_name() {
  echo "John"
}

echo "You are $(get_name)"
```

#### Conditionals
```bash
if [[ -z "$string" ]]; then
  echo "String is empty"
elif [[ -n "$string" ]]; then
  echo "String is not empty"
fi
```

#### Strict Mode
```bash
set -euo pipefail  # Exit on error, undefined vars, pipe failures
IFS=$'\n\t'        # Set Internal Field Separator
```

#### Brace Expansion
```bash
echo {A,B}.js           #=> A.js B.js
echo {1..5}             #=> 1 2 3 4 5
echo {{1..3},{7..9}}    #=> 1 2 3 7 8 9
```

#### Parameter Expansions
```bash
name="John"
echo "${name}"
echo "${name/J/j}"      #=> "john" (substitution)
echo "${name:0:2}"      #=> "Jo" (slicing)
echo "${name::2}"       #=> "Jo" (slicing)
echo "${name::-1}"      #=> "Joh" (slicing)
echo "${name:(-1)}"     #=> "n" (slicing from right)
echo "${name:(-2):1}"   #=> "h" (slicing from right)
echo "${food:-Cake}"    #=> $food or "Cake" (default value)
```

### 📁 Bron: Reference cheat sheets copy - bash.md

#### Arguments & Special Parameters
| Expression | Description |
| --- | --- |
| `$1` … `$9` | Parameter 1 ... 9 |
| `$0` | Name of the script itself |
| `${10}` | Positional parameter 10 |
| `$#` | Number of arguments |
| `$$` | Process id of the shell |
| `$*` | All arguments |
| `$@` | All arguments, starting from first |
| `$-` | Current options |
| `$_` | Last argument of the previous command |

#### Multi-line Comments
```bash
: '
This is a
very neat comment
in bash
'
```

### 📁 Bron: Awesome cheatsheets - languages/bash.sh

#### Keyboard Shortcuts
```bash
CTRL+A  # move to beginning of line
CTRL+E  # move to end of line
CTRL+K  # delete forward to end of line
CTRL+U  # delete backward to beginning of line
CTRL+W  # delete word backward
CTRL+Y  # paste (yank) deleted text
CTRL+L  # clear screen
CTRL+C  # halt current command
CTRL+D  # logout/exit
CTRL+Z  # suspend current command (fg/bg to resume)

CTRL+R  # search command history backward
CTRL+S  # search command history forward
CTRL+P  # previous command in history
CTRL+N  # next command in history

ALT+B   # move backward one word
ALT+F   # move forward one word
ALT+D   # delete next word
ALT+.   # paste last argument from previous command

!!      # repeat last command
!n      # repeat command n from history
!string # repeat command starting with string
```

#### Environment & Shell Info
```bash
env                 # display all environment variables
echo $SHELL         # display current shell
echo $BASH_VERSION  # display bash version
whereis bash        # locate bash binary, source, manual
which bash          # find bash executable path
```

#### File Operations
```bash
ls                  # list files in current directory
ls -l               # long format with permissions, size, date
ls -a               # show all files including hidden (.)
ls -la              # combine long format and all files
ln -s file link     # create symbolic link
readlink link       # show symbolic link target
tree                # show directory tree structure
touch filename      # create/update file timestamp
mktemp -t name      # create temp file in /tmp/
cat file            # display file content
cat -n file         # display with line numbers
nl file             # show file with line numbers
head file           # show first 10 lines
head -n 20 file     # show first 20 lines
tail file           # show last 10 lines
tail -f file        # follow file updates in real-time
```

---

## Git Version Control

**Wat is het?** Git is het meest gebruikte version control systeem voor het beheren van code wijzigingen.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Source control, collaboration, versioning, branching strategies

### 📁 Bron: Root directory - git-branch.md

#### Working with Branches
```bash
# Create and switch to new branch
git checkout -b branchname
git push origin branchname --set-upstream

# Get branch from remote
git fetch origin
git checkout --track origin/branchname

# List branches
git branch --list              # local branches
git branch -a --merged         # merged branches
git branch -r                  # remote branches

# Delete branches
git branch -d branchname       # delete local branch
git push origin --delete branchname  # delete remote
git remote prune origin        # clean up stale branches
```

### 📁 Bron: Reference cheat sheets copy - git.md

#### Repository Setup
```bash
# Create new repository
git init [project-name]

# Clone repository
git clone git_url
git clone git_url my_directory
```

#### Basic Workflow
```bash
# Check status
git status

# Stage changes
git add [file]              # stage specific file
git add .                   # stage all changes

# Commit changes
git commit -m "message"     # commit staged files
git commit -am "message"    # stage and commit tracked files

# Undo changes
git restore [file]          # discard unstaged changes
git restore --staged [file] # unstage file
```

### 📁 Bron: Awesome cheatsheets - tools/git.sh

#### Repository & Remote
```bash
git init                                              # initialize git in current directory
git remote add origin https://github.com/repo.git    # add remote repository
git clone <address>                                   # clone repository
git clone <address> -b <branch> <path>               # clone specific branch to path
git clone <address> -b <branch> --single-branch      # clone single branch only

# Remote management
git remote                   # show remotes
git remote -v               # show remote URLs
git remote add name <url>   # add new remote
git remote rm name          # remove remote
```

#### Staging & Committing
```bash
# Staging
git add <file>        # stage specific file
git add *             # stage all changes
git reset <file>      # unstage file
git rm <file>         # remove file from git and filesystem
git rm --cached <file> # remove from git index only

# Reset commands
git reset --soft <commit>   # move HEAD only
git reset --mixed <commit>  # move HEAD + reset staging (default)
git reset --hard <commit>   # move HEAD + reset staging + working dir

# Committing
git commit -m "message"                              # commit with message
git commit -m "title" -m "description"              # commit with title and description
git commit --amend                                   # modify last commit
git commit --amend --no-edit                        # amend without changing message
git commit --amend --author='Name <email@example.com>' # change author
```

#### Branching & Merging
```bash
# Branch management
git branch                    # list local branches
git branch -a                 # list all branches (local + remote)
git branch -vv                # list branches with upstreams and last commit
git branch <name>             # create new branch
git branch -d <name>          # delete branch
git branch -m <new-name>      # rename current branch
git checkout <branch>         # switch to branch
git checkout -b <branch>      # create and switch to branch
git checkout --orphan <name>  # create branch with no history

# Merging
git merge <branch>            # merge branch into current
git cherry-pick <commit>      # apply specific commit
git cherry-pick <A>^..<B>     # apply range of commits (A to B)
```

#### Stashing
```bash
git stash                     # stash changes
git stash -u                  # stash including untracked files
git stash save "message"      # stash with description
git stash list                # list all stashes
git stash pop                 # apply and remove latest stash
git stash pop stash@{2}       # apply and remove specific stash
git stash apply               # apply but keep stash
git stash show                # show stash contents
git stash drop stash@{1}      # delete specific stash
git stash clear               # delete all stashes
git stash branch <name> stash@{1} # create branch from stash
```

#### History & Inspection
```bash
# Log viewing
git log                       # show commit history
git log --oneline            # compact log view
git log --oneline --graph --decorate  # graphical log view
git log --since="2 weeks ago" # commits since date
git log -p <file>            # file change history
git log -n 5                 # last 5 commits
git log <branch1> ^<branch2> # commits in branch1 not in branch2
git log --grep='pattern'     # search commit messages

# Other inspection
git reflog                   # show reference log
git show                     # show last commit details
git diff                     # show unstaged changes
git diff --staged            # show staged changes
git diff HEAD                # changes vs last commit
git grep -n 'pattern'        # search in tracked files
```

#### Tags
```bash
git tag                      # list tags
git tag -a v1.0 -m "msg"     # create annotated tag
git show v1.0                # show tag details
git tag --delete v1.0        # delete local tag
git push origin v1.0         # push tag to remote
git push --delete origin v1.0 # delete remote tag
git fetch --tags             # fetch all tags
```

#### Cleanup & Maintenance
```bash
git clean -f                 # remove untracked files
git clean -fd                # remove untracked files and directories
git clean -fX                # remove ignored files
git clean -fx                # remove ignored and untracked files
git clean -d --dry-run       # preview what would be deleted
```

---

## GitHub Platform

**Wat is het?** GitHub is het grootste platform voor code hosting, collaboration en version control.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** Code hosting, collaboration, issue tracking, CI/CD, documentation

### 📁 Bron: Reference cheat sheets copy - github.md

#### Keyboard Shortcuts - Navigation
| Shortcut | Action |
| --- | --- |
| `S` | Focus the search bar |
| `G` `N` | Go to your notifications |
| `H` | Open user/issue/PR hovercard |
| `Esc` | Close hovercard |

#### Repository Navigation
| Shortcut | Action |
| --- | --- |
| `G` `C` | Go to Code tab |
| `G` `I` | Go to Issues tab |
| `G` `P` | Go to Pull requests tab |
| `G` `B` | Go to Projects tab |
| `G` `W` | Go to Wiki tab |

#### Source Code Browsing
| Shortcut | Action |
| --- | --- |
| `T` | Activate file finder |
| `L` | Jump to line in code |
| `W` | Switch branch or tag |
| `Y` | Get permanent link to file |
| `I` | Toggle diff comments |
| `B` | Open blame view |

#### Editing Shortcuts
| Shortcut | Action |
| --- | --- |
| `Ctrl` `F` | Search in file |
| `Ctrl` `G` | Find next |
| `Ctrl` `Shift` `G` | Find previous |
| `Ctrl` `Shift` `F` | Replace |
| `Ctrl` `Shift` `R` | Replace all |
| `Alt` `G` | Jump to line |

#### Comment Shortcuts
| Shortcut | Action |
| --- | --- |
| `Ctrl` `B` | Bold text |
| `Ctrl` `I` | Italic text |
| `Ctrl` `K` | Insert link |
| `Ctrl` `Shift` `P` | Toggle Write/Preview |
| `Ctrl` `Enter` | Submit comment |
| `R` | Quote selected text |

---

## Docker Containers

**Wat is het?** Docker is een platform voor het bouwen, deployen en draaien van applicaties in containers.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Containerization, microservices, development environments, deployment

### 📁 Bron: Root directory - docker.md

#### Building Images
```bash
# Build image from Dockerfile
docker build [options] .
  -t "app/container_name"              # Name your image
  --build-arg APP_HOME=$APP_HOME       # Set build-time variables

# Example
docker build -t myapp:latest .
```

#### Running Containers
```bash
# Run container from image
docker run [options] IMAGE
  -it                        # Interactive with TTY
  -d                         # Detached mode (background)
  --name NAME                # Name container
  -p 5000:5000              # Port mapping (host:container)
  -v /host/path:/container  # Volume mount
  -e VAR=value              # Environment variable
  --rm                      # Remove after exit

# Example
docker run -it debian:buster /bin/bash
docker run -d -p 8080:80 --name webserver nginx
```

#### Container Management
```bash
# Create container without starting
docker create [options] IMAGE
  -a, --attach               # Attach stdout/err
  -i, --interactive          # Attach stdin
  -t, --tty                  # Pseudo-tty
  --name NAME                # Name your container
  -p, --publish 5000:5000    # Port map
  --expose 5432              # Expose port to linked containers
  -P, --publish-all          # Publish all ports
  --link container:alias     # Link containers
  -v, --volume `pwd`:/app    # Mount volume
  -e, --env NAME=hello       # Environment variables

# Start/stop containers
docker start [options] CONTAINER
docker stop [options] CONTAINER
docker restart CONTAINER

# List containers
docker ps                    # Running containers
docker ps -a                 # All containers
docker ps -q                 # Only IDs
```

#### Execute Commands
```bash
docker exec [options] CONTAINER COMMAND
  -d, --detach        # Run in background
  -i, --interactive   # Keep STDIN open
  -t, --tty           # Allocate pseudo-TTY

# Examples
docker exec app_web_1 tail logs/development.log
docker exec -it app_web_1 /bin/bash
docker exec -it app_web_1 rails console
```

### 📁 Bron: Reference cheat sheets copy - docker.md

#### Container Lifecycle
| Command | Description |
| --- | --- |
| `docker start container` | Start container |
| `docker stop container` | Stop container gracefully |
| `docker restart container` | Restart container |
| `docker pause container` | Pause container |
| `docker unpause container` | Unpause container |
| `docker wait container` | Wait for container to stop |
| `docker kill container` | Force stop container |
| `docker attach container` | Attach to running container |

#### Container Information
| Command | Description |
| --- | --- |
| `docker ps` | List running containers |
| `docker ps -a` | List all containers |
| `docker ps -s` | List with size info |
| `docker logs container` | View container logs |
| `docker logs -f container` | Follow log output |
| `docker inspect container` | Detailed container info |
| `docker events container` | Real-time container events |
| `docker port container` | Show port mappings |
| `docker top container` | Show running processes |
| `docker stats container` | Show resource usage |
| `docker diff container` | Show filesystem changes |

### 📁 Bron: Awesome cheatsheets - tools/docker.sh

#### Image Management
```bash
docker images -a                            # List all images
docker build -t friendlyname .              # Build image from Dockerfile
docker tag image username/repository:tag    # Tag image for registry
docker push username/repository:tag         # Push to registry
docker pull username/repository:tag         # Pull from registry
docker rmi imagename                        # Remove image
docker rmi $(docker images -q)              # Remove all images
```

#### Container Cleanup
```bash
docker rm container                         # Remove container
docker rm -f container                      # Force remove running container
docker rm $(docker ps -a -q)                # Remove all containers
docker system prune                         # Remove unused resources
docker system prune -a                      # Remove all unused resources
docker volume prune                         # Remove unused volumes
docker network prune                        # Remove unused networks
```

#### Docker Compose
```bash
docker-compose up                           # Start services
docker-compose up -d                        # Start in detached mode
docker-compose down                         # Stop and remove
docker-compose logs                         # View logs
docker-compose logs -f                      # Follow logs
docker-compose restart                      # Restart all services
docker-compose pull                         # Pull all images
docker-compose build                        # Build all services
docker-compose config                       # Validate compose file
docker-compose scale service=n              # Scale service
docker-compose top                          # Show running processes
```

#### Docker Services (Swarm)
```bash
docker service create image                 # Create service
docker service ls                           # List services
docker service ps service                   # List tasks
docker service scale service=n              # Scale service
docker service update service               # Update service
docker service inspect service              # Inspect service
```

---

## SSH & Remote Access

**Wat is het?** SSH (Secure Shell) is een protocol voor veilige remote toegang tot servers.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Remote server access, file transfer, tunneling, automation

### 📁 Bron: Root directory - ssh.md (als beschikbaar)

#### Basic SSH Commands
```bash
# Connect to server
ssh user@hostname
ssh -p 2222 user@hostname          # Custom port
ssh -i ~/.ssh/key.pem user@host    # With key file

# SSH Key Generation
ssh-keygen -t rsa -b 4096          # Generate RSA key
ssh-keygen -t ed25519              # Generate Ed25519 key
ssh-copy-id user@hostname          # Copy key to server

# SSH Config (~/.ssh/config)
Host myserver
    HostName 192.168.1.100
    User myuser
    Port 2222
    IdentityFile ~/.ssh/mykey

# File Transfer
scp file.txt user@host:/path/      # Copy file to remote
scp user@host:/path/file.txt .     # Copy from remote
scp -r folder/ user@host:/path/    # Copy directory

# SSH Tunneling
ssh -L 8080:localhost:80 user@host # Local port forwarding
ssh -R 8080:localhost:80 user@host # Remote port forwarding
ssh -D 1080 user@host              # SOCKS proxy
```

---

## Vim Editor

**Wat is het?** Vim is een krachtige, configureerbare teksteditor voor efficiënt code editing.  
**Learning curve:** 🔴 Moeilijk  
**Gebruik voor:** Text editing, code editing, configuration files, remote editing

### 📁 Bron: Root directory - vim.md

#### Basic Operations
| Shortcut | Description |
| --- | --- |
| `:q` | Close file |
| `:qa` | Close all files |
| `:w` | Save |
| `:wq` / `:x` | Save and close |
| `ZZ` | Save and quit |
| `:q!` / `ZQ` | Quit without saving |

#### Mode Switching
| Shortcut | Description |
| --- | --- |
| `Esc` / `<C-[>` | Exit insert mode |
| `i` | Insert mode |
| `a` | Append mode |
| `v` | Visual mode |
| `V` | Visual line mode |
| `<C-V>` | Visual block mode |
| `R` | Replace mode |

#### Editing Commands
| Shortcut | Description |
| --- | --- |
| `a` | Append after cursor |
| `A` | Append at end of line |
| `i` | Insert before cursor |
| `I` | Insert at beginning of line |
| `o` | Open new line below |
| `O` | Open new line above |
| `s` | Delete char and insert |
| `S` | Delete line and insert |
| `C` | Delete to end of line and insert |
| `r` | Replace one character |
| `u` | Undo |
| `<C-R>` | Redo |

#### Copy, Cut & Paste
| Shortcut | Description |
| --- | --- |
| `x` | Delete character |
| `dd` | Delete (cut) line |
| `yy` | Yank (copy) line |
| `p` | Paste after |
| `P` | Paste before |
| `"*p` / `"+p` | Paste from system clipboard |
| `"*y` / `"+y` | Copy to system clipboard |

#### Navigation
| Shortcut | Description |
| --- | --- |
| `h` `j` `k` `l` | Left, Down, Up, Right |
| `w` / `b` | Next/Previous word |
| `e` / `ge` | End of word forward/backward |
| `0` / `$` | Start/End of line |
| `^` | First non-blank character |
| `gg` / `G` | Go to first/last line |
| `<C-U>` / `<C-D>` | Half-page up/down |
| `<C-B>` / `<C-F>` | Full page up/down |

### 📁 Bron: Reference cheat sheets copy - vim.md

#### Advanced Navigation
```bash
# Motion diagram for horizontal movement
┌───────────── |
├───────────── 0      $ ──────────────┐
│  ┌────────── ^      fe ────────┐    │
│  │  ┌─────── Fo     te ───────┐│    │
│  │  │┌────── To     30| ───┐  ││    │
│  │  ││ ┌──── ge     w ───┐ │  ││    │
│  │  ││ │ ┌── b      e ─┐ │ │  ││    │
│  │  ││ │ │  ┌h      l┐ │ │ │  ││    │
▽  ▽  ▽▽ ▽ ▽  ▽▼      ▼▽ ▽ ▽ ▽  ▽▽    ▽
```

---

## WebStorm IDE

**Wat is het?** WebStorm is een krachtige IDE van JetBrains speciaal voor JavaScript en web development.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** JavaScript/TypeScript development, React/Vue/Angular, Node.js, debugging, refactoring

### 📁 Bron: Reference cheat sheets copy - webstorm.md

#### Essential Shortcuts (Windows/Linux)

##### Basic Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Space` | Basic code completion |
| `Alt` `Enter` | Show intention actions, quick fixes |
| `Ctrl` `P` | Parameter info |
| `Ctrl` `Q` | Quick documentation lookup |
| `Alt` `Insert` | Generate code... |
| `Ctrl` `Alt` `T` | Surround with... |
| `Ctrl` `J` | Insert Live template |
| `Ctrl` `/` | Comment/uncomment with line |
| `Ctrl` `Shift` `/` | Comment/uncomment with block |

##### Code Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl` `B` | Go to declaration |
| `Ctrl` `N` | Go to class |
| `Ctrl` `Shift` `N` | Go to file |
| `Ctrl` `Alt` `Shift` `N` | Go to symbol |
| `Ctrl` `G` | Go to line |
| `Ctrl` `E` | Recent files popup |
| `Alt` `F1` | Select current file or symbol in any view |

##### Code Manipulation
| Shortcut | Action |
|----------|--------|
| `Ctrl` `W` | Select successively increasing code blocks |
| `Ctrl` `Shift` `W` | Decrease current selection to previous state |
| `Ctrl` `D` | Duplicate current line or selected block |
| `Ctrl` `Y` | Delete line at caret |
| `Alt` `Shift` `Up/Down` | Move line up/down |
| `Ctrl` `Shift` `J` | Join lines |
| `Ctrl` `Enter` | Split lines |

##### Search & Replace
| Shortcut | Action |
|----------|--------|
| `Double Shift` | Search everywhere |
| `Ctrl` `F` | Find |
| `Ctrl` `R` | Replace |
| `Ctrl` `Shift` `F` | Find in path |
| `Ctrl` `Shift` `R` | Replace in path |
| `F3` / `Shift` `F3` | Find next/previous |

##### Refactoring
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Alt` `Shift` `T` | Refactor this |
| `Shift` `F6` | Rename |
| `Ctrl` `F6` | Change function signature |
| `Ctrl` `Alt` `M` | Extract Method |
| `Ctrl` `Alt` `V` | Extract Variable |
| `Ctrl` `Alt` `C` | Extract Constant |
| `Ctrl` `Alt` `P` | Extract Parameter |

##### Running & Debugging
| Shortcut | Action |
|----------|--------|
| `Shift` `F10` | Run |
| `Shift` `F9` | Debug |
| `Ctrl` `Shift` `F10` | Run context configuration from editor |
| `F8` | Step over |
| `F7` | Step into |
| `Shift` `F8` | Step out |
| `F9` | Resume program |
| `Ctrl` `F8` | Toggle breakpoint |

##### Multi-cursor & Selection
| Shortcut | Action |
|----------|--------|
| `Alt` `Click` | Add or remove caret |
| `Shift` `Ctrl` `Alt` `J` | Select all occurrences |
| `Alt` `J` | Select next occurrence |
| `Alt` `Shift` `J` | Unselect occurrence |
| `Esc` | Unselect all occurrences or carets |

##### Version Control
| Shortcut | Action |
|----------|--------|
| `Alt` `` ` `` | VCS quick popup |
| `Ctrl` `K` | Commit project to VCS |
| `Ctrl` `T` | Update project from VCS |
| `Alt` `Shift` `C` | View recent changes |

---

## Visual Studio Code

**Wat is het?** Visual Studio Code is een gratis, open-source code editor van Microsoft met uitgebreide extensie ondersteuning.  
**Learning curve:** 🟢 Gemakkelijk  
**Gebruik voor:** Web development, Python, C#, extensies ecosystem, Git integration, debugging

### 📁 Bron: Reference cheat sheets copy - vscode.md

#### Essential Shortcuts (Windows)

##### General
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Shift` `P` | Show Command Palette |
| `Ctrl` `P` | Quick Open, Go to File... |
| `Ctrl` `Shift` `N` | New window/instance |
| `Ctrl` `Shift` `W` | Close window/instance |
| `Ctrl` `,` | User Settings |
| `Ctrl` `K` `Ctrl` `S` | Keyboard Shortcuts |

##### Basic Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl` `X` | Cut line (empty selection) |
| `Ctrl` `C` | Copy line (empty selection) |
| `Alt` `Up/Down` | Move line up/down |
| `Shift` `Alt` `Up/Down` | Copy line up/down |
| `Ctrl` `Shift` `K` | Delete line |
| `Ctrl` `Enter` | Insert line below |
| `Ctrl` `Shift` `Enter` | Insert line above |
| `Ctrl` `Shift` `\` | Jump to matching bracket |

##### Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl` `T` | Show all Symbols |
| `Ctrl` `G` | Go to Line... |
| `Ctrl` `P` | Go to File... |
| `Ctrl` `Shift` `O` | Go to Symbol... |
| `F8` / `Shift` `F8` | Go to next/previous error or warning |
| `Alt` `Left/Right` | Go back/forward |

##### Search and Replace
| Shortcut | Action |
|----------|--------|
| `Ctrl` `F` | Find |
| `Ctrl` `H` | Replace |
| `F3` / `Shift` `F3` | Find next/previous |
| `Alt` `Enter` | Select all occurrences of Find match |
| `Ctrl` `D` | Add selection to next Find match |
| `Ctrl` `K` `Ctrl` `D` | Move last selection to next Find match |

##### Multi-cursor and Selection
| Shortcut | Action |
|----------|--------|
| `Alt` `Click` | Insert cursor |
| `Ctrl` `Alt` `Up/Down` | Insert cursor above/below |
| `Ctrl` `U` | Undo last cursor operation |
| `Shift` `Alt` `I` | Insert cursor at end of each line selected |
| `Ctrl` `Shift` `L` | Select all occurrences of current selection |
| `Ctrl` `F2` | Select all occurrences of current word |

##### Rich Languages Editing
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Space` | Trigger suggestion |
| `Ctrl` `Shift` `Space` | Trigger parameter hints |
| `Shift` `Alt` `F` | Format document |
| `Ctrl` `K` `Ctrl` `F` | Format selection |
| `F12` | Go to Definition |
| `Alt` `F12` | Peek Definition |
| `Ctrl` `.` | Quick Fix |
| `Shift` `F12` | Show References |
| `F2` | Rename Symbol |

##### File Management
| Shortcut | Action |
|----------|--------|
| `Ctrl` `N` | New File |
| `Ctrl` `O` | Open File... |
| `Ctrl` `S` | Save |
| `Ctrl` `Shift` `S` | Save As... |
| `Ctrl` `K` `S` | Save All |
| `Ctrl` `F4` | Close |
| `Ctrl` `K` `Ctrl` `W` | Close All |
| `Ctrl` `Shift` `T` | Reopen closed editor |

##### Editor Management
| Shortcut | Action |
|----------|--------|
| `Ctrl` `\` | Split editor |
| `Ctrl` `1/2/3` | Focus into 1st, 2nd, or 3rd editor group |
| `Ctrl` `K` `Ctrl` `Left/Right` | Focus into previous/next editor group |
| `Ctrl` `Shift` `PgUp/PgDown` | Move editor left/right |

##### Display
| Shortcut | Action |
|----------|--------|
| `F11` | Toggle full screen |
| `Ctrl` `B` | Toggle Sidebar visibility |
| `Ctrl` `Shift` `E` | Show Explorer/Toggle focus |
| `Ctrl` `Shift` `F` | Show Search |
| `Ctrl` `Shift` `G` | Show Source Control |
| `Ctrl` `Shift` `D` | Show Debug |
| `Ctrl` `Shift` `X` | Show Extensions |
| `Ctrl` `K` `Z` | Zen Mode (Esc Esc to exit) |

##### Debug
| Shortcut | Action |
|----------|--------|
| `F9` | Toggle breakpoint |
| `F5` | Start/Continue |
| `Shift` `F5` | Stop |
| `F11` / `Shift` `F11` | Step into/out |
| `F10` | Step over |

##### Integrated Terminal
| Shortcut | Action |
|----------|--------|
| `Ctrl` `` ` `` | Show integrated terminal |
| `Ctrl` `Shift` `` ` `` | Create new terminal |
| `Ctrl` `C` | Copy selection |
| `Ctrl` `V` | Paste into active terminal |

#### Popular Extensions
- **Prettier** - Code formatter
- **ESLint** - JavaScript linter
- **Live Server** - Local development server
- **GitLens** - Enhanced Git capabilities
- **Auto Rename Tag** - HTML tag renaming
- **Bracket Pair Colorizer** - Bracket highlighting
- **Material Icon Theme** - File icons
- **Thunder Client** - REST API testing

---

# ⚛️ FRONTEND FRAMEWORK & CORE LIBRARIES

## React

**Wat is het?** React is een JavaScript library voor het bouwen van user interfaces met component-based architecture.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Single-page applications, complex UIs, mobile apps (React Native), reusable components

### 📁 Bron: Root directory - react.md

#### Components & Setup
```jsx
import React from 'react'
import ReactDOM from 'react-dom'

// Class Component
class Hello extends React.Component {
  render () {
    return <div className='message-box'>
      Hello {this.props.name}
    </div>
  }
}

// Rendering
const el = document.body
ReactDOM.render(<Hello name='John' />, el)
```

#### Props & State
```jsx
// Props
<Video fullscreen={true} autoplay={false} />

// Accessing props
render () {
  this.props.fullscreen
  const { fullscreen, autoplay } = this.props
}

// State
constructor(props) {
  super(props)
  this.state = { username: undefined }
}

// Setting state
this.setState({ username: 'rstacruz' })

// Using state
render () {
  return <div>{this.state.username}</div>
}
```

### 📁 Bron: Reference cheat sheets copy - react.md

#### JSX Basics
```jsx
// JSX Elements
let element = <h1>Hello, world!</h1>;
let emptyHeading = <h1 />;

// JSX Expressions
let name = "Josh Perez";
let element = <h1>Hello, {name}</h1>;

// JSX Attributes
const element = <img src={user.avatarUrl} />;
const element = <button className="btn">Click me</button>;

// JSX Functions
function getName() {
  return "Julie";
}

return <h1>Hi {getName()}!</h1>
```

#### Conditional Rendering
```jsx
function Weather(props) {
  if (props.temperature >= 20) {
    return (
      <p>
        It is {props.temperature}°C (Warm) in {props.city}
      </p>
    );
  } else {
    return (
      <p>
        It is {props.temperature}°C in {props.city}
      </p>
    );
  }
}

// Ternary operator
return (
  <div>
    {isLoggedIn ? <LogoutButton /> : <LoginButton />}
  </div>
)

// Short-circuit evaluation
return (
  <div>
    {showWarning && <WarningMessage />}
  </div>
)
```

### 📁 Bron: Awesome cheatsheets - frontend/react.js

#### React API Basics
```javascript
// Installation
npm install --save react       // React library
npm install --save react-dom   // DOM rendering
npm install --save prop-types  // Type checking

// Creating elements
React.createElement(
  type,
  [props],
  [...children]
)

// Clone element
React.cloneElement(
  element,
  [props],
  [...children]
)

// Validate element
React.isValidElement(object)   // Returns true/false

// React.Children utilities
React.Children.map(children, function)
React.Children.forEach(children, function)
React.Children.count(children)
React.Children.only(children)
React.Children.toArray(children)

// Fragments
React.Fragment  // or <></> syntax
```

#### Component Lifecycle
```javascript
class Component extends React.Component {
  // Constructor
  constructor(props) {
    super(props);
    
    // Bind methods
    this.method = this.method.bind(this);
    
    // Initialize state
    this.state = {
      active: true,
      color: props.initialColor
    };
  }
  
  // Component lifecycle methods
  componentDidMount() {
    // Called after component is mounted
  }
  
  componentDidUpdate(prevProps, prevState) {
    // Called after updating occurs
  }
  
  componentWillUnmount() {
    // Called before component unmounts
  }
  
  // Error handling
  componentDidCatch(error, info) {
    // Catch errors in component tree
  }
  
  // Render
  render() {
    return <div>{this.state.active}</div>
  }
}
```

---

## React Router

**Wat is het?** React Router is de standaard routing library voor React applicaties.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** Client-side routing, navigation, URL management in React apps

### 📁 Bron: Root directory - react-router.md

```jsx
import { BrowserRouter, Route, Link } from 'react-router-dom'

// Basic routing
<BrowserRouter>
  <div>
    <Route exact path="/" component={Home} />
    <Route path="/about" component={About} />
    <Route path="/users/:id" component={User} />
  </div>
</BrowserRouter>

// Navigation
<Link to="/about">About</Link>
<NavLink to="/about" activeClassName="active">About</NavLink>

// Programmatic navigation
this.props.history.push('/about')
this.props.history.replace('/about')
this.props.history.goBack()

// Route props
const User = ({ match, location, history }) => {
  return <div>User ID: {match.params.id}</div>
}

// Nested routes
<Route path="/users" component={Users}>
  <Route path="/users/:id" component={User} />
</Route>

// Route guards
<Route 
  path="/admin" 
  render={() => 
    isAuthenticated ? <Admin /> : <Redirect to="/login" />
  }
/>
```

---

## JavaScript ES6+/ESNext

**Wat is het?** JavaScript ES6+ bevat moderne JavaScript features zoals arrow functions, classes, modules, promises en meer.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Modern web development, React/Vue/Angular apps, Node.js, async programming

### 📁 Bron: Root directory - es6.md

#### Block Scoping
```javascript
// Let - block scoped
function fn () {
  let x = 0
  if (true) {
    let x = 1 // only inside this if block
  }
}

// Const - block scoped constants
const a = 1
// a = 2 // Error: Assignment to constant
```

#### Template Literals
```javascript
// String interpolation
const name = "World"
const message = `Hello ${name}`

// Multiline strings
const str = `
  This is a
  multiline string
`

// Tagged templates
const highlighted = highlight`Hello ${name}!`
```

#### Arrow Functions
```javascript
// Basic syntax
const add = (a, b) => a + b
const square = x => x * x

// With block body
const greet = name => {
  const msg = `Hello ${name}`
  return msg
}

// Returning objects
const makeUser = name => ({ name, age: 0 })

// No 'this' binding
const obj = {
  name: 'Object',
  arrow: () => this.name,     // undefined
  regular() { return this.name } // 'Object'
}
```

#### Classes
```javascript
class Circle extends Shape {
  // Constructor
  constructor(radius) {
    super() // Call parent constructor
    this.radius = radius
  }
  
  // Methods
  getArea() {
    return Math.PI * this.radius ** 2
  }
  
  // Getters/Setters
  get diameter() {
    return this.radius * 2
  }
  
  set diameter(d) {
    this.radius = d / 2
  }
  
  // Static methods
  static createFromDiameter(d) {
    return new Circle(d / 2)
  }
}
```

#### Destructuring
```javascript
// Array destructuring
const [a, b, ...rest] = [1, 2, 3, 4, 5]
// a=1, b=2, rest=[3,4,5]

// Object destructuring
const {name, age = 18} = user
const {name: userName, ...others} = user

// Function parameters
function greet({name, age = 18}) {
  console.log(`${name} is ${age}`)
}

// Nested destructuring
const {address: {city}} = user
```

### 📁 Bron: Reference cheat sheets copy - javascript.md

#### Variables & Data Types
```javascript
// Variable declarations
let x = null;
let name = "Tammy";
const found = false;
var old = "avoid var";

// Data types
let num = 123;           // Number
let str = "Hello";       // String  
let bool = true;         // Boolean
let arr = [1, 2, 3];     // Array
let obj = {a: 1};        // Object
let func = () => {};     // Function
let undef = undefined;   // Undefined
let nul = null;          // Null
let sym = Symbol('id');  // Symbol
```

#### String Methods
```javascript
let str = "Hello World"

// ES6+ String methods
str.includes("World")     // true
str.startsWith("Hello")   // true
str.endsWith("World")     // true
str.repeat(3)             // "Hello WorldHello WorldHello World"
str.padStart(15)          // "    Hello World"
str.padEnd(15, "!")       // "Hello World!!!!"

// Classic methods
str.length                // 11
str.charAt(0)             // "H"
str.indexOf("o")          // 4
str.slice(0, 5)           // "Hello"
str.toUpperCase()         // "HELLO WORLD"
str.split(" ")            // ["Hello", "World"]
str.replace("World", "JS") // "Hello JS"
```

### 📁 Bron: Awesome cheatsheets - languages/javascript.js

#### Promises
```javascript
// Creating promises
const promise = new Promise((resolve, reject) => {
  setTimeout(() => {
    if (Math.random() > 0.5) {
      resolve('Success!')
    } else {
      reject('Error!')
    }
  }, 1000)
})

// Using promises
promise
  .then(result => console.log(result))
  .catch(error => console.error(error))
  .finally(() => console.log('Done'))

// Promise methods
Promise.all([promise1, promise2])      // All must resolve
Promise.race([promise1, promise2])     // First to resolve/reject
Promise.allSettled([p1, p2])          // Wait for all to settle
Promise.any([p1, p2])                 // First to resolve

// Async/Await
async function fetchData() {
  try {
    const response = await fetch('/api/data')
    const data = await response.json()
    return data
  } catch (error) {
    console.error('Failed:', error)
  }
}
```

---

## TypeScript

**Wat is het?** TypeScript is een typed superset van JavaScript dat compileert naar plain JavaScript.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Large-scale applications, better IDE support, type safety, modern JavaScript features

### 📁 Bron: Root directory - typescript.md

#### Basic Types
```typescript
// Primitives
let isDone: boolean = false
let age: number = 30
let userName: string = "John"

// Arrays
let list: number[] = [1, 2, 3]
let list2: Array<number> = [1, 2, 3]

// Tuple
let tuple: [string, number] = ["hello", 10]

// Enum
enum Color {
  Red,
  Green,
  Blue = 4
}
let c: Color = Color.Green

// Any, Unknown, Never
let notSure: any = 4
let value: unknown = 4
let error: never  // unreachable

// Union types
let id: string | number = "abc123"

// Type assertions
let len: number = (input as string).length
let len2: number = (<string>input).length
```

#### Interfaces
```typescript
// Basic interface
interface Person {
  firstName: string
  lastName: string
  age?: number        // Optional
  readonly id: number // Read-only
}

// Function interface
interface SearchFunc {
  (source: string, subString: string): boolean
}

// Class interface
interface ClockInterface {
  currentTime: Date
  setTime(d: Date): void
}

// Extending interfaces
interface Employee extends Person {
  department: string
}
```

#### Functions
```typescript
// Function types
function add(x: number, y: number): number {
  return x + y
}

// Arrow functions
const multiply = (x: number, y: number): number => x * y

// Optional and default parameters
function buildName(first: string, last?: string): string {
  return first + (last ? " " + last : "")
}

function buildName2(first: string, last = "Smith"): string {
  return first + " " + last
}

// Rest parameters
function buildFullName(first: string, ...rest: string[]): string {
  return first + " " + rest.join(" ")
}

// Function overloading
function getValue(x: string): string
function getValue(x: number): number
function getValue(x: any): any {
  return x
}
```

### 📁 Bron: Reference cheat sheets copy - typescript.md

#### Classes
```typescript
class Greeter {
  greeting: string
  
  constructor(message: string) {
    this.greeting = message
  }
  
  greet() {
    return "Hello, " + this.greeting
  }
}

// Inheritance
class Animal {
  protected name: string
  
  constructor(name: string) {
    this.name = name
  }
  
  move(distance: number = 0) {
    console.log(`${this.name} moved ${distance}m`)
  }
}

class Dog extends Animal {
  bark() {
    console.log("Woof! Woof!")
  }
}

// Abstract classes
abstract class Department {
  abstract generateReports(): void
}
```

#### Generics
```typescript
// Generic function
function identity<T>(arg: T): T {
  return arg
}

// Generic interface
interface GenericIdentityFn<T> {
  (arg: T): T
}

// Generic class
class GenericNumber<T> {
  zeroValue: T
  add: (x: T, y: T) => T
}

// Generic constraints
function loggingIdentity<T extends { length: number }>(arg: T): T {
  console.log(arg.length)
  return arg
}
```

---

## Express.js

**Wat is het?** Express is een minimaal en flexibel Node.js web application framework.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** REST APIs, web servers, middleware, microservices

### 📁 Bron: Root directory - express.md

#### App Configuration
```javascript
const express = require('express')
const app = express()

// Settings
app.set('view engine', 'pug')
app.set('views', './views')
app.get('view engine') //=> 'pug'

app.enable('trust proxy')
app.disable('trust proxy')
app.enabled('trust proxy') //=> true

// Environment
app.get('env') //=> 'development'

// Middleware
app.use(express.static('public'))
app.use(express.json())
app.use(express.urlencoded({ extended: true }))

// Local variables
app.locals.title = "MyApp"
app.locals.email = "admin@myapp.com"
```

#### Request Object
```javascript
// Route: GET /user/tj?sort=desc
app.get('/user/:name', (req, res) => {
  req.path         //=> "/user/tj"
  req.url          //=> "/user/tj?sort=desc"
  req.method       //=> "GET"
  req.params.name  //=> "tj"
  req.query.sort   //=> "desc"
  
  req.cookies      // Cookies
  req.get('Content-Type') // Headers
  req.accepts('json')     // Content negotiation
  req.is('json')          // Content type check
  
  req.ip           // IP address
  req.protocol     // http or https
  req.secure       // true if https
  req.xhr          // true if AJAX
})
```

#### Response Object
```javascript
// Sending responses
res.send('Hello')
res.json({ user: 'tj' })
res.status(404).send('Not found')
res.sendFile('/path/to/file.pdf')

// Redirects
res.redirect('/')
res.redirect(301, '/')
res.redirect('back')

// Headers
res.set('Content-Type', 'text/html')
res.set({
  'Content-Type': 'text/plain',
  'X-Custom': 'value'
})

// Cookies
res.cookie('name', 'value', { 
  domain: '.example.com',
  secure: true,
  httpOnly: true
})
res.clearCookie('name')
```

### 📁 Bron: Reference cheat sheets copy - express.md

#### Routes
```javascript
// Basic routes
app.get('/', (req, res) => {
  res.send('GET request')
})

app.post('/', (req, res) => {
  res.send('POST request')
})

app.put('/user/:id', (req, res) => {
  res.send('PUT request')
})

app.delete('/user/:id', (req, res) => {
  res.send('DELETE request')
})

// Route patterns
app.get('/ab?cd', handler)     // abcd, acd
app.get('/ab+cd', handler)     // abcd, abbcd, abbbcd, etc
app.get('/ab*cd', handler)     // abcd, abxcd, abRANDOMcd, etc
app.get('/ab(cd)?e', handler)  // abe, abcde

// Route parameters
app.get('/users/:userId/books/:bookId', (req, res) => {
  res.send(req.params) // { userId: '123', bookId: '456' }
})

// Route handlers
app.get('/example', 
  (req, res, next) => {
    console.log('First handler')
    next() // pass control to next handler
  },
  (req, res) => {
    res.send('Second handler')
  }
)
```

### 📁 Bron: Awesome cheatsheets - backend/express.js

#### Express Global Objects
```javascript
// JSON middleware
app.use(express.json({
  inflate: true,              // Handle deflated bodies
  limit: '100kb',            // Max request body size
  reviver: null,             // JSON.parse reviver
  strict: true,              // Only accept arrays/objects
  type: 'application/json',  // MIME type to parse
  verify: undefined          // Verify function
}))

// URL-encoded middleware
app.use(express.urlencoded({
  extended: true,            // Use qs library
  parameterLimit: 1000,      // Max parameters
  inflate: true,             // Handle deflated bodies
  limit: '100kb',           // Max request body size
  type: 'application/x-www-form-urlencoded'
}))

// Static files
app.use(express.static('public', {
  dotfiles: 'ignore',        // How to treat dotfiles
  etag: true,               // Enable etag generation
  extensions: ['htm', 'html'], // File extension fallbacks
  fallthrough: true,         // Let client errors fall through
  index: 'index.html',      // Directory index file
  lastModified: true,       // Set Last-Modified header
  maxAge: '1d',            // Cache-Control max-age
  redirect: true,          // Redirect directories to trailing /
  setHeaders: function(res, path, stat) {
    res.set('x-timestamp', Date.now())
  }
}))

// Router
const router = express.Router({
  caseSensitive: false,    // Case sensitive routes
  mergeParams: false,      // Preserve req.params from parent
  strict: false           // Enable strict routing
})
```

---

## Tar

**Wat is het?** Tar is een archiving utility voor het combineren van files in één archief bestand.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** File archiving, compression, backups, distribution

### 📁 Bron: Root directory - tar.md

#### Basic Operations
```bash
# Create archive (compress)
tar -czf archive.tar.gz /path/to/files

# Extract archive (decompress)
tar -xzf archive.tar.gz

# Extract to specific directory
tar -xzf archive.tar.gz -C /target/directory

# Create uncompressed tar
tar -cf archive.tar /path/to/files

# List contents
tar -tzf archive.tar.gz
tar -tvzf archive.tar.gz  # Verbose listing

# Append to existing archive
tar -rf archive.tar newfile
```

#### Common Options
| Option | Description |
| --- | --- |
| `c` | Create new archive |
| `x` | Extract files from archive |
| `z` | Compress/decompress with gzip |
| `j` | Compress/decompress with bzip2 |
| `v` | Verbose output |
| `f` | Specify filename |
| `t` | List contents |
| `r` | Append files |
| `u` | Update files (newer only) |
| `C` | Change to directory |
| `a` | Auto-detect compression |

#### Examples
```bash
# Different compression formats
tar -czf archive.tar.gz files/    # gzip
tar -cjf archive.tar.bz2 files/   # bzip2
tar -cJf archive.tar.xz files/    # xz

# Exclude files
tar -czf archive.tar.gz --exclude='*.log' --exclude='node_modules' files/

# Create from file list
tar -czf archive.tar.gz -T filelist.txt

# Extract specific files
tar -xzf archive.tar.gz path/to/specific/file

# Show progress
tar -czf archive.tar.gz files/ --checkpoint=.100
```

---

## Promises (Advanced)

**Wat is het?** Promises zijn objecten die de eventual completion of failure van async operations representeren.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Async operations, API calls, file operations, avoiding callback hell

### 📁 Bron: Root directory - promise.md

#### Creating Promises
```javascript
// Basic promise
const promise = new Promise((resolve, reject) => {
  doAsyncOperation((error, result) => {
    if (error) {
      reject(error)
    } else {
      resolve(result)
    }
  })
})

// Immediate resolution/rejection
Promise.resolve('instant success')
Promise.reject(new Error('instant failure'))

// Converting callbacks to promises
function readFilePromise(filename) {
  return new Promise((resolve, reject) => {
    fs.readFile(filename, 'utf8', (err, data) => {
      if (err) reject(err)
      else resolve(data)
    })
  })
}
```

#### Consuming Promises
```javascript
// Basic usage
promise
  .then(result => {
    console.log('Success:', result)
    return processResult(result)
  })
  .then(processed => {
    console.log('Processed:', processed)
  })
  .catch(error => {
    console.error('Error:', error)
  })
  .finally(() => {
    console.log('Cleanup')
  })

// Async/await syntax
async function handlePromise() {
  try {
    const result = await promise
    const processed = await processResult(result)
    console.log('Processed:', processed)
  } catch (error) {
    console.error('Error:', error)
  } finally {
    console.log('Cleanup')
  }
}
```

#### Promise Combinators
```javascript
// Wait for all promises
Promise.all([promise1, promise2, promise3])
  .then(results => {
    // results is array of all results
    console.log(results[0], results[1], results[2])
  })
  .catch(error => {
    // Fails if ANY promise rejects
  })

// Wait for all to settle (success or failure)
Promise.allSettled([promise1, promise2, promise3])
  .then(results => {
    results.forEach(result => {
      if (result.status === 'fulfilled') {
        console.log('Success:', result.value)
      } else {
        console.log('Failed:', result.reason)
      }
    })
  })

// First to resolve wins
Promise.race([promise1, promise2, promise3])
  .then(result => {
    // First resolved value
  })

// First successful promise
Promise.any([promise1, promise2, promise3])
  .then(result => {
    // First successful result
  })
  .catch(error => {
    // All promises rejected
  })
```

---

## React Router (Extended)

**Wat is het?** React Router is de standaard routing library voor React applicaties.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** Client-side routing, navigation, URL management in React apps

### 📁 Bron: Root directory - react-router.md (extended)

#### Advanced Routing
```jsx
import { 
  BrowserRouter,
  Routes,
  Route,
  Link,
  NavLink,
  Navigate,
  useNavigate,
  useParams,
  useLocation,
  useSearchParams
} from 'react-router-dom'

// Routes setup (v6)
<BrowserRouter>
  <Routes>
    <Route path="/" element={<Layout />}>
      <Route index element={<Home />} />
      <Route path="about" element={<About />} />
      <Route path="users">
        <Route index element={<Users />} />
        <Route path=":id" element={<User />} />
        <Route path="new" element={<NewUser />} />
      </Route>
      <Route path="*" element={<NoMatch />} />
    </Route>
  </Routes>
</BrowserRouter>

// Navigation hooks
function NavigationExample() {
  const navigate = useNavigate()
  const location = useLocation()
  const params = useParams()
  const [searchParams, setSearchParams] = useSearchParams()
  
  // Programmatic navigation
  const handleClick = () => {
    navigate('/users')
    navigate('/users', { replace: true })
    navigate(-1) // Go back
    navigate(1)  // Go forward
  }
  
  // Query parameters
  const sort = searchParams.get('sort')
  const filter = searchParams.get('filter')
  
  const updateParams = () => {
    setSearchParams({ sort: 'name', filter: 'active' })
  }
}

// Protected routes
function ProtectedRoute({ children }) {
  const auth = useAuth()
  const location = useLocation()
  
  if (!auth.user) {
    return <Navigate to="/login" state={{ from: location }} replace />
  }
  
  return children
}

// Active link styling
<NavLink 
  to="/about"
  className={({ isActive }) => isActive ? 'active' : ''}
  style={({ isActive }) => ({ color: isActive ? 'red' : 'black' })}
>
  About
</NavLink>
```

---

# 🎨 STYLING & DESIGN

## CSS3 & Modern CSS

**Wat is het?** CSS3 is de nieuwste evolutie van Cascading Style Sheets voor het stylen van web content.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Web styling, layouts, animations, responsive design, themes

### 📁 Bron: Root directory - css.md

#### Selectors
```css
/* Basic selectors */
*               /* All elements */
div             /* Element */
.class          /* Class */
#id             /* ID */
[disabled]      /* Attribute */
[role="dialog"] /* Attribute with value */

/* Combinators */
.parent .child     /* Descendant */
.parent > .child   /* Direct child */
.child + .sibling  /* Adjacent sibling */
.child ~ .sibling  /* General sibling */
.class1.class2     /* Multiple classes */

/* Attribute selectors */
[role="dialog"]    /* Exact match */
[class~="box"]     /* Contains word */
[class|="box"]     /* Exact or prefix */
[href$=".doc"]     /* Ends with */
[href^="/index"]   /* Starts with */
[class*="-is-"]    /* Contains substring */
```

#### Pseudo-classes
```css
/* State */
:hover
:focus
:active
:visited
:disabled
:checked
:empty

/* Position */
:first-child
:last-child
:nth-child(3)
:nth-child(3n+2)
:nth-child(-n+4)
:nth-of-type(2)
:only-child
:only-of-type

/* Form */
:required
:optional
:valid
:invalid
:in-range
:out-of-range
```

#### Typography
```css
/* Font properties */
font-family: Arial, sans-serif;
font-size: 16px;
font-weight: bold;     /* 100-900, normal, bold */
font-style: italic;    /* normal, italic, oblique */
line-height: 1.5;      /* number, length, % */
letter-spacing: 0.1em;
word-spacing: 0.2em;

/* Text properties */
text-align: center;    /* left, right, justify */
text-decoration: none; /* underline, overline, line-through */
text-transform: uppercase; /* lowercase, capitalize */
text-indent: 2em;
text-shadow: 2px 2px 4px rgba(0,0,0,0.5);

/* Font shorthand */
font: italic bold 16px/1.5 Arial, sans-serif;
```

### 📁 Bron: Reference cheat sheets copy - css3.md

#### Flexbox
```css
/* Container */
.flex-container {
  display: flex;           /* or inline-flex */
  flex-direction: row;     /* row-reverse, column, column-reverse */
  flex-wrap: wrap;         /* nowrap, wrap-reverse */
  justify-content: center; /* flex-start, flex-end, space-between, space-around, space-evenly */
  align-items: center;     /* flex-start, flex-end, stretch, baseline */
  align-content: center;   /* flex-start, flex-end, stretch, space-between, space-around */
  gap: 10px;              /* row-gap, column-gap */
}

/* Items */
.flex-item {
  flex: 1 1 auto;         /* grow shrink basis */
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: auto;
  align-self: center;     /* auto, flex-start, flex-end, stretch, baseline */
  order: 0;
}
```

#### Grid
```css
/* Container */
.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  grid-template-columns: repeat(3, 1fr);
  grid-template-columns: 200px auto 200px;
  grid-template-rows: 100px 200px;
  grid-template-areas: 
    "header header header"
    "sidebar main aside"
    "footer footer footer";
  grid-gap: 10px;         /* grid-row-gap, grid-column-gap */
  justify-items: center;  /* start, end, stretch */
  align-items: center;    /* start, end, stretch */
}

/* Items */
.grid-item {
  grid-column: 1 / 3;     /* start / end */
  grid-row: 1 / 2;
  grid-area: header;      /* named area */
  justify-self: center;
  align-self: center;
}
```

#### Animations
```css
/* Keyframes */
@keyframes slide-in {
  from {
    transform: translateX(-100%);
    opacity: 0;
  }
  to {
    transform: translateX(0);
    opacity: 1;
  }
}

/* Animation usage */
.animated {
  animation: slide-in 0.5s ease-out forwards;
  animation-name: slide-in;
  animation-duration: 0.5s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-fill-mode: forwards;
  animation-play-state: running;
}

/* Transitions */
.button {
  transition: all 0.3s ease;
  transition-property: transform, opacity;
  transition-duration: 0.3s;
  transition-timing-function: ease;
  transition-delay: 0s;
}

.button:hover {
  transform: scale(1.1);
  opacity: 0.8;
}
```

### 📁 Bron: Awesome cheatsheets - frontend/css3.css

```css
/* CSS Variables */
:root {
  --primary-color: #3498db;
  --secondary-color: #2ecc71;
  --font-size: 16px;
  --spacing: 1rem;
}

.element {
  color: var(--primary-color);
  font-size: var(--font-size);
  padding: var(--spacing);
  margin: calc(var(--spacing) * 2);
}

/* Media Queries */
@media screen and (min-width: 768px) {
  .container { width: 750px; }
}

@media (orientation: landscape) {
  .sidebar { display: none; }
}

@media (min-width: 768px) and (max-width: 1024px) {
  .content { padding: 20px; }
}

/* Responsive breakpoints */
/* Mobile: 320px - 767px */
/* Tablet: 768px - 1023px */
/* Desktop: 1024px+ */
```

---

## SCSS/Sass

**Wat is het?** Sass is een CSS preprocessor die CSS uitbreidt met variabelen, nesting, mixins en meer.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** Complex stylesheets, theming, component styling, DRY CSS

### 📁 Bron: Root directory - sass.md

#### Variables & Nesting
```scss
// Variables
$primary-color: #333;
$secondary-color: #555;
$base-font-size: 16px;
$spacing: 1rem;

// Nesting
.navigation {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  
  li {
    padding: $spacing/2;
  }
  
  a {
    color: $primary-color;
    
    &:hover {
      color: darken($primary-color, 15%);
    }
    
    &.active {
      font-weight: bold;
    }
  }
}

// Property nesting
.box {
  margin: {
    top: 10px;
    bottom: 15px;
    left: 20px;
    right: 20px;
  }
}
```

#### Mixins
```scss
// Basic mixin
@mixin button-style {
  padding: 10px 15px;
  border-radius: 4px;
  border: none;
  cursor: pointer;
}

// Mixin with parameters
@mixin button($bg-color, $text-color: white) {
  @include button-style;
  background-color: $bg-color;
  color: $text-color;
  
  &:hover {
    background-color: lighten($bg-color, 10%);
  }
}

// Using mixins
.btn-primary {
  @include button(#3498db);
}

.btn-secondary {
  @include button(#95a5a6, #333);
}

// Mixin with content block
@mixin media($breakpoint) {
  @if $breakpoint == tablet {
    @media (min-width: 768px) { @content; }
  } @else if $breakpoint == desktop {
    @media (min-width: 1024px) { @content; }
  }
}

// Usage
.container {
  width: 100%;
  
  @include media(tablet) {
    width: 750px;
  }
  
  @include media(desktop) {
    width: 1200px;
  }
}
```

### 📁 Bron: Reference cheat sheets copy - sass.md

#### Advanced Features
```scss
// Inheritance
%message-shared {
  border: 1px solid #ccc;
  padding: 10px;
  color: #333;
}

.success {
  @extend %message-shared;
  border-color: green;
}

.error {
  @extend %message-shared;
  border-color: red;
}

// Functions
@function calculate-rem($size) {
  $rem-size: $size / 16px;
  @return #{$rem-size}rem;
}

.heading {
  font-size: calculate-rem(32px); // 2rem
}

// Control directives
@for $i from 1 through 6 {
  .col-#{$i} {
    width: 100% / 6 * $i;
  }
}

@each $color, $value in (primary: #3498db, success: #2ecc71, danger: #e74c3c) {
  .btn-#{$color} {
    background-color: $value;
  }
}

// Maps
$breakpoints: (
  small: 480px,
  medium: 768px,
  large: 1024px
);

@each $name, $width in $breakpoints {
  @media (min-width: $width) {
    .hide-#{$name} {
      display: none;
    }
  }
}

// Lists
$margins: 10px, 20px, 30px, 40px;

@each $margin in $margins {
  .margin-#{$margin} {
    margin: $margin;
  }
}
```

---

## Tailwind CSS

**Wat is het?** Tailwind CSS is een utility-first CSS framework voor rapid UI development.  
**Learning curve:** 🟢 Makkelijk  
**Gebruik voor:** Rapid prototyping, consistent design systems, responsive layouts

### 📁 Bron: Awesome cheatsheets - frontend/tailwind.css

#### Layout Utilities
```css
/* Breakpoints */
/* sm: min-width: 640px */
/* md: min-width: 768px */
/* lg: min-width: 1024px */
/* xl: min-width: 1280px */
/* 2xl: min-width: 1536px */

/* Container */
.container             /* Centers and constrains width */

/* Display */
.hidden               /* display: none */
.block                /* display: block */
.inline-block         /* display: inline-block */
.inline               /* display: inline */
.flex                 /* display: flex */
.inline-flex          /* display: inline-flex */
.grid                 /* display: grid */
.inline-grid          /* display: inline-grid */

/* Flexbox */
.flex-row             /* flex-direction: row */
.flex-col             /* flex-direction: column */
.flex-wrap            /* flex-wrap: wrap */
.flex-nowrap          /* flex-wrap: nowrap */
.items-start          /* align-items: flex-start */
.items-center         /* align-items: center */
.items-end            /* align-items: flex-end */
.justify-start        /* justify-content: flex-start */
.justify-center       /* justify-content: center */
.justify-end          /* justify-content: flex-end */
.justify-between      /* justify-content: space-between */
.justify-around       /* justify-content: space-around */
.flex-1               /* flex: 1 1 0% */
.flex-auto            /* flex: 1 1 auto */
.flex-none            /* flex: none */

/* Grid */
.grid-cols-1          /* grid-template-columns: repeat(1, minmax(0, 1fr)) */
.grid-cols-2          /* grid-template-columns: repeat(2, minmax(0, 1fr)) */
.grid-cols-3          /* grid-template-columns: repeat(3, minmax(0, 1fr)) */
.grid-cols-12         /* grid-template-columns: repeat(12, minmax(0, 1fr)) */
.col-span-1           /* grid-column: span 1 / span 1 */
.col-span-2           /* grid-column: span 2 / span 2 */
.gap-0                /* gap: 0 */
.gap-1                /* gap: 0.25rem */
.gap-4                /* gap: 1rem */
.gap-8                /* gap: 2rem */
```

#### Spacing & Sizing
```css
/* Margin */
.m-0                  /* margin: 0 */
.m-1                  /* margin: 0.25rem */
.m-4                  /* margin: 1rem */
.m-8                  /* margin: 2rem */
.m-auto               /* margin: auto */
.mx-4                 /* margin-left: 1rem; margin-right: 1rem */
.my-4                 /* margin-top: 1rem; margin-bottom: 1rem */
.mt-4                 /* margin-top: 1rem */
.mr-4                 /* margin-right: 1rem */
.mb-4                 /* margin-bottom: 1rem */
.ml-4                 /* margin-left: 1rem */
.-m-4                 /* margin: -1rem (negative) */

/* Padding */
.p-0                  /* padding: 0 */
.p-1                  /* padding: 0.25rem */
.p-4                  /* padding: 1rem */
.p-8                  /* padding: 2rem */
.px-4                 /* padding-left: 1rem; padding-right: 1rem */
.py-4                 /* padding-top: 1rem; padding-bottom: 1rem */

/* Width & Height */
.w-full               /* width: 100% */
.w-screen             /* width: 100vw */
.w-1/2                /* width: 50% */
.w-1/3                /* width: 33.333333% */
.w-64                 /* width: 16rem */
.max-w-full           /* max-width: 100% */
.max-w-screen-lg      /* max-width: 1024px */
.min-w-0              /* min-width: 0 */
.h-full               /* height: 100% */
.h-screen             /* height: 100vh */
.h-64                 /* height: 16rem */
```

#### Typography & Colors
```css
/* Font Size */
.text-xs              /* font-size: 0.75rem */
.text-sm              /* font-size: 0.875rem */
.text-base            /* font-size: 1rem */
.text-lg              /* font-size: 1.125rem */
.text-xl              /* font-size: 1.25rem */
.text-2xl             /* font-size: 1.5rem */
.text-3xl             /* font-size: 1.875rem */
.text-4xl             /* font-size: 2.25rem */

/* Font Weight */
.font-thin            /* font-weight: 100 */
.font-light           /* font-weight: 300 */
.font-normal          /* font-weight: 400 */
.font-medium          /* font-weight: 500 */
.font-semibold        /* font-weight: 600 */
.font-bold            /* font-weight: 700 */

/* Text Color */
.text-black           /* color: #000 */
.text-white           /* color: #fff */
.text-gray-500        /* color: #6b7280 */
.text-red-500         /* color: #ef4444 */
.text-blue-500        /* color: #3b82f6 */
.text-green-500       /* color: #10b981 */

/* Background Color */
.bg-transparent       /* background-color: transparent */
.bg-black             /* background-color: #000 */
.bg-white             /* background-color: #fff */
.bg-gray-100          /* background-color: #f3f4f6 */
.bg-blue-500          /* background-color: #3b82f6 */

/* Text Alignment */
.text-left            /* text-align: left */
.text-center          /* text-align: center */
.text-right           /* text-align: right */
.text-justify         /* text-align: justify */
```

#### Responsive Design
```html
<!-- Mobile-first responsive design -->
<div class="w-full md:w-1/2 lg:w-1/3">
  <!-- Full width on mobile, half on medium screens, third on large -->
</div>

<!-- Hide/show at breakpoints -->
<div class="hidden md:block">
  <!-- Hidden on mobile, visible on medium+ screens -->
</div>

<!-- Responsive flexbox -->
<div class="flex flex-col md:flex-row">
  <!-- Column on mobile, row on medium+ screens -->
</div>

<!-- Responsive text -->
<h1 class="text-2xl md:text-4xl lg:text-6xl">
  <!-- Responsive heading sizes -->
</h1>
```

---

## Figma

**Wat is het?** Figma is een collaborative interface design tool voor UI/UX design.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** UI design, prototyping, design systems, collaboration

### 📁 Bron: Reference cheat sheets copy - figma.md

#### Essential Shortcuts
| Shortcut | Action |
| --- | --- |
| `Ctrl` `\` | Show/Hide UI |
| `Ctrl` `C` | Pick Color |
| `Ctrl` `/` | Search Menu |

#### Design Tools
| Shortcut | Action |
| --- | --- |
| `V` | Move Tool |
| `F` | Frame Tool |
| `P` | Pen Tool |
| `Shift` `P` | Pencil Tool |
| `T` | Text Tool |
| `R` | Rectangle Tool |
| `O` | Ellipse Tool |
| `L` | Line Tool |
| `Shift` `L` | Arrow Tool |
| `C` | Add/Show Comments |
| `S` | Slice Tool |

#### View Controls
| Shortcut | Action |
| --- | --- |
| `Shift` `R` | Toggle Rulers |
| `Ctrl` `Y` | Show Outlines |
| `Ctrl` `P` | Pixel Preview |
| `Ctrl` `G` | Layout Grids |
| `Ctrl` `'` | Pixel Grid |
| `Alt` `1` | Show Layers |
| `Alt` `2` | Show Components |
| `Alt` `3` | Show Team Library |

#### Zoom & Navigation
| Shortcut | Action |
| --- | --- |
| `Space` + drag | Pan |
| `+` | Zoom In |
| `-` | Zoom Out |
| `Shift` `0` | Zoom to 100% |
| `Shift` `1` | Zoom to Fit |
| `Shift` `2` | Zoom to Selection |
| `N` | Next Frame |
| `Shift` `N` | Previous Frame |

---

## Adobe Tools

**Wat zijn het?** Adobe Creative Suite bevat professionele design en media editing tools.  
**Learning curve:** 🟡 Gemiddeld tot 🔴 Moeilijk  
**Gebruik voor:** Graphic design, photo editing, UI/UX design, vector graphics, digital art

### 📁 Bron: Reference cheat sheets copy - adobe-*.md

#### Adobe Photoshop - Photo Editing & Digital Art

##### Essential Shortcuts
| Shortcut | Action |
|----------|--------|
| `Ctrl` `T` | Free transform |
| `[` / `]` | Decrease/Increase brush size |
| `Shift` `[` / `]` | Decrease/Increase brush hardness |
| `D` | Default foreground/background colors |
| `X` | Switch foreground/background colors |
| `Ctrl` `J` | New layer via copy |
| `Ctrl` `Shift` `J` | New layer via cut |
| `Ctrl` `F` | Invoke search experience |

##### Function Keys
| Shortcut | Action |
|----------|--------|
| `F1` | Start help |
| `F2` | Cut |
| `F3` | Copy |
| `F4` | Paste |
| `F5` | Show/hide brush panel |
| `F6` | Show/hide color panel |
| `F7` | Show/hide layers panel |
| `F8` | Show/hide info panel |

##### Layer Operations
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Shift` `N` | New layer |
| `Ctrl` `G` | Group layers |
| `Ctrl` `Shift` `G` | Ungroup layers |
| `Ctrl` `E` | Merge down |
| `Ctrl` `Shift` `E` | Merge visible |
| `Alt` `Delete` | Fill with foreground color |
| `Ctrl` `Delete` | Fill with background color |

##### Selection Tools
| Shortcut | Action |
|----------|--------|
| `M` | Marquee tool |
| `L` | Lasso tool |
| `W` | Magic wand tool |
| `Ctrl` `A` | Select all |
| `Ctrl` `D` | Deselect |
| `Ctrl` `Shift` `I` | Inverse selection |
| `Ctrl` `Alt` `R` | Refine edge |

#### Adobe XD - UI/UX Design

##### File Operations
| Shortcut | Action |
|----------|--------|
| `Ctrl` `N` | New |
| `Ctrl` `Shift` `O` | Open... |
| `Ctrl` `S` | Save... |
| `Ctrl` `Shift` `S` | Save As... |
| `Ctrl` `Shift` `E` | Export Batch |
| `Ctrl` `E` | Export Selected |
| `Ctrl` `Shift` `I` | Import |
| `Alt` `F4` | Close |

##### Edit Operations
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Z` | Undo |
| `Ctrl` `Shift` `Z` | Redo |
| `Ctrl` `X` | Cut |
| `Ctrl` `C` | Copy |
| `Ctrl` `V` | Paste |
| `Ctrl` `Alt` `V` | Paste Appearance/Interaction |
| `Ctrl` `D` | Duplicate |
| `Del` | Delete |
| `Ctrl` `A` | Select All |
| `Ctrl` `Shift` `A` | Deselect All |

##### Design Tools
| Shortcut | Action |
|----------|--------|
| `R` | Rectangle tool |
| `E` | Ellipse tool |
| `L` | Line tool |
| `P` | Pen tool |
| `T` | Text tool |
| `A` | Artboard tool |
| `V` | Select tool |
| `Ctrl` `G` | Group |
| `Ctrl` `Shift` `G` | Ungroup |

##### View & Navigation
| Shortcut | Action |
|----------|--------|
| `Ctrl` `+` | Zoom in |
| `Ctrl` `-` | Zoom out |
| `Ctrl` `0` | Zoom to fit |
| `Ctrl` `1` | Zoom to 100% |
| `Space` + `Drag` | Pan |
| `Ctrl` `R` | Toggle rulers |
| `Ctrl` `;` | Toggle guides |

---

## GIMP - GNU Image Manipulation Program

**Wat is het?** GIMP is een gratis, open-source alternatief voor Photoshop.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Photo editing, graphic design, digital art, image manipulation

### 📁 Bron: Reference cheat sheets copy - gimp.md

#### Toolbox Selection
| Shortcut | Action |
|----------|--------|
| `R` | Rectangle select |
| `E` | Ellipse select |
| `F` | Free select |
| `U` | Fuzzy select |
| `Shift` `O` | Select by color |
| `I` | Scissors |
| `B` | Paths |
| `O` | Color picker |
| `M` | Move |

#### Transform Tools
| Shortcut | Action |
|----------|--------|
| `Shift` `C` | Crop and resize |
| `Shift` `R` | Rotate |
| `Shift` `T` | Scale |
| `Shift` `S` | Shear |
| `Shift` `P` | Perspective |
| `Shift` `F` | Flip |

#### Paint Tools
| Shortcut | Action |
|----------|--------|
| `N` | Pencil |
| `P` | Paintbrush |
| `Shift` `E` | Eraser |
| `A` | Airbrush |
| `K` | Ink |
| `C` | Clone |
| `V` | Convolve |
| `S` | Smudge |
| `Shift` `D` | Dodge or burn |
| `Shift` `B` | Bucket fill |
| `L` | Blend |

#### Color & General
| Shortcut | Action |
|----------|--------|
| `X` | Swap colors |
| `D` | Default colors |
| `T` | Text tool |
| `Tab` | Toggle toolbox visibility |
| `Ctrl` `Z` | Undo |
| `Ctrl` `Y` | Redo |
| `Ctrl` `A` | Select all |
| `Ctrl` `Shift` `A` | Select none |

---

## 📐 **Sketch/SketchUp - Design Tools**

**Wat zijn het?** Sketch is een vector design tool voor macOS, SketchUp is een 3D modeling tool.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** UI/UX design (Sketch), 3D modeling en architectuur (SketchUp)

### 📁 Bron: Reference cheat sheets copy - sketch.md, sketchup.md

#### Sketch - Digital Design (macOS only)

##### General Operations
| Shortcut | Action |
|----------|--------|
| `Cmd` `C` | Copy |
| `Cmd` `X` | Cut |
| `Cmd` `V` | Paste |
| `Cmd` `Shift` `V` | Paste over selection |
| `Space` + `Drag` | Pan Canvas |
| `Cmd` `Z` | Undo |
| `Cmd` `Shift` `Z` | Redo |

##### File Operations
| Shortcut | Action |
|----------|--------|
| `Cmd` `N` | New document |
| `Cmd` `Shift` `N` | New Cloud document |
| `Cmd` `O` | Open document |
| `Cmd` `W` | Close window |
| `Cmd` `S` | Save document |
| `Cmd` `Shift` `S` | Duplicate document |

##### View Controls
| Shortcut | Action |
|----------|--------|
| `Cmd` `+` | Zoom in |
| `Cmd` `-` | Zoom out |
| `Cmd` `0` | Zoom to fit |
| `Cmd` `1` | Zoom to 100% |
| `Ctrl` `R` | Toggle rulers |
| `Ctrl` `G` | Toggle grid |
| `Ctrl` `L` | Toggle layout |
| `Ctrl` `E` | Toggle slices |

##### Drawing Tools
| Shortcut | Action |
|----------|--------|
| `R` | Rectangle |
| `O` | Oval |
| `L` | Line |
| `V` | Vector |
| `P` | Pencil |
| `T` | Text |
| `A` | Artboard |
| `S` | Slice |

##### Layer Operations
| Shortcut | Action |
|----------|--------|
| `Cmd` `G` | Group layers |
| `Cmd` `Shift` `G` | Ungroup layers |
| `Cmd` `R` | Rename layer |
| `Cmd` `Opt` `Up` | Move layer up |
| `Cmd` `Opt` `Down` | Move layer down |
| `Cmd` `Shift` `L` | Lock/unlock layer |
| `Cmd` `Shift` `H` | Show/hide layer |

#### SketchUp - 3D Modeling

##### Basic Tools
| Tool | Description |
|------|-------------|
| **Select** | Select and move objects |
| **Line** | Draw straight lines |
| **Rectangle** | Draw rectangles |
| **Circle** | Draw circles |
| **Arc** | Draw arcs |
| **Polygon** | Draw multi-sided shapes |

##### 3D Operations
| Tool | Description |
|------|-------------|
| **Push/Pull** | Extrude faces into 3D |
| **Move** | Move objects in 3D space |
| **Rotate** | Rotate objects |
| **Scale** | Resize objects |
| **Follow Me** | Extrude along a path |
| **Offset** | Create parallel edges |

##### Navigation
| Control | Action |
|---------|--------|
| **Orbit** | Rotate view around model |
| **Pan** | Move view left/right/up/down |
| **Zoom** | Zoom in and out |
| **Zoom Extents** | Fit model in view |
| **Walk** | Navigate at eye level |

##### Common Shortcuts
| Shortcut | Action |
|----------|--------|
| `Ctrl` `Z` | Undo |
| `Ctrl` `Y` | Redo |
| `Ctrl` `A` | Select all |
| `Ctrl` `C` | Copy |
| `Ctrl` `V` | Paste |
| `Delete` | Delete selected |
| `G` | Make group |
| `Ctrl` `G` | Make component |

---

# 🎯 CANVAS & VISUALIZATION

## HTML5 Canvas API

**Wat is het?** Canvas API biedt een manier om 2D graphics te tekenen via JavaScript en HTML.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Games, data visualization, image manipulation, animations, drawing apps

### 📁 Bron: Root directory - canvas.md

#### Getting Started
```javascript
// Get canvas and context
var canvas = document.getElementById('myCanvas')
var ctx = canvas.getContext('2d')

// Set canvas size
canvas.width = 800
canvas.height = 600
```

#### Basic Drawing
```javascript
// Colors and styles
ctx.fillStyle = '#ff0000'     // Fill color
ctx.strokeStyle = '#0000ff'   // Stroke color
ctx.lineWidth = 5             // Line width
ctx.lineCap = 'round'         // Line cap style: butt, round, square
ctx.lineJoin = 'round'        // Line join style: round, bevel, miter

// Rectangle
ctx.fillRect(10, 20, 200, 100)    // Filled rectangle
ctx.strokeRect(10, 20, 200, 100)  // Outlined rectangle
ctx.clearRect(10, 20, 200, 100)   // Clear area

// Apply styles
ctx.fill()    // Fill current path
ctx.stroke()  // Stroke current path
```

#### Paths
```javascript
// Begin new path
ctx.beginPath()

// Move to position
ctx.moveTo(50, 50)

// Draw lines
ctx.lineTo(200, 50)
ctx.lineTo(200, 200)

// Close path
ctx.closePath()

// Apply stroke
ctx.stroke()
```

#### Transformations
```javascript
// Save/restore state
ctx.save()    // Save current state
ctx.restore() // Restore saved state

// Basic transformations
ctx.translate(100, 100)  // Move origin
ctx.rotate(Math.PI / 4)  // Rotate 45 degrees
ctx.scale(2, 2)          // Scale 2x

// Rotate around point
function rotateAroundPoint(x, y, angle) {
  ctx.translate(x, y)
  ctx.rotate(angle)
  ctx.translate(-x, -y)
}

// Scale from point
function scaleFromPoint(x, y, scaleX, scaleY) {
  ctx.translate(x, y)
  ctx.scale(scaleX, scaleY)
  ctx.translate(-x / scaleX, -y / scaleY)
}
```

### 📁 Bron: Reference cheat sheets copy - canvas.md

#### Drawing Shapes
```javascript
// Circles and arcs
ctx.beginPath()
ctx.arc(x, y, radius, startAngle, endAngle, anticlockwise)
ctx.arc(150, 150, 75, 0, 2 * Math.PI)  // Full circle
ctx.fill()

// Partial arc
ctx.beginPath()
ctx.arc(200, 200, 50, 0, Math.PI, false)  // Half circle
ctx.stroke()

// Bezier curves
ctx.beginPath()
ctx.moveTo(20, 20)
ctx.quadraticCurveTo(20, 100, 200, 20)  // Quadratic curve
ctx.stroke()

ctx.beginPath()
ctx.moveTo(20, 20)
ctx.bezierCurveTo(20, 100, 200, 100, 200, 20)  // Cubic curve
ctx.stroke()
```

#### Text
```javascript
// Font styling
ctx.font = '48px Arial'
ctx.textAlign = 'center'      // left, right, center, start, end
ctx.textBaseline = 'middle'   // top, hanging, middle, alphabetic, ideographic, bottom

// Draw text
ctx.fillText('Hello World', x, y, maxWidth)
ctx.strokeText('Hello World', x, y, maxWidth)

// Measure text
const metrics = ctx.measureText('Hello World')
console.log(metrics.width)
```

#### Images
```javascript
// Draw image
const img = new Image()
img.onload = function() {
  // Draw full image
  ctx.drawImage(img, x, y)
  
  // Draw scaled image
  ctx.drawImage(img, x, y, width, height)
  
  // Draw part of image
  ctx.drawImage(img, 
    sx, sy, sWidth, sHeight,  // Source rectangle
    dx, dy, dWidth, dHeight   // Destination rectangle
  )
}
img.src = 'image.png'
```

#### Gradients & Patterns
```javascript
// Linear gradient
const gradient = ctx.createLinearGradient(x0, y0, x1, y1)
gradient.addColorStop(0, 'red')
gradient.addColorStop(0.5, 'yellow')
gradient.addColorStop(1, 'green')
ctx.fillStyle = gradient

// Radial gradient
const radialGradient = ctx.createRadialGradient(x0, y0, r0, x1, y1, r1)
radialGradient.addColorStop(0, 'red')
radialGradient.addColorStop(1, 'blue')
ctx.fillStyle = radialGradient

// Pattern
const pattern = ctx.createPattern(image, 'repeat')  // repeat, repeat-x, repeat-y, no-repeat
ctx.fillStyle = pattern
```

#### Animation
```javascript
// Basic animation loop
function animate() {
  // Clear canvas
  ctx.clearRect(0, 0, canvas.width, canvas.height)
  
  // Update positions
  x += velocityX
  y += velocityY
  
  // Draw
  ctx.fillRect(x, y, 50, 50)
  
  // Continue animation
  requestAnimationFrame(animate)
}

// Start animation
requestAnimationFrame(animate)
```

---

## SVG Graphics

**Wat is het?** SVG (Scalable Vector Graphics) is een XML-based vector image format voor 2D graphics.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Scalable icons, illustrations, logos, simple animations

### Basic SVG Elements
```html
<!-- SVG Container -->
<svg width="200" height="200" viewBox="0 0 200 200">
  
  <!-- Basic shapes -->
  <rect x="10" y="10" width="100" height="50" fill="red" stroke="black" stroke-width="2"/>
  <circle cx="50" cy="100" r="30" fill="blue"/>
  <ellipse cx="100" cy="50" rx="40" ry="20" fill="green"/>
  <line x1="0" y1="0" x2="100" y2="100" stroke="black" stroke-width="2"/>
  
  <!-- Path -->
  <path d="M 10 10 L 100 10 L 100 100 Z" fill="yellow"/>
  
  <!-- Text -->
  <text x="50" y="150" font-family="Arial" font-size="16" fill="black">Hello SVG</text>
  
  <!-- Group -->
  <g transform="translate(50,50)">
    <circle r="20" fill="orange"/>
    <text y="5" text-anchor="middle">Group</text>
  </g>
</svg>
```

### SVG Styling
```css
/* CSS styling */
.svg-icon {
  width: 24px;
  height: 24px;
  fill: currentColor;
}

.svg-icon:hover {
  fill: #3498db;
  transform: scale(1.1);
  transition: all 0.3s ease;
}

/* SVG animations */
.rotating {
  animation: rotate 2s linear infinite;
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
```

---

## Framer Motion

**Wat is het?** Framer Motion is een React animation library voor complexe animaties en interactions.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** React animations, micro-interactions, page transitions, gesture handling

### 📁 Bron: Reference cheat sheets copy - framer-x.md

#### Framer X Shortcuts
| Shortcut | Action |
| --- | --- |
| `F` | Frame |
| `U` | Round |
| `T` | Text |
| `S` | Stack |
| `L` | Link |
| `Space` | Pan Canvas |

#### Graphics Tools
| Shortcut | Action |
| --- | --- |
| `G` | Graphic |
| `P` | Path |
| `R` | Rectangle |
| `O` | Oval |
| `V` | Vector |
| `Cmd` `G` | Group |
| `Cmd` `Shift` `G` | Ungroup |

#### Layout Controls
| Shortcut | Action |
| --- | --- |
| `Cmd` `Enter` | Add Frame |
| `Cmd` `Opt` `Enter` | Add Stack |
| `Cmd` `Del` | Remove Wrapper |
| `Cmd` `Opt` `Up` | Move Forward |
| `Cmd` `Opt` `Down` | Move Backward |

### Framer Motion Code Examples
```jsx
import { motion, AnimatePresence } from 'framer-motion'

// Basic animation
<motion.div
  initial={{ opacity: 0, y: -50 }}
  animate={{ opacity: 1, y: 0 }}
  exit={{ opacity: 0, y: 50 }}
  transition={{ duration: 0.5 }}
>
  Content
</motion.div>

// Hover and tap animations
<motion.button
  whileHover={{ scale: 1.1 }}
  whileTap={{ scale: 0.9 }}
  transition={{ type: "spring", stiffness: 400, damping: 17 }}
>
  Click me
</motion.button>

// List animations
<AnimatePresence>
  {items.map(item => (
    <motion.div
      key={item.id}
      layout
      initial={{ opacity: 0 }}
      animate={{ opacity: 1 }}
      exit={{ opacity: 0 }}
    >
      {item.content}
    </motion.div>
  ))}
</AnimatePresence>

// Gesture handling
<motion.div
  drag
  dragConstraints={{ left: -100, right: 100, top: -100, bottom: 100 }}
  whileDrag={{ scale: 1.2 }}
>
  Draggable
</motion.div>
```

---

# 🗄️ BACKEND & DATABASE

## PostgreSQL

**Wat is het?** PostgreSQL is een krachtige, open source object-relational database system.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Complex queries, JSON data, full-text search, geospatial data

### 📁 Bron: Root directory - postgresql.md

#### Console Access
```bash
# Connect to database
psql                              # Default database and user
sudo -u postgres psql             # Connect as postgres user
psql -h localhost -U username -d dbname  # Specific connection

# Connection string
psql postgresql://user:password@localhost:5432/dbname
```

#### Basic Commands
```sql
-- Show information
\du                    -- Show roles/users
\l                     -- Show databases
\dt                    -- Show tables
\d table_name          -- Describe table
\d+ table_name         -- Detailed table info
\c database_name       -- Connect to database
\q                     -- Quit

-- Database operations
CREATE DATABASE mydb;
DROP DATABASE mydb;
```

#### Data Types
```sql
-- Numeric types
INTEGER, BIGINT, DECIMAL, NUMERIC, REAL, DOUBLE PRECISION

-- Character types
CHAR(n), VARCHAR(n), TEXT

-- Date/Time types
DATE, TIME, TIMESTAMP, TIMESTAMPTZ, INTERVAL

-- Boolean
BOOLEAN

-- JSON types
JSON, JSONB

-- Arrays
INTEGER[], TEXT[], VARCHAR(50)[]

-- UUID
UUID

-- Example table
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    email VARCHAR(255) UNIQUE NOT NULL,
    name TEXT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    metadata JSONB,
    tags TEXT[]
);
```

#### PostgreSQL Commando's

**Verbinden en Navigeren:**
```bash
# Verbind als postgres gebruiker
sudo -u postgres psql

# Verbind met specifieke database
psql -d mydb -U username -h localhost -p 5432

# Lijst alle databases
\l

# Verbind met database
\c database_name

# Toon huidige database
SELECT current_database();

# Disconnect
\q
```

**Database Beheer:**
```sql
-- Maak database
CREATE DATABASE myapp WITH OWNER developer;

-- Verwijder database
DROP DATABASE IF EXISTS oldapp;

-- Hernoem database
ALTER DATABASE oldname RENAME TO newname;

-- Backup database
pg_dump -d mydb -f backup.sql

-- Restore database
psql -U user mydb < backup.sql
```

**Tabel Operaties:**
```sql
-- Lijst tabellen
\dt
SELECT table_name FROM information_schema.tables 
WHERE table_schema = 'public';

-- Beschrijf tabel structuur
\d+ table_name

-- Voeg kolom toe
ALTER TABLE users ADD COLUMN age INTEGER;

-- Wijzig kolom type
ALTER TABLE users ALTER COLUMN email TYPE VARCHAR(300);

-- Verwijder kolom
ALTER TABLE users DROP COLUMN age;

-- Verwijder tabel
DROP TABLE IF EXISTS old_table CASCADE;
```

**Data Queries:**
```sql
-- Selecteer data met filtering
SELECT * FROM users WHERE age > 18 AND email LIKE '%@gmail.com';

-- Voeg data toe
INSERT INTO users (name, email, age) 
VALUES ('Jan Jansen', 'jan@email.com', 25);

-- Update data
UPDATE users 
SET age = 26, last_login = NOW() 
WHERE email = 'jan@email.com';

-- Verwijder data
DELETE FROM users WHERE age < 18;

-- Count en aggregatie
SELECT COUNT(*), AVG(age), MAX(created_at) FROM users;
```

**Gebruikers en Permissies:**
```sql
-- Maak gebruiker
CREATE USER developer WITH PASSWORD 'secure123';

-- Geef database permissies
GRANT ALL PRIVILEGES ON DATABASE myapp TO developer;

-- Geef tabel permissies
GRANT SELECT, INSERT, UPDATE ON users TO developer;

-- Lijst gebruikers
SELECT rolname FROM pg_roles;

-- Wijzig wachtwoord
ALTER ROLE developer WITH PASSWORD 'newsecure456';
```

**Datum en Tijd Functies:**
```sql
-- Huidige datum en tijd
SELECT NOW(), CURRENT_DATE, CURRENT_TIME;

-- Datum berekeningen
SELECT age(NOW(), created_at) FROM users;

-- Datum formatting
SELECT to_char(created_at, 'YYYY-MM-DD HH24:MI:SS') FROM users;

-- Maak datum van integers
SELECT make_date(2024, 1, 15);
```

**PostgreSQL Specifieke Features:**
```sql
-- JSON data types
SELECT data->>'name' FROM users WHERE data @> '{"active": true}';

-- Array operations
SELECT * FROM posts WHERE tags @> ARRAY['postgresql'];

-- Full-text search
SELECT * FROM articles WHERE to_tsvector(content) @@ to_tsquery('database');

-- Window functions
SELECT name, age, 
       ROW_NUMBER() OVER (ORDER BY age DESC) as rank
FROM users;

-- Common Table Expressions (CTE)
WITH young_users AS (
    SELECT * FROM users WHERE age < 25
)
SELECT COUNT(*) FROM young_users;
```

#### SQL Joins en Queries

**JOIN Types:**
```sql
-- INNER JOIN - alleen records met match in beide tabellen
SELECT u.name, p.title 
FROM users u 
INNER JOIN posts p ON u.id = p.user_id;

-- LEFT JOIN - alle records uit linker tabel
SELECT u.name, p.title 
FROM users u 
LEFT JOIN posts p ON u.id = p.user_id;

-- RIGHT JOIN - alle records uit rechter tabel  
SELECT u.name, p.title 
FROM users u 
RIGHT JOIN posts p ON u.id = p.user_id;

-- FULL OUTER JOIN - alle records uit beide tabellen
SELECT u.name, p.title 
FROM users u 
FULL OUTER JOIN posts p ON u.id = p.user_id;
```

**Complexe Queries:**
```sql
-- Subqueries
SELECT name FROM users 
WHERE id IN (SELECT user_id FROM posts WHERE created_at > '2024-01-01');

-- EXISTS clause
SELECT * FROM users u 
WHERE EXISTS (SELECT 1 FROM posts p WHERE p.user_id = u.id);

-- CASE statements
SELECT name,
       CASE 
           WHEN age < 18 THEN 'Minor'
           WHEN age < 65 THEN 'Adult'
           ELSE 'Senior'
       END as age_group
FROM users;

-- GROUP BY en HAVING
SELECT category, COUNT(*), AVG(price) 
FROM products 
GROUP BY category 
HAVING COUNT(*) > 5;
```

**Performance en Indexing:**
```sql
-- Maak index voor betere performance
CREATE INDEX idx_users_email ON users(email);
CREATE INDEX idx_posts_user_created ON posts(user_id, created_at);

-- Unique index
CREATE UNIQUE INDEX idx_users_username ON users(username);

-- Partial index
CREATE INDEX idx_active_users ON users(email) WHERE active = true;

-- Verwijder index
DROP INDEX IF EXISTS idx_old_index;

-- Analyse query performance
EXPLAIN ANALYZE SELECT * FROM users WHERE email = 'test@example.com';
```

---

## SQL Queries

**Wat is het?** SQL (Structured Query Language) is de standaardtaal voor relationale databases.  
**Learning curve:** 🟡 Gemiddeld  
**Gebruik voor:** Database queries, data manipulation, reporting, data analysis

### 📁 Bron: Root directory - mysql.md, sql-join.md

#### Basic Syntax

##### Database Operations
```sql
-- Show databases and tables
SHOW DATABASES;
SHOW TABLES;
SHOW FIELDS FROM table;
DESCRIBE table;
SHOW CREATE TABLE table;

-- Use specific database
USE database_name;
```

##### Basic SELECT Queries
```sql
-- Simple select
SELECT * FROM table;
SELECT column1, column2 FROM table;
SELECT DISTINCT column1 FROM table;

-- With conditions
SELECT * FROM table WHERE condition;
SELECT * FROM table WHERE column = 'value';
SELECT * FROM table WHERE column IN ('value1', 'value2');
SELECT * FROM table WHERE column IS NULL;
SELECT * FROM table WHERE column IS NOT NULL;
SELECT * FROM table WHERE column LIKE 'pattern%';
```

##### Sorting and Limiting
```sql
-- Order by
SELECT * FROM table ORDER BY column1;
SELECT * FROM table ORDER BY column1 DESC;
SELECT * FROM table ORDER BY column1, column2 DESC;

-- Limit results
SELECT * FROM table LIMIT 10;
SELECT * FROM table LIMIT 10 OFFSET 20;
```

##### Grouping and Aggregation
```sql
-- Group by
SELECT column1, COUNT(*) FROM table GROUP BY column1;
SELECT column1, SUM(column2) FROM table GROUP BY column1;
SELECT column1, AVG(column2) FROM table GROUP BY column1 HAVING AVG(column2) > 100;

-- Aggregate functions
SELECT COUNT(*) FROM table;
SELECT SUM(column) FROM table;
SELECT AVG(column) FROM table;
SELECT MIN(column) FROM table;
SELECT MAX(column) FROM table;
```

#### SQL Joins

##### Join Types Overview
| Join Type | Description | Venn Diagram |
|-----------|-------------|--------------|
| INNER JOIN | Only matching records | `A ∩ B` |
| LEFT JOIN | All from left + matching | `A + ∩` |
| RIGHT JOIN | Matching + all from right | `∩ + B` |
| FULL OUTER JOIN | All records from both | `A + ∩ + B` |

##### Join Syntax
```sql
-- Inner join
SELECT * FROM table1 
INNER JOIN table2 ON table1.id = table2.foreign_id;

-- Left outer join
SELECT * FROM order_items 
LEFT OUTER JOIN orders ON order_items.order_id = orders.id;

-- Right outer join
SELECT * FROM customers 
RIGHT JOIN orders ON customers.id = orders.customer_id;

-- Full outer join
SELECT * FROM table1 
FULL OUTER JOIN table2 ON table1.id = table2.foreign_id;

-- Multiple joins
SELECT * FROM table1 
JOIN table2 ON table1.id = table2.id
JOIN table3 ON table2.id = table3.id;
```

#### Data Modification

##### INSERT Operations
```sql
-- Insert single row
INSERT INTO table (column1, column2) VALUES ('value1', 'value2');

-- Insert multiple rows
INSERT INTO table (column1, column2) VALUES 
  ('value1', 'value2'),
  ('value3', 'value4');

-- Insert from select
INSERT INTO table1 (column1, column2) 
SELECT column1, column2 FROM table2 WHERE condition;
```

##### UPDATE Operations
```sql
-- Update records
UPDATE table SET column1 = 'new_value' WHERE condition;
UPDATE table SET column1 = 'value1', column2 = 'value2' WHERE id = 1;

-- Update with join
UPDATE table1 SET column1 = 'value' 
FROM table2 WHERE table1.id = table2.foreign_id;
```

##### DELETE Operations
```sql
-- Delete records
DELETE FROM table WHERE condition;
DELETE FROM table WHERE column IS NULL;

-- Delete with join
DELETE table1 FROM table1 
JOIN table2 ON table1.id = table2.foreign_id 
WHERE table2.status = 'inactive';
```

#### Advanced Queries

##### Subqueries
```sql
-- Subquery in WHERE
SELECT * FROM table1 
WHERE column1 IN (SELECT column1 FROM table2 WHERE condition);

-- Subquery in SELECT
SELECT column1, (SELECT COUNT(*) FROM table2 WHERE table2.foreign_id = table1.id) as count
FROM table1;

-- EXISTS subquery
SELECT * FROM table1 
WHERE EXISTS (SELECT 1 FROM table2 WHERE table2.foreign_id = table1.id);
```

##### Window Functions
```sql
-- Row number
SELECT *, ROW_NUMBER() OVER (ORDER BY column1) as row_num FROM table;

-- Rank
SELECT *, RANK() OVER (PARTITION BY category ORDER BY score DESC) as rank FROM table;

-- Running totals
SELECT *, SUM(amount) OVER (ORDER BY date) as running_total FROM table;
```

##### Common Conditions
```sql
-- Comparison operators
column = value
column <> value
column != value
column < value
column > value
column <= value
column >= value

-- String operations
column LIKE 'pattern%'    -- Starts with pattern
column LIKE '%pattern'    -- Ends with pattern
column LIKE '%pattern%'   -- Contains pattern
column LIKE 'patter_'     -- Single character wildcard

-- Null checks
column IS NULL
column IS NOT NULL

-- Range checks
column BETWEEN value1 AND value2
column IN (value1, value2, value3)
column NOT IN (value1, value2)
```

##### Date Functions
```sql
-- Current date/time
SELECT NOW();
SELECT CURRENT_DATE;
SELECT CURRENT_TIME;

-- Date formatting
SELECT DATE_FORMAT(date_column, '%Y-%m-%d');
SELECT YEAR(date_column);
SELECT MONTH(date_column);
SELECT DAY(date_column);

-- Date arithmetic
SELECT DATE_ADD(date_column, INTERVAL 1 DAY);
SELECT DATE_SUB(date_column, INTERVAL 1 MONTH);
SELECT DATEDIFF(date1, date2);
```

---

## 🔧 **Heroku - Cloud Platform Deployment**

*Heroku is een cloud application platform voor het deployen, schalen en beheren van web applicaties. Ondersteunt meerdere programmeertalen en biedt een eenvoudige deployment workflow via Git.*

**Leercurve:** 🟢 **Makkelijk** - Intuïtieve CLI interface en deployment proces
**Gebruik:** Platform-as-a-Service voor applicatie hosting, database services, add-ons

#### Heroku CLI Installatie

**Installatie per OS:**
```bash
# macOS
brew tap heroku/brew && brew install heroku

# Ubuntu/Debian
sudo snap install --classic heroku
curl https://cli-assets.heroku.com/install-ubuntu.sh | sh

# Arch Linux
yay -S heroku-cli

# NPM (cross-platform)
npm install -g heroku

# Verificatie installatie
heroku --version
```

#### App Management

**Basis App Operaties:**
```bash
# Inloggen
heroku login
heroku login -i  # CLI interface zonder browser

# App maken
heroku create myapp
heroku create  # automatische naam

# App informatie
heroku apps                    # lijst alle apps
heroku apps:info              # app details
heroku apps:open             # open in browser
heroku apps:rename newname   # hernoemen
heroku apps:destroy --app myapp  # verwijderen

# App transfer
heroku apps:transfer new@owner.com
```

**Collaboratie:**
```bash
# Collaborators beheren
heroku access                    # lijst collaborators
heroku access:add dev@company.com
heroku access:remove dev@company.com
```

#### Deployment Workflows

**Git-based Deployment:**
```bash
# Project setup
cd myproject
git init
git add .
git commit -m "Initial commit"

# Heroku remote toevoegen
heroku create myapp
git remote -v  # verificeer remote

# Voor bestaande app
heroku git:remote -a existing-app
git remote rename heroku heroku-staging

# Deployen
git push heroku main
git push heroku main --force      # force push
git push heroku develop:main      # van branch naar main
```

**Container Deployment:**
```bash
# Container stack instellen
heroku stack:set container -a myapp

# Docker workflow
heroku container:login
heroku container:push web -a myapp
heroku container:push --recursive     # recursive build
heroku container:release web -a myapp

# Meerdere processes
heroku container:push web worker --recursive
```

#### Environment Configuration

**Config Variables:**
```bash
# Environment variables
heroku config                      # lijst alle vars
heroku config -s                  # shell format
heroku config:get DATABASE_URL    # specifieke var

# Variabelen instellen
heroku config:set NODE_ENV=production
heroku config:set API_KEY=abc123 SECRET=xyz789
heroku config:unset OLD_VAR       # verwijderen
```

**Release Management:**
```bash
# Releases beheren
heroku releases                   # lijst releases
heroku releases:info v25         # release details
heroku rollback                  # rollback naar vorige
heroku rollback v23              # rollback naar specifieke
```

#### Database & Add-ons

**PostgreSQL Database:**
```bash
# Database toevoegen
heroku addons:create heroku-postgresql:hobby-dev
heroku addons:create heroku-postgresql:standard-0

# Database info
heroku pg:info
heroku pg:credentials:url DATABASE

# Backup configuratie
heroku addons:create pgbackups:auto-month
heroku pg:backups              # lijst backups
heroku pg:backups:capture      # handmatige backup
heroku pg:backups:restore      # restore backup
```

**Add-ons Management:**
```bash
# Add-ons beheren
heroku addons                     # lijst geïnstalleerde add-ons
heroku addons:create redis:hobby-dev
heroku addons:upgrade redis:premium-0
heroku addons:destroy redis       # verwijderen
```

#### Process Management

**Dyno Management:**
```bash
# Process status
heroku ps                        # lijst alle processes
heroku ps:scale web=2           # schaal web dynos
heroku ps:scale worker=1        # schaal worker dynos
heroku ps:stop web.1            # stop specifieke dyno

# Process restart
heroku restart                   # restart alle dynos
heroku restart web              # restart web dynos
```

**Running Commands:**
```bash
# One-off commands
heroku run bash                 # interactieve shell
heroku run node -v             # Node.js versie check
heroku run npm run migrate     # database migratie
heroku run rails console       # Rails console
heroku run python manage.py shell  # Django shell

# Scheduled tasks
heroku run:detached rake maintenance_task
```

#### Logging & Monitoring

**Log Management:**
```bash
# Logs bekijken
heroku logs                     # recente logs
heroku logs --tail             # live log stream
heroku logs --source app       # alleen app logs
heroku logs --ps web.1         # specifieke dyno
heroku logs --num 500          # meer log regels

# Log drains (voor externe services)
heroku drains:add https://logs.example.com
```

#### Domain & SSL

**Custom Domains:**
```bash
# Domain beheer
heroku domains                  # lijst domains
heroku domains:add example.com
heroku domains:add www.example.com
heroku domains:remove example.com
heroku domains:clear           # verwijder alle

# SSL certificaten
heroku certs                   # lijst certificaten
heroku certs:auto:enable       # automatische SSL
heroku certs:add cert.pem key.pem  # custom certificaat
```

#### Maintenance & Monitoring

**Maintenance Mode:**
```bash
# Maintenance page
heroku maintenance:on          # enable maintenance page
heroku maintenance:off         # disable maintenance page
heroku maintenance            # check status
```

**App Metrics:**
```bash
# Performance metrics
heroku ps:autoscale:enable    # enable autoscaling
heroku metrics               # app metrics
heroku status               # Heroku platform status
```

#### Heroku Procfile

**Process Types Definitie:**
```bash
# Procfile (in project root)
web: npm start
worker: node worker.js
scheduler: node scheduler.js
release: npm run migrate

# Voor verschillende environments
web: NODE_ENV=production npm start
```

#### Troubleshooting

**Debug Commands:**
```bash
# App informatie
heroku info
heroku config
heroku ps
heroku releases

# Connectivity test
heroku logs --tail
heroku run bash
heroku run env  # environment variables

# Reset app
heroku apps:destroy --app myapp
heroku create myapp
git push heroku main
```

**Performance Optimization:**
```bash
# Dyno metrics
heroku logs --ps router        # router logs
heroku metrics:mem            # memory usage
heroku metrics:cpu            # CPU usage

# Database performance
heroku pg:diagnose            # database health
heroku pg:outliers           # slow queries
heroku pg:stats              # connection stats
```

---

## 🌐 **Nginx - Web Server & Reverse Proxy**

*Nginx is een high-performance web server, reverse proxy en load balancer. Bekend om zijn efficiëntie, stabiliteit en lage resource verbruik.*

**Leercurve:** 🟡 **Gemiddeld** - Configuratie syntax en server concepten vereisen enige ervaring
**Gebruik:** Web server, reverse proxy voor Node.js apps, load balancing, SSL termination

#### Nginx Basis Commando's

**Service Management:**
```bash
# Configuratie testen
sudo nginx -t
sudo nginx -T  # test en toon configuratie

# Service status en beheer
sudo systemctl status nginx
sudo systemctl start nginx
sudo systemctl stop nginx
sudo systemctl restart nginx
sudo systemctl reload nginx    # herlaad configuratie zonder downtime

# Sites activeren
sudo ln -s /etc/nginx/sites-available/mysite /etc/nginx/sites-enabled/
sudo unlink /etc/nginx/sites-enabled/mysite  # deactiveren

# Logs bekijken
sudo tail -f /var/log/nginx/access.log
sudo tail -f /var/log/nginx/error.log
```

#### Basis Server Configuratie

**Poorten en Domains:**
```nginx
server {
    # HTTP poort
    listen 80;
    
    # HTTPS poort
    listen 443 ssl;
    
    # IPv6 ondersteuning
    listen [::]:80;
    listen [::]:443 ssl;
    
    # Server namen
    server_name example.com www.example.com;
    # server_name *.example.com;      # wildcards
    # server_name example.*;          # alle TLD's
    # server_name "";                 # IP address
    
    # Document root
    root /var/www/html;
    index index.html index.php;
}
```

#### Statische Website Hosting

**File Serving:**
```nginx
server {
    listen 80;
    server_name mywebsite.com;
    root /var/www/mywebsite;
    
    # Basis locatie
    location / {
        try_files $uri $uri/ =404;
    }
    
    # Statische assets met caching
    location ~* \.(css|js|img|jpg|jpeg|png|gif|ico|svg)$ {
        expires 1y;
        add_header Cache-Control "public, immutable";
    }
    
    # Security headers
    add_header X-Frame-Options "SAMEORIGIN" always;
    add_header X-Content-Type-Options "nosniff" always;
    add_header X-XSS-Protection "1; mode=block" always;
}
```

#### Reverse Proxy Setup

**Node.js Application Proxy:**
```nginx
# Upstream definitie
upstream nodejs_backend {
    server 127.0.0.1:3000;
    server 127.0.0.1:3001;  # multiple instances
    keepalive 32;
}

server {
    listen 80;
    server_name api.example.com;
    
    location / {
        proxy_pass http://nodejs_backend;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header X-Forwarded-Proto $scheme;
        proxy_cache_bypass $http_upgrade;
        proxy_redirect off;
    }
}
```

**WebSocket Support:**
```nginx
server {
    listen 80;
    server_name websocket.example.com;
    
    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection "upgrade";
        proxy_set_header Host $host;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_read_timeout 86400;
    }
}
```

#### SSL/HTTPS Configuratie

**SSL Setup met Let's Encrypt:**
```nginx
server {
    listen 80;
    server_name example.com www.example.com;
    
    # Redirect HTTP naar HTTPS
    return 301 https://$server_name$request_uri;
}

server {
    listen 443 ssl http2;
    server_name example.com www.example.com;
    
    # SSL certificaten
    ssl_certificate /etc/letsencrypt/live/example.com/fullchain.pem;
    ssl_certificate_key /etc/letsencrypt/live/example.com/privkey.pem;
    
    # SSL configuratie
    ssl_protocols TLSv1.2 TLSv1.3;
    ssl_ciphers ECDHE-RSA-AES256-GCM-SHA512:DHE-RSA-AES256-GCM-SHA512;
    ssl_prefer_server_ciphers off;
    ssl_session_cache shared:SSL:10m;
    ssl_session_timeout 10m;
    
    # HSTS
    add_header Strict-Transport-Security "max-age=63072000" always;
    
    # OCSP Stapling
    ssl_stapling on;
    ssl_stapling_verify on;
    ssl_trusted_certificate /etc/letsencrypt/live/example.com/chain.pem;
    
    location / {
        root /var/www/html;
        index index.html;
    }
}
```

#### Load Balancing

**Multiple Backend Servers:**
```nginx
upstream backend_pool {
    # Load balancing methods
    # ip_hash;        # based on client IP
    # least_conn;     # least connections
    # random;         # random selection
    
    server backend1.example.com:8080 weight=3;
    server backend2.example.com:8080 weight=2;
    server backend3.example.com:8080 weight=1;
    server backup.example.com:8080 backup;
    
    # Health checks
    health_check interval=10s fails=3 passes=2;
}

server {
    listen 80;
    server_name loadbalancer.example.com;
    
    location / {
        proxy_pass http://backend_pool;
        proxy_set_header Host $host;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    }
}
```

#### Redirects en URL Rewriting

**Common Redirects:**
```nginx
server {
    listen 80;
    server_name example.com;
    
    # WWW naar non-WWW redirect
    if ($host = 'www.example.com') {
        return 301 http://example.com$request_uri;
    }
    
    # Specifieke path redirects
    location /old-page {
        return 301 /new-page;
    }
    
    # Pattern-based redirects
    location ~ ^/blog/(.*)$ {
        return 301 /articles/$1;
    }
    
    # Query string preserving redirect
    location /search {
        return 301 /new-search$is_args$args;
    }
}
```

**URL Rewriting:**
```nginx
server {
    listen 80;
    server_name example.com;
    root /var/www/html;
    
    # Rewrite rules
    rewrite ^/products/([0-9]+)/?$ /product.php?id=$1 last;
    rewrite ^/category/([a-zA-Z0-9-]+)/?$ /cat.php?name=$1 last;
    
    # Try files for SPA routing
    location / {
        try_files $uri $uri/ /index.html;
    }
}
```

#### Performance Optimalisatie

**Caching en Compression:**
```nginx
http {
    # Gzip compression
    gzip on;
    gzip_vary on;
    gzip_comp_level 6;
    gzip_types
        text/plain
        text/css
        text/xml
        text/javascript
        application/javascript
        application/xml+rss
        application/json;
    
    # Brotli compression (if module available)
    # brotli on;
    # brotli_comp_level 6;
    
    server {
        listen 80;
        server_name example.com;
        root /var/www/html;
        
        # Static file caching
        location ~* \.(jpg|jpeg|png|gif|ico|css|js)$ {
            expires 1y;
            add_header Cache-Control "public, no-transform";
        }
        
        # Disable access logs for static files
        location ~* \.(jpg|jpeg|png|gif|ico|css|js)$ {
            access_log off;
        }
    }
}
```

#### Security Configuratie

**Security Headers:**
```nginx
server {
    listen 443 ssl http2;
    server_name secure.example.com;
    
    # Security headers
    add_header X-Frame-Options "SAMEORIGIN" always;
    add_header X-Content-Type-Options "nosniff" always;
    add_header X-XSS-Protection "1; mode=block" always;
    add_header Referrer-Policy "no-referrer-when-downgrade" always;
    add_header Content-Security-Policy "default-src 'self' http: https: data: blob: 'unsafe-inline'" always;
    
    # Hide nginx version
    server_tokens off;
    
    # Rate limiting
    limit_req_zone $binary_remote_addr zone=login:10m rate=10r/m;
    
    location /login {
        limit_req zone=login burst=5;
        proxy_pass http://backend;
    }
    
    # Block access to hidden files
    location ~ /\. {
        deny all;
        access_log off;
        log_not_found off;
    }
}
```

#### Monitoring en Logging

**Custom Log Formats:**
```nginx
http {
    # Custom log format
    log_format main '$remote_addr - $remote_user [$time_local] "$request" '
                   '$status $body_bytes_sent "$http_referer" '
                   '"$http_user_agent" "$http_x_forwarded_for"';
    
    # JSON logging
    log_format json_combined escape=json
    '{'
        '"time_local":"$time_local",'
        '"remote_addr":"$remote_addr",'
        '"remote_user":"$remote_user",'
        '"request":"$request",'
        '"status": "$status",'
        '"body_bytes_sent":"$body_bytes_sent",'
        '"request_time":"$request_time",'
        '"http_referrer":"$http_referer",'
        '"http_user_agent":"$http_user_agent"'
    '}';
    
    access_log /var/log/nginx/access.log main;
    error_log /var/log/nginx/error.log warn;
}
```

#### Troubleshooting

**Debug Commands:**
```bash
# Configuratie fouten checken
sudo nginx -t

# Actieve configuratie bekijken
sudo nginx -T

# Process informatie
ps aux | grep nginx
sudo netstat -tlnp | grep nginx

# Log analyse
sudo tail -f /var/log/nginx/error.log
sudo grep "404" /var/log/nginx/access.log
sudo awk '{print $1}' /var/log/nginx/access.log | sort | uniq -c | sort -nr

# Performance testing
ab -n 1000 -c 10 http://example.com/
```

---

## 🌍 **HTTP & API Integration**

*HTTP en API integratie tools voor het bouwen en testen van web services, REST APIs en het uitwisselen van data tussen clients en servers.*

### 📡 **REST API Design Patterns**

*RESTful API is een architectuurstijl voor het ontwerpen van web services. REST staat voor Representational State Transfer.*

**Leercurve:** 🟡 **Gemiddeld** - HTTP concepten en API design principles
**Gebruik:** Web API's, microservices, data uitwisseling tussen frontend en backend

#### REST API Methodologie

**HTTP Methoden:**
```bash
# CRUD Operations
GET /api/users          # Lijst alle gebruikers (READ)
GET /api/users/123      # Haal specifieke gebruiker op (READ)
POST /api/users         # Maak nieuwe gebruiker aan (CREATE)
PUT /api/users/123      # Update volledige gebruiker (UPDATE)
PATCH /api/users/123    # Gedeeltelijke update (PARTIAL UPDATE)
DELETE /api/users/123   # Verwijder gebruiker (DELETE)

# Collection vs Resource
GET /api/articles       # Collection - lijst artikelen
GET /api/articles/456   # Resource - specifiek artikel
```

**HTTP Status Codes:**
```bash
# Success Responses (2xx)
200 OK                  # Succesvolle GET, PUT, PATCH
201 Created            # Succesvolle POST - resource aangemaakt
202 Accepted           # Async operatie geaccepteerd
204 No Content         # Succesvolle DELETE

# Client Errors (4xx)
400 Bad Request        # Invalide request syntax
401 Unauthorized       # Authenticatie vereist
403 Forbidden          # Geen permissies
404 Not Found          # Resource niet gevonden
409 Conflict           # Conflicterende state
422 Unprocessable Entity # Validatie fouten
429 Too Many Requests  # Rate limiting

# Server Errors (5xx)
500 Internal Server Error  # Server fout
502 Bad Gateway           # Proxy/gateway fout
503 Service Unavailable   # Tijdelijk offline
```

**API Versioning:**
```bash
# URL Path versioning
GET /api/v1/users
GET /api/v2/users

# Header versioning
GET /api/users
Accept: application/json; version=1

# Query parameter versioning
GET /api/users?version=1
```

**Request/Response Headers:**
```bash
# Content negotiation
Accept: application/json
Content-Type: application/json; charset=utf-8

# Authentication
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
Authorization: Basic dXNlcm5hbWU6cGFzc3dvcmQ=

# CORS headers
Access-Control-Allow-Origin: *
Access-Control-Allow-Methods: GET, POST, PUT, DELETE
Access-Control-Allow-Headers: Content-Type, Authorization
```

#### Error Response Format

**Standaard Error Response:**
```json
{
  "error": {
    "code": "VALIDATION_ERROR",
    "message": "De opgegeven data is ongeldig",
    "details": [
      {
        "field": "email",
        "message": "Email adres is vereist"
      },
      {
        "field": "password",
        "message": "Wachtwoord moet minimaal 8 karakters zijn"
      }
    ],
    "timestamp": "2024-01-15T10:30:00Z",
    "path": "/api/users"
  }
}
```

---

### 🌐 **cURL - HTTP Client Tool**

*cURL is een command-line tool voor het overdragen van data via verschillende netwerkprotocollen, vooral gebruikt voor HTTP API testing.*

**Leercurve:** 🟢 **Makkelijk** - Basis commando's zijn snel te leren
**Gebruik:** API testing, file downloads, HTTP debugging, automation scripts

#### Basis cURL Commando's

**GET Requests:**
```bash
# Basis GET request
curl https://api.example.com/users

# Headers toevoegen
curl -H "Accept: application/json" \
     -H "Authorization: Bearer token123" \
     https://api.example.com/users

# Headers weergeven in response
curl -i https://api.example.com/users

# Alleen headers ophalen
curl -I https://api.example.com/users

# Verbose output voor debugging
curl -v https://api.example.com/users
```

**POST Requests:**
```bash
# JSON data versturen
curl -X POST https://api.example.com/users \
     -H "Content-Type: application/json" \
     -d '{"name": "Jan Jansen", "email": "jan@example.com"}'

# Data uit bestand
curl -X POST https://api.example.com/users \
     -H "Content-Type: application/json" \
     -d @user.json

# Form data versturen
curl -X POST https://api.example.com/users \
     -d "name=Jan Jansen" \
     -d "email=jan@example.com"

# File upload
curl -X POST https://api.example.com/upload \
     -F "file=@document.pdf" \
     -F "description=Important document"
```

**Authentication:**
```bash
# Basic authentication
curl -u username:password https://api.example.com/protected

# Bearer token
curl -H "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..." \
     https://api.example.com/protected

# API key als header
curl -H "X-API-Key: abc123def456" \
     https://api.example.com/data
```

**Response Handling:**
```bash
# Output naar bestand
curl -o response.json https://api.example.com/users

# Stil uitvoeren (geen progress bar)
curl -s https://api.example.com/users

# Alleen HTTP status code
curl -o /dev/null -s -w "%{http_code}" https://api.example.com/users

# Response tijd meten
curl -w "Time: %{time_total}s\n" https://api.example.com/users

# Redirects volgen
curl -L https://api.example.com/redirect
```

**Advanced cURL:**
```bash
# Cookies gebruiken
curl -c cookies.txt -b cookies.txt https://api.example.com/session

# SSL certificaat negeren (development only!)
curl -k https://selfsigned.example.com/api

# Timeout instellen
curl --connect-timeout 10 --max-time 60 https://api.example.com/slow

# Retry op failure
curl --retry 3 --retry-delay 5 https://unreliable-api.com/data

# Multiple URLs parallel
curl -Z https://api1.com/data https://api2.com/data

# Custom user agent
curl -A "MijnApp/1.0" https://api.example.com/data
```

---

### 📄 **JSON - JavaScript Object Notation**

*JSON is een lightweight data-interchange format dat door mensen makkelijk te lezen is en door machines makkelijk te parsen.*

**Leercurve:** 🟢 **Makkelijk** - Eenvoudige syntax en breed ondersteund
**Gebruik:** API responses, configuratie bestanden, data opslag, data uitwisseling

#### JSON Syntax en Typen

**Basis Data Typen:**
```json
{
  "string": "Hallo wereld",
  "number": 42,
  "float": 3.14159,
  "boolean": true,
  "null_value": null,
  "array": [1, 2, 3, "vier"],
  "object": {
    "nested": "waarde"
  }
}
```

**Complexe Structuren:**
```json
{
  "gebruiker": {
    "id": 123,
    "naam": "Jan Jansen",
    "email": "jan@example.com",
    "profiel": {
      "geboortedatum": "1990-05-15",
      "adres": {
        "straat": "Hoofdstraat 123",
        "stad": "Amsterdam",
        "postcode": "1000 AB"
      }
    },
    "hobbies": ["programmeren", "fietsen", "lezen"],
    "actief": true
  },
  "metadata": {
    "created_at": "2024-01-15T10:30:00Z",
    "version": "1.2.3"
  }
}
```

**JavaScript JSON Methods:**
```javascript
// JSON string naar object
const jsonString = '{"naam": "Jan", "leeftijd": 30}';
const object = JSON.parse(jsonString);
console.log(object.naam); // "Jan"

// Object naar JSON string
const data = { naam: "Marie", leeftijd: 25 };
const jsonString = JSON.stringify(data);
console.log(jsonString); // '{"naam":"Marie","leeftijd":25}'

// Pretty print JSON
const prettyJson = JSON.stringify(data, null, 2);
console.log(prettyJson);
/*
{
  "naam": "Marie",
  "leeftijd": 25
}
*/

// JSON validatie
function isValidJSON(str) {
  try {
    JSON.parse(str);
    return true;
  } catch (e) {
    return false;
  }
}
```

**Common JSON Patterns voor APIs:**
```json
{
  "success": true,
  "data": {
    "users": [
      {
        "id": 1,
        "name": "Jan Jansen",
        "email": "jan@example.com",
        "created_at": "2024-01-01T00:00:00Z"
      }
    ]
  },
  "pagination": {
    "page": 1,
    "per_page": 10,
    "total": 156,
    "pages": 16
  },
  "meta": {
    "request_id": "req_abc123",
    "response_time_ms": 245
  }
}
```

#### HTTP Status Code Referentie

**1xx Informational:**
```bash
100 Continue            # Client kan doorgaan met request
101 Switching Protocols # Server switcht protocols
```

**2xx Success:**
```bash
200 OK                  # Request succesvol
201 Created            # Resource aangemaakt
202 Accepted           # Request geaccepteerd, processing async
204 No Content         # Succesvol, geen content terug
206 Partial Content    # Gedeeltelijke content (Range requests)
```

**3xx Redirection:**
```bash
301 Moved Permanently  # Resource permanent verplaatst
302 Found             # Resource tijdelijk op andere locatie
304 Not Modified      # Resource niet gewijzigd (caching)
307 Temporary Redirect # Tijdelijke redirect, method behouden
308 Permanent Redirect # Permanente redirect, method behouden
```

**4xx Client Error:**
```bash
400 Bad Request           # Ongeldige request syntax
401 Unauthorized         # Authenticatie vereist
403 Forbidden           # Geen toegang tot resource
404 Not Found           # Resource niet gevonden
405 Method Not Allowed  # HTTP method niet toegestaan
409 Conflict            # Request conflicteert met server state
422 Unprocessable Entity # Validatie fout
429 Too Many Requests   # Rate limit overschreden
```

**5xx Server Error:**
```bash
500 Internal Server Error # Algemene server fout
502 Bad Gateway          # Invalid response van upstream
503 Service Unavailable  # Server tijdelijk offline
504 Gateway Timeout      # Upstream server timeout
```

#### Praktische API Testing Workflows

**API Development Workflow:**
```bash
# 1. Test connectiviteit
curl -I https://api.example.com/health

# 2. Authentication test
curl -X POST https://api.example.com/auth/login \
     -H "Content-Type: application/json" \
     -d '{"email": "test@example.com", "password": "secret123"}'

# 3. CRUD operations testen
# Create
curl -X POST https://api.example.com/users \
     -H "Authorization: Bearer $TOKEN" \
     -H "Content-Type: application/json" \
     -d '{"name": "Test User", "email": "test@example.com"}'

# Read
curl -H "Authorization: Bearer $TOKEN" \
     https://api.example.com/users/123

# Update
curl -X PUT https://api.example.com/users/123 \
     -H "Authorization: Bearer $TOKEN" \
     -H "Content-Type: application/json" \
     -d '{"name": "Updated User"}'

# Delete
curl -X DELETE https://api.example.com/users/123 \
     -H "Authorization: Bearer $TOKEN"

# 4. Error handling testen
curl -X POST https://api.example.com/users \
     -H "Authorization: Bearer invalid_token" \
     -H "Content-Type: application/json" \
     -d '{}'
```

**Response Validation Scripts:**
```bash
#!/bin/bash
# API health check script

API_URL="https://api.example.com"
EXPECTED_STATUS=200

# Test API endpoint
response=$(curl -s -o /dev/null -w "%{http_code}" "$API_URL/health")

if [ "$response" -eq "$EXPECTED_STATUS" ]; then
    echo "✅ API is healthy (Status: $response)"
else
    echo "❌ API unhealthy (Status: $response)"
    exit 1
fi

# Test with JSON response validation
json_response=$(curl -s "$API_URL/status")
status=$(echo "$json_response" | jq -r '.status')

if [ "$status" = "ok" ]; then
    echo "✅ API status OK"
else
    echo "❌ API status: $status"
fi
```

---

## 🧪 **Testing & Quality Assurance**

*Testing tools en frameworks voor het automatiseren van unit tests, integration tests en end-to-end testing van applicaties.*

### ⚡ **Vitest - Modern Testing Framework**

*Vitest is een snelle unit testing framework dat native ES modules ondersteunt en optimaal werkt met Vite.*

**Leercurve:** 🟢 **Makkelijk** - Jest-compatible API met moderne features
**Gebruik:** Unit testing, integration testing, component testing voor Vite projecten

#### Vitest Setup en Configuratie

**Installatie:**
```bash
# Installatie
npm install -D vitest
npm install -D @vitest/ui    # UI voor test results

# TypeScript support
npm install -D @types/node

# Configuratie in package.json
{
  "scripts": {
    "test": "vitest",
    "test:ui": "vitest --ui",
    "test:run": "vitest run",
    "coverage": "vitest --coverage"
  }
}
```

**Basis Test Setup:**
```javascript
// vite.config.ts
import { defineConfig } from 'vite'
import { configDefaults } from 'vitest/config'

export default defineConfig({
  test: {
    globals: true,
    environment: 'jsdom',
    setupFiles: './src/test/setup.ts',
    exclude: [...configDefaults.exclude, 'e2e/*'],
    coverage: {
      reporter: ['text', 'json', 'html'],
      exclude: ['node_modules/', 'src/test/']
    }
  }
})
```

#### Vitest Test Patterns

**Basis Test Structuur:**
```javascript
// src/utils.test.js
import { describe, it, expect, beforeEach, afterEach } from 'vitest'
import { calculateTotal, formatCurrency } from './utils'

describe('Utility Functions', () => {
  beforeEach(() => {
    // Setup voor elke test
  })

  afterEach(() => {
    // Cleanup na elke test
  })

  it('should calculate total correctly', () => {
    const items = [
      { price: 10, quantity: 2 },
      { price: 5, quantity: 3 }
    ]
    
    expect(calculateTotal(items)).toBe(35)
  })

  it('should format currency properly', () => {
    expect(formatCurrency(1234.56)).toBe('€ 1.234,56')
    expect(formatCurrency(0)).toBe('€ 0,00')
  })
})
```

**Async Testing:**
```javascript
import { describe, it, expect, vi } from 'vitest'

describe('API Functions', () => {
  it('should fetch user data', async () => {
    const mockFetch = vi.fn().mockResolvedValue({
      ok: true,
      json: () => Promise.resolve({ id: 1, name: 'Jan Jansen' })
    })
    
    global.fetch = mockFetch
    
    const userData = await fetchUser(1)
    
    expect(userData).toEqual({ id: 1, name: 'Jan Jansen' })
    expect(mockFetch).toHaveBeenCalledWith('/api/users/1')
  })
})
```

**React Component Testing:**
```javascript
import { render, screen, fireEvent } from '@testing-library/react'
import { expect, it, describe, vi } from 'vitest'
import { UserButton } from './UserButton'

describe('UserButton', () => {
  it('calls onClick when clicked', () => {
    const handleClick = vi.fn()
    
    render(<UserButton onClick={handleClick}>Click me</UserButton>)
    
    fireEvent.click(screen.getByText('Click me'))
    
    expect(handleClick).toHaveBeenCalledOnce()
  })

  it('renders with correct text', () => {
    render(<UserButton>Test Button</UserButton>)
    
    expect(screen.getByText('Test Button')).toBeInTheDocument()
  })
})
```

---

### 🎭 **Playwright - End-to-End Testing**

*Playwright is een moderne E2E testing framework voor web applications dat meerdere browsers ondersteunt.*

**Leercurve:** 🟡 **Gemiddeld** - Browser automation concepten en async patterns
**Gebruik:** End-to-end testing, cross-browser testing, visual regression testing

#### Playwright Setup

**Installatie en Configuratie:**
```bash
# Installatie
npm init playwright@latest

# Browsers installeren
npx playwright install

# Test uitvoeren
npx playwright test
npx playwright test --ui    # UI mode
npx playwright test --headed # Met browser UI
```

**Playwright Configuratie:**
```javascript
// playwright.config.ts
import { defineConfig, devices } from '@playwright/test'

export default defineConfig({
  testDir: './tests',
  fullyParallel: true,
  forbidOnly: !!process.env.CI,
  retries: process.env.CI ? 2 : 0,
  workers: process.env.CI ? 1 : undefined,
  reporter: 'html',
  
  use: {
    baseURL: 'http://localhost:3000',
    trace: 'on-first-retry',
    video: 'retain-on-failure',
    screenshot: 'only-on-failure'
  },

  projects: [
    {
      name: 'chromium',
      use: { ...devices['Desktop Chrome'] }
    },
    {
      name: 'firefox',
      use: { ...devices['Desktop Firefox'] }
    },
    {
      name: 'webkit',
      use: { ...devices['Desktop Safari'] }
    },
    {
      name: 'mobile-chrome',
      use: { ...devices['Pixel 5'] }
    }
  ],

  webServer: {
    command: 'npm run dev',
    url: 'http://localhost:3000',
    reuseExistingServer: !process.env.CI
  }
})
```

#### Playwright Test Patterns

**Basis Page Interactions:**
```javascript
// tests/homepage.spec.ts
import { test, expect } from '@playwright/test'

test('homepage has correct title and navigation', async ({ page }) => {
  await page.goto('/')

  // Title check
  await expect(page).toHaveTitle(/My App/)

  // Navigation test
  await page.click('text=About')
  await expect(page.url()).toContain('/about')
  
  // Form interaction
  await page.fill('input[name="email"]', 'test@example.com')
  await page.fill('input[name="password"]', 'password123')
  await page.click('button[type="submit"]')
  
  // Wait for navigation
  await page.waitForURL('/dashboard')
  await expect(page.locator('h1')).toContainText('Dashboard')
})
```

**Advanced Page Object Pattern:**
```javascript
// tests/pages/LoginPage.ts
export class LoginPage {
  constructor(private page: Page) {}

  async goto() {
    await this.page.goto('/login')
  }

  async login(email: string, password: string) {
    await this.page.fill('[data-testid=email]', email)
    await this.page.fill('[data-testid=password]', password)
    await this.page.click('[data-testid=login-button]')
  }

  async expectSuccessMessage() {
    await expect(this.page.locator('[data-testid=success]')).toBeVisible()
  }
}

// tests/auth.spec.ts
import { LoginPage } from './pages/LoginPage'

test('user can login successfully', async ({ page }) => {
  const loginPage = new LoginPage(page)
  
  await loginPage.goto()
  await loginPage.login('user@example.com', 'password123')
  await loginPage.expectSuccessMessage()
})
```

**API Testing met Playwright:**
```javascript
import { test, expect } from '@playwright/test'

test('API endpoints work correctly', async ({ request }) => {
  // GET request
  const response = await request.get('/api/users')
  expect(response.ok()).toBeTruthy()
  
  const users = await response.json()
  expect(users).toHaveLength(3)

  // POST request
  const newUser = {
    name: 'Test User',
    email: 'test@example.com'
  }
  
  const createResponse = await request.post('/api/users', {
    data: newUser
  })
  
  expect(createResponse.ok()).toBeTruthy()
  const createdUser = await createResponse.json()
  expect(createdUser.id).toBeDefined()
})
```

---

### 🃏 **Jest - JavaScript Testing Framework**

*Jest is een comprehensive testing framework voor JavaScript applicaties met built-in assertions, mocking en coverage.*

**Leercurve:** 🟡 **Gemiddeld** - Breed feature set met many concepts
**Gebruik:** Unit testing, integration testing, snapshot testing voor React/Node.js

#### Jest Configuration

**Setup en Configuratie:**
```bash
# Installatie
npm install --save-dev jest babel-jest
npm install --save-dev @testing-library/jest-dom  # Voor React

# TypeScript support
npm install --save-dev @types/jest ts-jest
```

**Jest Configuratie:**
```javascript
// jest.config.js
module.exports = {
  testEnvironment: 'jsdom',
  setupFilesAfterEnv: ['<rootDir>/src/setupTests.js'],
  moduleNameMapping: {
    '^@/(.*)$': '<rootDir>/src/$1',
    '\\.(css|less|scss|sass)$': 'identity-obj-proxy'
  },
  collectCoverageFrom: [
    'src/**/*.{js,jsx,ts,tsx}',
    '!src/index.js',
    '!src/reportWebVitals.js'
  ],
  coverageThreshold: {
    global: {
      branches: 80,
      functions: 80,
      lines: 80,
      statements: 80
    }
  },
  testMatch: [
    '<rootDir>/src/**/__tests__/**/*.{js,jsx,ts,tsx}',
    '<rootDir>/src/**/*.{test,spec}.{js,jsx,ts,tsx}'
  ]
}
```

#### Jest Test Patterns

**Basic Testing:**
```javascript
// math.test.js
describe('Math utilities', () => {
  test('adds 1 + 2 to equal 3', () => {
    expect(1 + 2).toBe(3)
  })

  test('should handle floating point', () => {
    expect(0.1 + 0.2).toBeCloseTo(0.3)
  })

  test('should work with arrays', () => {
    expect(['a', 'b', 'c']).toContain('b')
    expect(['a', 'b', 'c']).toHaveLength(3)
  })
})
```

**Mocking en Spies:**
```javascript
import { fetchUserData, apiClient } from './api'

// Mock module
jest.mock('./api')

describe('User API', () => {
  beforeEach(() => {
    jest.clearAllMocks()
  })

  test('should fetch user data', async () => {
    const mockUser = { id: 1, name: 'Jan' }
    apiClient.get.mockResolvedValue({ data: mockUser })

    const result = await fetchUserData(1)

    expect(result).toEqual(mockUser)
    expect(apiClient.get).toHaveBeenCalledWith('/users/1')
  })

  test('should handle errors', async () => {
    apiClient.get.mockRejectedValue(new Error('Network error'))

    await expect(fetchUserData(1)).rejects.toThrow('Network error')
  })
})
```

**Snapshot Testing:**
```javascript
import renderer from 'react-test-renderer'
import { UserCard } from './UserCard'

test('UserCard renders correctly', () => {
  const user = {
    id: 1,
    name: 'Jan Jansen',
    email: 'jan@example.com'
  }

  const tree = renderer
    .create(<UserCard user={user} />)
    .toJSON()

  expect(tree).toMatchSnapshot()
})
```

---

### 🎪 **Puppeteer - Browser Automation**

*Puppeteer is een Node.js library voor het controleren van Chrome/Chromium browsers via de DevTools Protocol.*

**Leercurve:** 🔴 **Moeilijk** - Browser automation en async programming
**Gebruik:** Web scraping, PDF generation, performance testing, automated screenshots

#### Puppeteer Basis Setup

**Installatie en Configuratie:**
```bash
# Volledige installatie (met Chromium)
npm install puppeteer

# Lightweight versie (eigen browser)
npm install puppeteer-core

# TypeScript support
npm install --save-dev @types/puppeteer
```

**Basis Browser Automation:**
```javascript
const puppeteer = require('puppeteer')

async function basicExample() {
  // Browser starten
  const browser = await puppeteer.launch({
    headless: false, // Browser UI tonen
    devtools: true,
    slowMo: 50      // Vertraag acties voor debugging
  })

  const page = await browser.newPage()
  
  // Pagina laden
  await page.goto('https://example.com')
  
  // Screenshot maken
  await page.screenshot({ path: 'example.png' })
  
  // PDF genereren
  await page.pdf({ path: 'example.pdf', format: 'A4' })
  
  await browser.close()
}
```

#### Puppeteer Advanced Testing

**Form Automation en Testing:**
```javascript
async function testFormSubmission() {
  const browser = await puppeteer.launch()
  const page = await browser.newPage()
  
  await page.goto('https://myapp.com/contact')
  
  // Form invullen
  await page.type('#name', 'Jan Jansen')
  await page.type('#email', 'jan@example.com')
  await page.type('#message', 'Test bericht')
  
  // Submit button klikken
  await page.click('button[type="submit"]')
  
  // Wachten op success bericht
  await page.waitForSelector('.success-message')
  
  const successText = await page.$eval('.success-message', 
    el => el.textContent
  )
  
  console.log('Success message:', successText)
  
  await browser.close()
}
```

**Performance Monitoring:**
```javascript
async function measurePagePerformance() {
  const browser = await puppeteer.launch()
  const page = await browser.newPage()
  
  // Performance metrics starten
  await page.tracing.start({ path: 'trace.json' })
  
  const navigationPromise = page.waitForNavigation()
  await page.goto('https://myapp.com')
  await navigationPromise
  
  // Performance data verzamelen
  const metrics = await page.metrics()
  console.log('Performance metrics:', metrics)
  
  // Trace stoppen
  await page.tracing.stop()
  
  // Network requests monitoren
  page.on('response', response => {
    console.log(`${response.status()} - ${response.url()}`)
  })
  
  await browser.close()
}
```

#### Test Automation Workflows

**Complete Test Suite Setup:**
```javascript
// test-runner.js
const puppeteer = require('puppeteer')

class TestRunner {
  async setup() {
    this.browser = await puppeteer.launch({
      headless: true,
      args: ['--no-sandbox', '--disable-setuid-sandbox']
    })
  }

  async teardown() {
    await this.browser.close()
  }

  async testUserFlow() {
    const page = await this.browser.newPage()
    
    try {
      // Login flow
      await page.goto('http://localhost:3000/login')
      await page.type('[data-testid=email]', 'user@example.com')
      await page.type('[data-testid=password]', 'password123')
      await page.click('[data-testid=login-btn]')
      
      // Verify dashboard
      await page.waitForSelector('[data-testid=dashboard]')
      const userText = await page.$eval('[data-testid=user-name]', 
        el => el.textContent
      )
      
      console.assert(userText.includes('Welcome'), 'User not logged in')
      
      // Create new item
      await page.click('[data-testid=new-item-btn]')
      await page.type('[data-testid=item-title]', 'Test Item')
      await page.click('[data-testid=save-btn]')
      
      // Verify item created
      await page.waitForSelector('[data-testid=item-list]')
      const items = await page.$$('[data-testid=item-row]')
      
      console.assert(items.length > 0, 'No items found')
      
      return { success: true, message: 'User flow completed' }
      
    } catch (error) {
      await page.screenshot({ path: 'error.png' })
      return { success: false, error: error.message }
    } finally {
      await page.close()
    }
  }
}

// Test uitvoeren
async function runTests() {
  const runner = new TestRunner()
  await runner.setup()
  
  const result = await runner.testUserFlow()
  console.log('Test result:', result)
  
  await runner.teardown()
}

runTests().catch(console.error)
```

#### Testing Best Practices

**Reliable Selectors:**
```javascript
// ❌ Fragile selectors
await page.click('.btn-primary')  // CSS classes kunnen wijzigen
await page.click('div > button:nth-child(2)')  // Positie kan wijzigen

// ✅ Stable selectors
await page.click('[data-testid=submit-button]')  // Data attributes
await page.click('#login-form button[type="submit"]')  // Semantic selectors
await page.click('text=Submit')  // Text content (Playwright)
```

**Wait Strategies:**
```javascript
// Wachten op elementen
await page.waitForSelector('#results')

// Wachten op network requests
await page.waitForResponse('**/api/users')

// Wachten op JavaScript execution
await page.waitForFunction(() => window.dataLoaded === true)

// Custom wait met timeout
await page.waitForSelector('.loading', { hidden: true, timeout: 5000 })
```

---

## 🛠️ **Development Tools**

*Essentiële development tools voor debugging, performance analysis, security en media processing.*

### 🔍 **Chrome DevTools - Browser Developer Tools**

*Chrome DevTools is een set van web development tools direct ingebouwd in Google Chrome voor debugging en optimization.*

**Leercurve:** 🟢 **Makkelijk** - Intuïtieve interface met powerful features
**Gebruik:** Debugging, performance profiling, network analysis, DOM inspection

#### DevTools Keyboard Shortcuts

**Opening DevTools:**
```bash
Ctrl + Shift + I    # Open laatste gebruikte panel
Ctrl + Shift + J    # Open Console panel
Ctrl + Shift + C    # Open Elements panel en inspect mode
F12                 # Toggle DevTools
```

**Globale Shortcuts:**
```bash
F1                  # Settings tonen
Ctrl + ]            # Volgend panel
Ctrl + [            # Vorig panel
Ctrl + Shift + D    # Toggle dock position
Ctrl + Shift + M    # Toggle device mode
Ctrl + Shift + P    # Command menu
Esc                 # Toggle drawer
Ctrl + F            # Zoeken in huidig panel
Ctrl + Shift + F    # Zoeken in alle bestanden
Ctrl + P            # Open file (Sources panel)
```

#### Elements Panel

**DOM Manipulation:**
```javascript
// Console commands voor DOM
$0                  // Laatste geselecteerde element
$1 - $4            // Vorige selecties
$('#id')           // querySelector shortcut
$$('.class')       // querySelectorAll shortcut

// Element properties
$0.innerHTML       // HTML content
$0.textContent     // Text content
$0.style           // Inline styles
$0.classList       // Class list

// DOM manipulation
$0.remove()        // Element verwijderen
$0.setAttribute('data-test', 'value')
$0.classList.add('highlight')
```

**CSS Inspection:**
```css
/* Force element states */
:hover
:active  
:focus
:visited
:focus-within

/* Device emulation */
@media (max-width: 768px)
@media (prefers-color-scheme: dark)
@media (prefers-reduced-motion: reduce)
```

#### Console API

**Console Methods:**
```javascript
// Basis logging
console.log('Normale log')
console.info('Info bericht')
console.warn('Waarschuwing')
console.error('Error bericht')

// Groeperen
console.group('Groep naam')
console.log('Item 1')
console.log('Item 2')
console.groupEnd()

// Tabellen
console.table([
  { name: 'Jan', age: 30 },
  { name: 'Marie', age: 25 }
])

// Timing
console.time('operatie')
// ... code ...
console.timeEnd('operatie')

// Assertions
console.assert(false, 'Dit wordt getoond')
console.assert(true, 'Dit wordt niet getoond')

// Stack trace
console.trace('Trace punt')

// Object inspection
console.dir(document.body)

// Styling
console.log('%cGestyled bericht', 'color: blue; font-size: 20px')
```

#### Network Panel

**Network Analysis:**
```javascript
// Performance API
performance.mark('start')
// ... operatie ...
performance.mark('end')
performance.measure('operatie', 'start', 'end')

// Resource timing
performance.getEntriesByType('resource').forEach(resource => {
  console.log(`${resource.name}: ${resource.duration}ms`)
})

// Network conditions simulatie
// Slow 3G: Download 400kb/s, Upload 400kb/s, Latency 2000ms
// Fast 3G: Download 1.6Mb/s, Upload 750kb/s, Latency 150ms
```

#### Performance Profiling

**Performance Metrics:**
```javascript
// Core Web Vitals
// LCP - Largest Contentful Paint
// FID - First Input Delay  
// CLS - Cumulative Layout Shift

// Performance Observer
const observer = new PerformanceObserver((list) => {
  for (const entry of list.getEntries()) {
    console.log(entry)
  }
})

observer.observe({ entryTypes: ['paint', 'layout-shift'] })

// Memory profiling
console.memory  // Heap snapshot info
performance.memory  // Memory usage
```

#### Sources Panel Debugging

**Breakpoints en Debugging:**
```javascript
// Conditional breakpoint
// Right-click op regel nummer -> Add conditional breakpoint
count > 10

// Logpoint (geen execution pause)
// Right-click -> Add logpoint
'User:', user.name, 'Count:', count

// XHR/Fetch breakpoints
// Pause on URL containing: /api/

// Event listener breakpoints
// Mouse -> click
// Keyboard -> keydown
// Touch -> touchstart
```

#### Application Panel

**Storage Inspection:**
```javascript
// Local Storage
localStorage.setItem('theme', 'dark')
localStorage.getItem('theme')
localStorage.removeItem('theme')
localStorage.clear()

// Session Storage
sessionStorage.setItem('tempData', JSON.stringify(data))

// Cookies
document.cookie = "user=Jan; expires=Thu, 18 Dec 2025 12:00:00 UTC"

// IndexedDB
const request = indexedDB.open('MyDatabase', 1)
request.onsuccess = (event) => {
  const db = event.target.result
  // Use database
}

// Service Worker
navigator.serviceWorker.register('/sw.js')
```

---

### 🎬 **FFmpeg - Media Processing**

*FFmpeg is een complete cross-platform oplossing voor het opnemen, converteren en streamen van audio en video.*

**Leercurve:** 🔴 **Moeilijk** - Complexe command-line syntax met vele opties
**Gebruik:** Video conversie, audio processing, streaming, screen recording

#### FFmpeg Basis Commando's

**Video Conversie:**
```bash
# Basis conversie
ffmpeg -i input.mp4 output.avi

# Format conversie met codec specificatie
ffmpeg -i input.mov -c:v libx264 -c:a aac output.mp4

# Video kwaliteit instellen
ffmpeg -i input.mp4 -c:v libx264 -crf 23 output.mp4
# CRF: 0 = lossless, 23 = default, 51 = slechtste kwaliteit

# Bitrate instellen
ffmpeg -i input.mp4 -b:v 1M -b:a 128k output.mp4
```

**Video Resizing en Cropping:**
```bash
# Resize naar specifieke resolutie
ffmpeg -i input.mp4 -s 1280x720 output.mp4

# Aspect ratio behouden
ffmpeg -i input.mp4 -vf scale=1280:-1 output.mp4

# Crop video
ffmpeg -i input.mp4 -vf "crop=640:480:100:50" output.mp4
# crop=width:height:x:y

# Rotate video
ffmpeg -i input.mp4 -vf "transpose=1" output.mp4
# 0 = 90° counter-clockwise + flip
# 1 = 90° clockwise
# 2 = 90° counter-clockwise
# 3 = 90° clockwise + flip
```

**Audio Processing:**
```bash
# Audio extractie
ffmpeg -i video.mp4 -vn -acodec copy audio.aac

# Audio toevoegen aan video
ffmpeg -i video.mp4 -i audio.mp3 -c:v copy -c:a aac output.mp4

# Volume aanpassen
ffmpeg -i input.mp4 -af "volume=0.5" output.mp4

# Audio normaliseren
ffmpeg -i input.mp4 -af loudnorm output.mp4

# Verwijder audio
ffmpeg -i input.mp4 -an output.mp4
```

**Video Editing:**
```bash
# Trim video (van 00:01:00 tot 00:02:00)
ffmpeg -i input.mp4 -ss 00:01:00 -t 00:01:00 output.mp4

# Trim met re-encoding voorkomen
ffmpeg -ss 00:01:00 -i input.mp4 -t 00:01:00 -c copy output.mp4

# Video samenvoegen
ffmpeg -f concat -safe 0 -i filelist.txt -c copy output.mp4
# filelist.txt:
# file 'video1.mp4'
# file 'video2.mp4'

# Video speed up/slow down
ffmpeg -i input.mp4 -vf "setpts=0.5*PTS" -af "atempo=2.0" output.mp4
```

**GIF Creation:**
```bash
# Video naar GIF
ffmpeg -i input.mp4 -vf "fps=10,scale=320:-1" output.gif

# Geoptimaliseerde GIF met palette
ffmpeg -i input.mp4 -vf "fps=10,scale=320:-1:flags=lanczos,palettegen" palette.png
ffmpeg -i input.mp4 -i palette.png -filter_complex \
  "fps=10,scale=320:-1:flags=lanczos[x];[x][1:v]paletteuse" output.gif
```

**Screen Recording:**
```bash
# Screen capture (Linux)
ffmpeg -f x11grab -s 1920x1080 -i :0.0 output.mp4

# Met audio
ffmpeg -f x11grab -s 1920x1080 -i :0.0 -f alsa -i default output.mp4

# Windows screen capture
ffmpeg -f gdigrab -i desktop output.mp4

# macOS screen capture
ffmpeg -f avfoundation -i "1:0" output.mp4
```

**Streaming:**
```bash
# RTMP streaming
ffmpeg -re -i input.mp4 -c:v libx264 -b:v 2M -c:a aac -b:a 128k \
  -f flv rtmp://server/live/stream

# HLS output
ffmpeg -i input.mp4 -c:v libx264 -c:a aac -f hls \
  -hls_time 10 -hls_list_size 0 output.m3u8
```

---

### 🔐 **OpenSSL - Cryptography Toolkit**

*OpenSSL is een robuuste toolkit voor Transport Layer Security (TLS) en algemene cryptografie.*

**Leercurve:** 🔴 **Moeilijk** - Complexe cryptografie concepten en commando's
**Gebruik:** SSL certificaten, encryptie, hashing, key management

#### Certificate Management

**Private Key Operations:**
```bash
# Generate RSA private key
openssl genrsa -out private.key 2048

# Generate met password
openssl genrsa -aes256 -out private.key 4096

# View private key details
openssl rsa -in private.key -text -noout

# Remove password from key
openssl rsa -in encrypted.key -out decrypted.key

# Generate EC private key
openssl ecparam -name prime256v1 -genkey -out ec-private.key
```

**Certificate Signing Request (CSR):**
```bash
# Create CSR
openssl req -new -key private.key -out request.csr \
  -subj "/C=NL/ST=Noord-Holland/L=Amsterdam/O=Company/CN=example.com"

# CSR met SAN (Subject Alternative Names)
openssl req -new -key private.key -out request.csr -config <(
cat <<EOF
[req]
distinguished_name = req_distinguished_name
req_extensions = v3_req

[req_distinguished_name]
CN = example.com

[v3_req]
subjectAltName = @alt_names

[alt_names]
DNS.1 = example.com
DNS.2 = www.example.com
DNS.3 = api.example.com
EOF
)

# View CSR
openssl req -in request.csr -text -noout
```

**Certificate Operations:**
```bash
# Self-signed certificate
openssl req -x509 -new -nodes -key private.key \
  -sha256 -days 365 -out certificate.crt

# View certificate
openssl x509 -in certificate.crt -text -noout

# Verify certificate
openssl verify -CAfile ca.crt certificate.crt

# Convert formats
openssl x509 -in cert.pem -outform DER -out cert.der
openssl x509 -in cert.der -inform DER -out cert.pem

# Extract public key
openssl x509 -in certificate.crt -pubkey -noout > public.key
```

**PKCS#12 (PFX) Files:**
```bash
# Create PKCS#12
openssl pkcs12 -export -out certificate.pfx \
  -inkey private.key -in certificate.crt -certfile ca.crt

# Extract from PKCS#12
openssl pkcs12 -in certificate.pfx -out certificate.pem -nodes

# Extract alleen private key
openssl pkcs12 -in certificate.pfx -nocerts -out private.key

# Extract alleen certificate
openssl pkcs12 -in certificate.pfx -clcerts -nokeys -out certificate.crt
```

#### Encryption en Hashing

**File Encryption:**
```bash
# Encrypt file
openssl enc -aes-256-cbc -salt -in file.txt -out file.enc

# Decrypt file
openssl enc -d -aes-256-cbc -in file.enc -out file.txt

# Base64 encoding
openssl base64 -in file.txt -out file.b64
openssl base64 -d -in file.b64 -out file.txt
```

**Hashing:**
```bash
# Generate hashes
openssl dgst -sha256 file.txt
openssl dgst -sha512 file.txt
openssl dgst -md5 file.txt

# HMAC
openssl dgst -sha256 -hmac "secret" file.txt

# Password hashing
openssl passwd -6 -salt xyz password  # SHA512
```

#### SSL/TLS Testing

**Test SSL Connections:**
```bash
# Test HTTPS connection
openssl s_client -connect example.com:443

# Show certificate chain
openssl s_client -showcerts -connect example.com:443

# Test met specific protocol
openssl s_client -connect example.com:443 -tls1_2

# Test STARTTLS
openssl s_client -starttls smtp -connect mail.example.com:587

# Check certificate dates
echo | openssl s_client -connect example.com:443 2>/dev/null | \
  openssl x509 -noout -dates
```

---

### 🔤 **RegExp - Regular Expressions**

*Regular Expressions zijn patterns gebruikt voor het matchen van character combinaties in strings.*

**Leercurve:** 🟡 **Gemiddeld** - Syntax vereist oefening maar zeer krachtig
**Gebruik:** Text parsing, validation, search/replace, data extraction

#### RegExp Basis Patterns

**Character Classes:**
```javascript
// Basis classes
/./ // Elk karakter behalve newline
/\w/ // Word karakter [a-zA-Z0-9_]
/\W/ // Geen word karakter
/\d/ // Digit [0-9]
/\D/ // Geen digit
/\s/ // Whitespace [ \t\n\r\f]
/\S/ // Geen whitespace

// Custom classes
/[aeiou]/ // Elke klinker
/[^aeiou]/ // Geen klinker
/[a-z]/ // Lowercase letter
/[A-Z]/ // Uppercase letter
/[0-9]/ // Digit
/[a-zA-Z0-9]/ // Alphanumeric
```

**Anchors en Boundaries:**
```javascript
/^start/ // Begin van string
/end$/ // Eind van string
/^exact$/ // Exacte match
/\bword\b/ // Word boundary
/\Bword\B/ // Geen word boundary

// Multiline mode
/^line/m // Begin van regel
/line$/m // Eind van regel
```

**Quantifiers:**
```javascript
/a*/ // 0 of meer
/a+/ // 1 of meer
/a?/ // 0 of 1
/a{3}/ // Exact 3
/a{3,}/ // 3 of meer
/a{3,5}/ // Tussen 3 en 5

// Greedy vs Lazy
/.*/ // Greedy - match zoveel mogelijk
/.*?/ // Lazy - match zo weinig mogelijk
```

#### Geavanceerde Patterns

**Groups en Capturing:**
```javascript
// Capturing groups
/(ab)+/ // Capture "ab" herhalingen
/(\d{4})-(\d{2})-(\d{2})/ // Datum capture

// Non-capturing groups
/(?:ab)+/ // Groep zonder capture

// Named groups
/(?<year>\d{4})-(?<month>\d{2})-(?<day>\d{2})/

// Backreferences
/(["'])(.*?)\1/ // Match quotes
/(\w+)\s+\1/ // Herhaald woord
```

**Lookahead en Lookbehind:**
```javascript
// Positive lookahead
/foo(?=bar)/ // "foo" gevolgd door "bar"

// Negative lookahead
/foo(?!bar)/ // "foo" niet gevolgd door "bar"

// Positive lookbehind
/(?<=foo)bar/ // "bar" voorafgegaan door "foo"

// Negative lookbehind
/(?<!foo)bar/ // "bar" niet voorafgegaan door "foo"
```

#### Praktische RegExp Voorbeelden

**Common Validations:**
```javascript
// Email (simpel)
/^[^\s@]+@[^\s@]+\.[^\s@]+$/

// Email (uitgebreid)
/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/

// URL
/^https?:\/\/(www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)$/

// Nederlandse postcode
/^[1-9]\d{3}\s?[A-Z]{2}$/

// Telefoonnummer (NL)
/^((\+|00)?31|0)[\s-]?[1-9][\s-]?(\d[\s-]?){8}$/

// Sterk wachtwoord
/^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$/
```

**String Manipulation:**
```javascript
// Trim whitespace
str.replace(/^\s+|\s+$/g, '')

// Multiple spaces naar single
str.replace(/\s+/g, ' ')

// CamelCase naar kebab-case
str.replace(/([A-Z])/g, '-$1').toLowerCase()

// Extract numbers
str.match(/\d+/g)

// Remove HTML tags
str.replace(/<[^>]*>/g, '')

// Highlight search terms
str.replace(/(search)/gi, '<mark>$1</mark>')
```

**JavaScript RegExp Methods:**
```javascript
// Test pattern
const pattern = /hello/i
pattern.test('Hello World') // true

// Match
'Hello World'.match(/\w+/g) // ['Hello', 'World']

// Replace
'Hello World'.replace(/World/, 'JavaScript')

// Split
'a,b;c:d'.split(/[,;:]/) // ['a', 'b', 'c', 'd']

// Search
'Hello World'.search(/World/) // 6

// Exec with groups
const regex = /(\d{4})-(\d{2})-(\d{2})/
const result = regex.exec('2024-01-15')
// result[0] = '2024-01-15'
// result[1] = '2024'
// result[2] = '01'
// result[3] = '15'
```

---

## 🌐 **Web Technologies**

*Core web technologieën voor het bouwen van moderne web applicaties met HTML5, DOM manipulation, APIs en development shortcuts.*

### 📄 **HTML5 - HyperText Markup Language**

*HTML5 is de laatste versie van HTML met moderne semantic elements, multimedia support en enhanced forms.*

**Leercurve:** 🟢 **Makkelijk** - Basis markup is eenvoudig te leren
**Gebruik:** Web page structuur, semantic markup, forms, multimedia integratie

#### HTML5 Document Structure

**Modern HTML5 Template:**
```html
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="Beschrijving van de pagina">
    
    <!-- Open Graph voor social media -->
    <meta property="og:title" content="Pagina Titel">
    <meta property="og:description" content="Pagina beschrijving">
    <meta property="og:image" content="https://example.com/image.jpg">
    <meta property="og:url" content="https://example.com">
    
    <title>Mijn HTML5 Pagina</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" href="/favicon.png">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">Over Ons</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <article>
            <h1>Welkom bij HTML5</h1>
            <section>
                <h2>Introductie</h2>
                <p>Content hier...</p>
            </section>
        </article>
        
        <aside>
            <h3>Gerelateerde Links</h3>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
            </ul>
        </aside>
    </main>
    
    <footer>
        <p>&copy; 2024 Mijn Website. Alle rechten voorbehouden.</p>
    </footer>
    
    <script src="app.js"></script>
</body>
</html>
```

#### HTML5 Semantic Elements

**Structurele Elements:**
```html
<!-- Page structuur -->
<header>Site header content</header>
<nav>Navigation links</nav>
<main>Main page content</main>
<article>Independent content</article>
<section>Thematic grouping</section>
<aside>Sidebar content</aside>
<footer>Footer content</footer>

<!-- Content grouping -->
<figure>
    <img src="diagram.png" alt="Diagram">
    <figcaption>Figuur 1: Systeem architectuur</figcaption>
</figure>

<!-- Details disclosure -->
<details>
    <summary>Meer informatie</summary>
    <p>Verborgen content die wordt getoond bij klik.</p>
</details>

<!-- Date/Time -->
<time datetime="2024-01-15T10:30">15 januari 2024, 10:30</time>

<!-- Progress indicators -->
<progress value="70" max="100">70%</progress>
<meter value="6" min="0" max="10">6 van 10</meter>
```

#### HTML5 Forms

**Modern Form Elements:**
```html
<form action="/submit" method="POST">
    <!-- Text inputs -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    
    <label for="url">Website:</label>
    <input type="url" id="url" name="url" placeholder="https://example.com">
    
    <label for="tel">Telefoon:</label>
    <input type="tel" id="tel" name="tel" pattern="[0-9]{10}">
    
    <!-- Number inputs -->
    <label for="age">Leeftijd:</label>
    <input type="number" id="age" name="age" min="18" max="100" step="1">
    
    <label for="price">Prijs:</label>
    <input type="range" id="price" name="price" min="0" max="1000" step="10">
    
    <!-- Date/Time inputs -->
    <label for="date">Datum:</label>
    <input type="date" id="date" name="date">
    
    <label for="time">Tijd:</label>
    <input type="time" id="time" name="time">
    
    <label for="datetime">Datum & Tijd:</label>
    <input type="datetime-local" id="datetime" name="datetime">
    
    <!-- Color picker -->
    <label for="color">Kleur:</label>
    <input type="color" id="color" name="color" value="#0066cc">
    
    <!-- File upload -->
    <label for="file">Bestand:</label>
    <input type="file" id="file" name="file" accept="image/*" multiple>
    
    <!-- Datalist (autocomplete) -->
    <label for="browser">Browser:</label>
    <input list="browsers" id="browser" name="browser">
    <datalist id="browsers">
        <option value="Chrome">
        <option value="Firefox">
        <option value="Safari">
        <option value="Edge">
    </datalist>
    
    <!-- Form validation attributes -->
    <input type="text" required minlength="3" maxlength="50">
    <input type="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$">
    
    <button type="submit">Verzenden</button>
</form>
```

#### HTML5 Media Elements

**Video en Audio:**
```html
<!-- Video element -->
<video controls width="640" height="360" poster="thumbnail.jpg">
    <source src="video.webm" type="video/webm">
    <source src="video.mp4" type="video/mp4">
    <track kind="subtitles" src="subs_nl.vtt" srclang="nl" label="Nederlands">
    <p>Uw browser ondersteunt geen HTML5 video.</p>
</video>

<!-- Audio element -->
<audio controls>
    <source src="audio.ogg" type="audio/ogg">
    <source src="audio.mp3" type="audio/mpeg">
    Uw browser ondersteunt geen HTML5 audio.
</audio>

<!-- Canvas voor graphics -->
<canvas id="myCanvas" width="300" height="200">
    Canvas wordt niet ondersteund in uw browser.
</canvas>

<!-- SVG inline -->
<svg width="100" height="100">
    <circle cx="50" cy="50" r="40" fill="blue" />
</svg>
```

---

### 🔧 **DOM API - Document Object Model**

*De DOM API biedt een programmeerbare interface voor HTML documenten, waarmee je dynamisch content kunt manipuleren.*

**Leercurve:** 🟡 **Gemiddeld** - Vereist JavaScript kennis
**Gebruik:** Dynamic content updates, event handling, element manipulation

#### DOM Selection Methods

**Element Selection:**
```javascript
// Single element selection
const element = document.getElementById('myId')
const element = document.querySelector('.myClass')  // Eerste match
const element = document.querySelector('[data-id="123"]')

// Multiple elements selection
const elements = document.getElementsByClassName('myClass')
const elements = document.getElementsByTagName('div')
const elements = document.querySelectorAll('.myClass')  // Alle matches

// Relative selection
const parent = element.parentElement
const children = element.children  // HTMLCollection
const siblings = element.nextElementSibling
const prevSibling = element.previousElementSibling

// Closest parent matching selector
const closestDiv = element.closest('div.container')
```

#### DOM Manipulation

**Creating and Modifying Elements:**
```javascript
// Element creation
const newDiv = document.createElement('div')
const newText = document.createTextNode('Hello World')
const fragment = document.createDocumentFragment()

// Adding content
element.textContent = 'Plain text'  // Veilig voor user input
element.innerHTML = '<strong>HTML content</strong>'  // Let op XSS
element.insertAdjacentHTML('beforeend', '<p>New paragraph</p>')

// Attributes
element.setAttribute('data-id', '123')
element.getAttribute('data-id')
element.removeAttribute('data-id')
element.hasAttribute('data-id')

// Classes
element.classList.add('active', 'highlight')
element.classList.remove('active')
element.classList.toggle('hidden')
element.classList.contains('active')
element.classList.replace('old', 'new')

// Styles
element.style.color = 'red'
element.style.cssText = 'color: red; font-size: 16px;'
const styles = window.getComputedStyle(element)
```

**DOM Tree Manipulation:**
```javascript
// Adding elements
parent.appendChild(child)
parent.insertBefore(newChild, referenceChild)
parent.replaceChild(newChild, oldChild)
element.after(newElement)
element.before(newElement)

// Removing elements
element.remove()
parent.removeChild(child)

// Cloning
const clone = element.cloneNode(true)  // Deep clone
const shallowClone = element.cloneNode(false)
```

#### Event Handling

**Event Listeners:**
```javascript
// Modern event handling
element.addEventListener('click', handleClick)
element.addEventListener('click', handleClick, { once: true })
element.removeEventListener('click', handleClick)

// Event object
function handleClick(event) {
    event.preventDefault()  // Voorkom default actie
    event.stopPropagation()  // Stop event bubbling
    
    console.log(event.type)  // 'click'
    console.log(event.target)  // Element dat geklikt is
    console.log(event.currentTarget)  // Element met listener
    console.log(event.clientX, event.clientY)  // Mouse positie
}

// Event delegation
document.body.addEventListener('click', (e) => {
    if (e.target.matches('.button')) {
        // Handle button click
    }
})

// Custom events
const customEvent = new CustomEvent('myevent', {
    detail: { message: 'Hello' },
    bubbles: true,
    cancelable: true
})
element.dispatchEvent(customEvent)
```

**Common Events:**
```javascript
// Mouse events
'click', 'dblclick', 'mousedown', 'mouseup'
'mouseenter', 'mouseleave', 'mouseover', 'mouseout'
'mousemove', 'contextmenu'

// Keyboard events
'keydown', 'keyup', 'keypress'

// Form events
'submit', 'change', 'input', 'focus', 'blur'
'select', 'invalid'

// Window events
'load', 'DOMContentLoaded', 'resize', 'scroll'
'hashchange', 'popstate', 'beforeunload'

// Touch events
'touchstart', 'touchmove', 'touchend', 'touchcancel'

// Drag events
'dragstart', 'drag', 'dragend', 'dragenter'
'dragover', 'dragleave', 'drop'
```

---

### 🌊 **Fetch API - Modern HTTP Requests**

*De Fetch API biedt een moderne interface voor het maken van HTTP requests, als vervanging voor XMLHttpRequest.*

**Leercurve:** 🟡 **Gemiddeld** - Promises en async/await kennis vereist
**Gebruik:** API calls, data fetching, file uploads, streaming

#### Basic Fetch Requests

**GET Requests:**
```javascript
// Simple GET request
fetch('/api/users')
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(error => console.error('Error:', error))

// Met async/await
async function getUsers() {
    try {
        const response = await fetch('/api/users')
        if (!response.ok) {
            throw new Error(`HTTP error! status: ${response.status}`)
        }
        const data = await response.json()
        return data
    } catch (error) {
        console.error('Fetch error:', error)
    }
}

// Met query parameters
const params = new URLSearchParams({
    page: 1,
    limit: 10,
    sort: 'name'
})
fetch(`/api/users?${params}`)
```

**POST Requests:**
```javascript
// JSON data
fetch('/api/users', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
        'Authorization': 'Bearer token123'
    },
    body: JSON.stringify({
        name: 'Jan Jansen',
        email: 'jan@example.com'
    })
})

// FormData
const formData = new FormData()
formData.append('name', 'Jan Jansen')
formData.append('file', fileInput.files[0])

fetch('/api/upload', {
    method: 'POST',
    body: formData  // Content-Type wordt automatisch gezet
})

// URLSearchParams
const params = new URLSearchParams()
params.append('name', 'Jan')
params.append('age', '30')

fetch('/api/form', {
    method: 'POST',
    body: params
})
```

#### Response Handling

**Response Properties en Methods:**
```javascript
fetch('/api/data')
    .then(response => {
        // Response properties
        console.log(response.status)      // 200
        console.log(response.statusText)  // 'OK'
        console.log(response.ok)          // true als 200-299
        console.log(response.headers.get('Content-Type'))
        console.log(response.url)
        console.log(response.redirected)
        
        // Response parsing
        return response.json()      // Parse als JSON
        // return response.text()   // Parse als text
        // return response.blob()   // Parse als Blob
        // return response.formData() // Parse als FormData
        // return response.arrayBuffer() // Parse als ArrayBuffer
    })
```

**Error Handling:**
```javascript
// Comprehensive error handling
async function fetchWithErrorHandling(url, options = {}) {
    try {
        const response = await fetch(url, options)
        
        // Check if response is ok
        if (!response.ok) {
            throw new Error(`HTTP ${response.status}: ${response.statusText}`)
        }
        
        // Check content type
        const contentType = response.headers.get('content-type')
        if (!contentType || !contentType.includes('application/json')) {
            throw new TypeError("Response was not JSON")
        }
        
        const data = await response.json()
        return data
        
    } catch (error) {
        if (error instanceof TypeError) {
            console.error('Network error:', error)
        } else {
            console.error('Fetch error:', error)
        }
        throw error
    }
}
```

#### Advanced Fetch Features

**Request Options:**
```javascript
// All fetch options
fetch(url, {
    method: 'POST',              // HTTP method
    headers: {                   // Request headers
        'Content-Type': 'application/json',
        'X-Custom-Header': 'value'
    },
    body: JSON.stringify(data),  // Request body
    mode: 'cors',               // cors, no-cors, same-origin
    credentials: 'include',      // include, same-origin, omit
    cache: 'no-cache',          // default, no-cache, reload, force-cache
    redirect: 'follow',         // follow, error, manual
    referrer: 'client',         // client, no-referrer, URL
    referrerPolicy: 'origin',   // no-referrer, origin, etc.
    integrity: '',              // Subresource integrity
    keepalive: false,           // Keep request alive
    signal: abortController.signal  // AbortController signal
})
```

**Aborting Requests:**
```javascript
// Abort controller voor timeout/cancel
const controller = new AbortController()
const timeoutId = setTimeout(() => controller.abort(), 5000)

try {
    const response = await fetch('/api/slow', {
        signal: controller.signal
    })
    clearTimeout(timeoutId)
    const data = await response.json()
} catch (error) {
    if (error.name === 'AbortError') {
        console.log('Request was aborted')
    }
}
```

---

### ⚡ **Emmet - HTML/CSS Expansion**

*Emmet is een plugin voor text editors die het schrijven van HTML en CSS versnelt door abbreviations te expanderen.*

**Leercurve:** 🟢 **Makkelijk** - Simpele syntax, grote productiviteitswinst
**Gebruik:** Rapid HTML/CSS prototyping, boilerplate generation

#### Emmet HTML Abbreviations

**Basic Syntax:**
```css
/* Element generation */
div → <div></div>
p → <p></p>
br → <br>
img → <img src="" alt="">

/* Nesting with > */
nav>ul>li → 
<nav>
    <ul>
        <li></li>
    </ul>
</nav>

/* Siblings with + */
div+p+section →
<div></div>
<p></p>
<section></section>

/* Climb up with ^ */
div>p>span^h2 →
<div>
    <p><span></span></p>
    <h2></h2>
</div>

/* Grouping with () */
div>(header>ul>li*2)+footer>p →
<div>
    <header>
        <ul>
            <li></li>
            <li></li>
        </ul>
    </header>
    <footer>
        <p></p>
    </footer>
</div>
```

**Classes and IDs:**
```css
/* Classes */
div.container → <div class="container"></div>
p.text.large → <p class="text large"></p>

/* IDs */
div#header → <div id="header"></div>
section#main.container → <section id="main" class="container"></section>

/* Multiple classes */
div.col-sm-6.col-md-4 → <div class="col-sm-6 col-md-4"></div>
```

**Multiplication and Numbering:**
```css
/* Multiplication */
ul>li*5 → 
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>

/* Numbering with $ */
ul>li.item$*3 → 
<ul>
    <li class="item1"></li>
    <li class="item2"></li>
    <li class="item3"></li>
</ul>

/* Zero padding with $$ */
ul>li.item$$*3 →
<ul>
    <li class="item01"></li>
    <li class="item02"></li>
    <li class="item03"></li>
</ul>

/* Reverse numbering */
ul>li.item$@-*3 →
<ul>
    <li class="item3"></li>
    <li class="item2"></li>
    <li class="item1"></li>
</ul>

/* Custom counter start */
ul>li.item$@5*3 →
<ul>
    <li class="item5"></li>
    <li class="item6"></li>
    <li class="item7"></li>
</ul>
```

**Attributes and Text:**
```css
/* Attributes with [] */
a[href="#"] → <a href="#"></a>
input[type="text" name="username"] → <input type="text" name="username">
img[src="logo.png" alt="Logo"] → <img src="logo.png" alt="Logo">

/* Text with {} */
p{Click here} → <p>Click here</p>
a[href="#"]{Read more} → <a href="#">Read more</a>

/* Lorem ipsum */
lorem → Lorem ipsum dolor sit amet...
lorem10 → Lorem ipsum met 10 woorden
p*3>lorem5 → 3 paragraphs met elk 5 lorem woorden
```

#### Emmet CSS Abbreviations

**Property Shortcuts:**
```css
/* Margins and Padding */
m10 → margin: 10px;
mt10 → margin-top: 10px;
m10-20 → margin: 10px 20px;
m10-20-30 → margin: 10px 20px 30px;
p10! → padding: 10px !important;

/* Width and Height */
w100 → width: 100px;
w100p → width: 100%;
h50p → height: 50%;
maw500 → max-width: 500px;
mih100 → min-height: 100px;

/* Display and Position */
d:n → display: none;
d:b → display: block;
d:f → display: flex;
pos:a → position: absolute;
pos:r → position: relative;
t10 → top: 10px;
l50p → left: 50%;

/* Colors and Background */
c#333 → color: #333;
bgc#fff → background-color: #fff;
bg+ → background: #fff url() 0 0 no-repeat;

/* Flexbox */
d:f → display: flex;
jc:c → justify-content: center;
ai:c → align-items: center;
fxd:c → flex-direction: column;
```

#### Complex Emmet Examples

**Complete Page Structure:**
```css
/* HTML5 Boilerplate */
html:5 →
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

/* Navigation menu */
nav>ul.nav>li.nav-item*5>a[href="#"]{Item $} →
<nav>
    <ul class="nav">
        <li class="nav-item"><a href="#">Item 1</a></li>
        <li class="nav-item"><a href="#">Item 2</a></li>
        <li class="nav-item"><a href="#">Item 3</a></li>
        <li class="nav-item"><a href="#">Item 4</a></li>
        <li class="nav-item"><a href="#">Item 5</a></li>
    </ul>
</nav>

/* Form structure */
form:post>(.form-group>label[for="field$"]{Field $}+input[type="text" id="field$" name="field$"])*3+button[type="submit"]{Submit} →
<form action="" method="post">
    <div class="form-group">
        <label for="field1">Field 1</label>
        <input type="text" id="field1" name="field1">
    </div>
    <div class="form-group">
        <label for="field2">Field 2</label>
        <input type="text" id="field2" name="field2">
    </div>
    <div class="form-group">
        <label for="field3">Field 3</label>
        <input type="text" id="field3" name="field3">
    </div>
    <button type="submit">Submit</button>
</form>
```

---

## 📚 Documentation

### 📝 **Markdown - Lightweight Markup Language**
Markdown is een eenvoudige opmaaktaal voor het schrijven van geformatteerde tekst.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Documentatie, README bestanden, blog posts, notities

#### Basic Syntax

##### Headers
```markdown
# h1
## h2
### h3
#### h4
##### h5
###### h6

Header 1
========

Header 2
--------
```

##### Emphasis
```markdown
*italic*
_italic_

**bold**
__bold__

***bold italic***
___bold italic___

~~strikethrough~~

`code`
```

##### Lists
```markdown
* Item 1
  * Nested Item 1
* Item 2

- Item 1
  - Nested Item 1
- Item 2

- [ ] Checkbox off
- [x] Checkbox on

1. Item 1
2. Item 2
```

##### Links
```markdown
[link](http://google.com)

[link][google]
[google]: http://google.com

<http://google.com>
```

##### Images
```markdown
![Image alt text](/path/to/img.jpg)
![Image alt text](/path/to/img.jpg "title")

![Image alt text][img]
[img]: http://foo.com/img.jpg

![Image alt text][img_base64]
[img_base64]: <data:image/png;base64,...>
```

##### Code
```markdown
`inline code`
```

```
    4 space indent
    makes a code block
```

~~~markdown
```
code fences
```
~~~

~~~markdown
```js
codeFences.withLanguage()
```
~~~

##### Blockquotes
```markdown
> This is
> a blockquote
>
> > Nested
> > Blockquote
```

##### Horizontal line
```markdown
----
****
```

##### Tables
```markdown
| Column 1 Heading | Column 2 Heading |
| ---------------- | ---------------- |
| Some content     | Other content    |

Column 1 Heading | Column 2 Heading
--- | ---
Some content | Other content
```

#### Advanced Features

##### Table Alignment
```markdown
| Left column | Center column | Right column |
| :---------- | :-----------: | -----------: |
| Cell 1      |   Centered    |        $1600 |
| Cell 2      |    Cell 3     |          $12 |
```

##### Multiline Strings
```markdown
# Literal Block Scalar
Multiline: |
  exactly as you see
  will appear these three
  lines of poetry

# Folded Block Scalar
Multiline: >
  this is really a
  single line of text
  despite appearances
```

##### Backslash Escapes
| Characters | Escape | Description |
|------------|--------|-------------|
| `\` | `\\` | Backslash |
| `` ` `` | `` \` `` | Backtick |
| `*` | `\*` | Asterisk |
| `_` | `\_` | Underscore |
| `{}` | `\{\}` | Curly braces |
| `[]` | `\[\]` | Square brackets |
| `()` | `\(\)` | Parentheses |
| `#` | `\#` | Hash mark |
| `+` | `\+` | Plus sign |
| `-` | `\-` | Minus sign (hyphen) |
| `.` | `\.` | Dot |
| `!` | `\!` | Exclamation mark |

---

### 📖 **JSDoc - JavaScript Documentation**
JSDoc is een standaard voor het documenteren van JavaScript code met speciale comments.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: API documentatie, code annotaties, type hints

#### Functions
```js
/**
 * This is a function.
 *
 * @param {string} n - A string param
 * @param {string} [o] - A optional string param
 * @param {string} [d=DefaultValue] - A optional string param
 * @return {string} A good string
 *
 * @example
 *
 *     foo('hello')
 */
function foo(n, o, d) {
  return n
}
```

#### Types
| Type | Description |
|------|-------------|
| `@param {string=} n` | Optional |
| `@param {string} [n]` | Optional |
| `@param {(string\|number)} n` | Multiple types |
| `@param {*} n` | Any type |
| `@param {...string} n` | Repeatable arguments |
| `@param {string} [n="hi"]` | Optional with default |
| `@param {string[]} n` | Array of strings |
| `@return {Promise<string[]>} n` | Promise fulfilled by array of strings |

#### Variables
```js
/**
 * @type {number}
 */
var FOO = 1

/**
 * @const {number}
 */
const FOO = 1
```

#### Typedef
```js
/**
 * A song
 * @typedef {Object} Song
 * @property {string} title - The title
 * @property {string} artist - The artist
 * @property {number} year - The year
 */

/**
 * Plays a song
 * @param {Song} song - The {@link Song} to be played
 */
function play(song) {}
```

#### Typedef Shorthand
```js
/**
 * A song
 * @typedef {{title: string, artist: string, year: number}} Song
 */

/**
 * Plays a song
 * @param {Song} song - The {@link Song} to be played
 */
function play(song) {}
```

#### Importing Types
```js
/**
 * @typedef {import('./Foo').default} Bar
 */

// or

/** @import { Bar } from "./Foo.js" */

/**
 * @param {Bar} x
 */
function test(x) {}
```

#### Other Keywords
```js
/**
 * @throws {FooException}
 * @async
 * @private
 * @deprecated
 * @see
 *
 * @function
 * @class
 */
```

#### Renaming
```js
/**
 * @alias Foo.bar
 * @name Foo.bar
 */
```

---

### 🔧 **YAML - YAML Ain't Markup Language**
YAML is een mens-leesbaar data serialisatie formaat voor configuratie bestanden.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Configuratie bestanden, CI/CD pipelines, Docker Compose, Kubernetes

#### Basic Syntax

##### Scalar Types
```yaml
n1: 1            # integer
n2: 1.234        # float

s1: 'abc'        # string
s2: "abc"        # string
s3: abc          # string

b: false         # boolean type

d: 2015-04-05    # date type
```

##### Comments
```yaml
# A single line comment example

# block level comment example
# comment line 1
# comment line 2
# comment line 3
```

##### Multiline Strings
```yaml
# Literal Block Scalar
description: |
  hello
  world

# Folded Block Scalar
description: >
  hello world
```

##### Lists
```yaml
# List items begin with a "- "
foods:
  - Apple
  - Orange
  - Strawberry
  - Mango
```

##### Dictionaries
```yaml
# Dictionary are written like "key: value"
name: Martin D'vloper
languages:
  perl: Elite
  python: Elite
  pascal: Lame

employed: true
```

#### Advanced Features

##### Variables & References
```yaml
some_thing: &VAR_NAME foobar
other_thing: *VAR_NAME
```

##### Inheritance
```yaml
parent: &defaults
  a: 2
  b: 3

child:
  <<: *defaults
  b: 4
```

##### Reference Content
```yaml
values: &ref
  - Will be
  - reused below

other_values:
  i_am_ref: *ref
```

##### Two Documents
```yaml
---
document: this is doc 1
---
document: this is doc 2
```

#### Collections

##### Sequence
```yaml
- Mark McGwire
- Sammy Sosa
- Ken Griffey
```

##### Mapping
```yaml
hr:  65       # Home runs
avg: 0.278    # Batting average
rbi: 147      # Runs Batted In
```

##### Mapping to Sequences
```yaml
attributes:
  - a1
  - a2
methods: [getter, setter]
```

##### Sequence of Mappings
```yaml
children:
  - name: Jimmy Smith
    age: 15
  - name: Jimmy Smith
    age: 15
  -
    name: Sammy Sosa
    age: 12
```

##### Nested Collections
```yaml
Jack:
  id: 1
  name: Franc
  salary: 25000
  hobby:
    - a
    - b
  location: { country: "A", city: "A-A" }
```

#### Special Types

##### Unordered Sets
```yaml
set1: !!set
  ? one
  ? two
set2: !!set { "one", "two" }
```

##### Ordered Mappings
```yaml
ordered: !!omap
  - Mark McGwire: 65
  - Sammy Sosa: 63
  - Ken Griffy: 58
```

#### Reference

##### Document Indicators
| Indicator | Description |
|-----------|-------------|
| `%` | Directive indicator |
| `---` | Document header |
| `...` | Document terminator |

##### Collection Indicators
| Indicator | Description |
|-----------|-------------|
| `?` | Key indicator |
| `:` | Value indicator |
| `-` | Nested series entry indicator |
| `,` | Separate in-line branch entries |
| `[]` | Surround in-line series branch |
| `{}` | Surround in-line keyed branch |

##### Alias Indicators
| Indicator | Description |
|-----------|-------------|
| `&` | Anchor property |
| `*` | Alias indicator |

##### Special Keys
| Key | Description |
|-----|-------------|
| `=` | Default "value" mapping key |
| `<<` | Merge keys from another mapping |

---

### 🎯 **TOML - Tom's Obvious, Minimal Language**
TOML is een configuratie bestandsformaat dat gemakkelijk te lezen is door duidelijke semantiek.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Configuratie bestanden, package manifests, settings

#### Basic Types

##### Examples
```toml
bool = true
date = 2006-05-27T07:32:00Z
string = "hello"
number = 42
float = 3.14
scientificNotation = 1e+12
```

##### Comments
```toml
# A single line comment example

# block level comment example
# comment line 1
# comment line 2
# comment line 3
```

##### Integer
```toml
int1 = +42
int2 = 0
int3 = -21
integerRange = 64
```

##### Float
```toml
float2 = 3.1415
float4 = 5e+22
float7 = 6.626e-34
```

##### Boolean
```toml
bool1 = true
bool2 = false
boolMustBeLowercase = true
```

##### Datetime
```toml
date1 = 1989-05-27T07:32:00Z
date2 = 1989-05-26T15:32:00-07:00
date3 = 1989-05-27T07:32:00
date4 = 1989-05-27
time1 = 07:32:00
time2 = 00:32:00.999999
```

#### Strings

##### Basic Strings
```toml
str1 = "I'm a string."
str2 = "You can \"quote\" me."
str3 = "Name\tJos\u00E9\nLoc\tSF."
```

##### Multiline String
```toml
multiLineString = """
Multi-line basic strings are surrounded
by three quotation marks on each side
and allow newlines.
"""
```

##### Literal String
```toml
path = 'C:\Users\nodejs\templates'
path2 = '\\User\admin$\system32'
quoted = 'Tom "Dubs" Preston-Werner'
regex = '<\i\c*\s*>'
```

##### MultiLine Literal String
```toml
re = '''\d{2} apps is t[wo]o many'''
lines = '''
The first newline is
trimmed in raw strings.
All other whitespace
is preserved.
'''
```

#### Tables

##### Basic
```toml
[name]
foo = 1
bar = 2
```

##### Nested
```toml
[table1]
  foo = "bar"

[table1.nested_table]
  baz = "bat"
```

##### Array-like
```toml
[[comments]]
author = "Nate"
text = "Great Article!"

[[comments]]
author = "Anonymous"
text = "Love it!"
```

##### Dot Separated
```toml
[dog."tater.man"]
type = "pug"
```

##### Multi-nested
```toml
[foo.bar.baz]
bat = "hi"
```

##### Inline Table
```toml
name = { first = "Tom", last = "Preston-Werner" }
point = { x = 1, y = 2 }
animal = { type.name = "pug" }
```

#### Arrays
```toml
array1 = [1, 2, 3]
array2 = ["Commas", "are", "delimiter"]
array3 = [8001, 8001, 8002]
```

##### Friendly Array
```toml
array1 = [ "Don't mix", "different", "types" ]
array2 = [ [ 1.2, 2.4 ], ["all", 'strings', """are the same""", '''type'''] ]
array3 = [
  "Whitespace", "is",
  "ignored"
]
```

---

### 📋 **XML - eXtensible Markup Language**
XML is een opmaaktaal voor het opslaan en transporteren van data.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Data uitwisseling, configuratie, web services, RSS feeds

#### What is XML
XML stands for eXtensible Markup Language, XML was designed to store and transport data. XML is often used for distributing data over the Internet (especially in web development).

#### XML vs HTML
* **XML**: is used to store or transport data (Complement to HTML)
* **HTML**: is used to format and display the same data

XML does not carry any information about how to be displayed. The same XML data can be used in many different presentation scenarios. Because of this, with XML, there is a full separation between data and presentation.

#### XML Syntax
The XML language has no predefined tags, but the syntax is rather logic and easy to learn. XML documents must contain one root element that is the parent of all other elements.

```xml
<bookstore>
  <book category="children">
    <title>Harry Potter</title>
    <author>J K. Rowling</author>
    <year>2005</year>
    <price>29.99</price>
  </book>
  <book category="web">
    <title>Learning XML</title>
    <author>Erik T. Ray</author>
    <year>2003</year>
    <price>39.95</price>
  </book>
</bookstore>
```

#### XML Rules
1. **XML Tags are Case Sensitive**
2. **All XML Elements Must Have a Closing Tag**
```xml
<p>This is a paragraph.</p>
<br />  <!-- This is a self closing -->
```
3. **XML Attribute Values Must Always be Quoted**
4. **Pay attention to the name rules**

#### XML Schema/DTD
The purpose of a DTD (Document Type Definition) is to define the structure of an XML document. It defines the structure with a list of legal elements.

#### When Not to Use XML DTD/Schema
XML does not require a DTD/Schema.

When you are experimenting with XML, or when you are working with small XML files, creating DTDs may be a waste of time.

If you develop applications, wait until the specification is stable before you add a document definition. Otherwise, your software might stop working because of validation errors.

---

## 🎭 UI Components & Icons

### 😀 **Emoji Reference**
Emoji codes zijn niet altijd gemakkelijk te onthouden, dus hier is een kleine cheat sheet.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Social media, chat applicaties, user interfaces, notifications

#### People & Faces

##### Happy Faces
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| 😀 | `:smile:` | 😂 | `:joy:` |
| 😄 | `:smiley:` | 😃 | `:grinning:` |
| 😊 | `:blush:` | ☺️ | `:relaxed:` |
| 😆 | `:laughing:` | 😍 | `:heart_eyes:` |
| 😘 | `:kissing_heart:` | 😗 | `:kissing:` |
| 😙 | `:kissing_smiling_eyes:` | 😚 | `:kissing_closed_eyes:` |
| 😋 | `:yum:` | 😛 | `:stuck_out_tongue:` |
| 😜 | `:stuck_out_tongue_winking_eye:` | 😝 | `:stuck_out_tongue_closed_eyes:` |

##### Sad & Worried Faces
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| 😢 | `:cry:` | 😭 | `:sob:` |
| 😔 | `:pensive:` | 😞 | `:disappointed:` |
| 😟 | `:worried:` | 😣 | `:persevere:` |
| 😖 | `:confounded:` | 😫 | `:weary:` |
| 😩 | `:tired_face:` | 😤 | `:triumph:` |
| 😠 | `:angry:` | 😡 | `:rage:` |

##### Hand Gestures
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| 👍 | `:+1:` of `:thumbsup:` | 👎 | `:-1:` of `:thumbsdown:` |
| 👌 | `:ok_hand:` | ✌️ | `:v:` |
| 👋 | `:wave:` | ✋ | `:hand:` of `:raised_hand:` |
| 👏 | `:clap:` | 💪 | `:muscle:` |
| 🙏 | `:pray:` | 👊 | `:punch:` of `:facepunch:` |

#### Symbols & Objects

##### Numbers
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| 1️⃣ | `:one:` | 2️⃣ | `:two:` |
| 3️⃣ | `:three:` | 4️⃣ | `:four:` |
| 5️⃣ | `:five:` | 6️⃣ | `:six:` |
| 7️⃣ | `:seven:` | 8️⃣ | `:eight:` |
| 9️⃣ | `:nine:` | 🔟 | `:keycap_ten:` |
| 0️⃣ | `:zero:` | #️⃣ | `:hash:` |

##### Arrows & Directions
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| ⬅️ | `:arrow_left:` | ➡️ | `:arrow_right:` |
| ⬆️ | `:arrow_up:` | ⬇️ | `:arrow_down:` |
| ↖️ | `:arrow_upper_left:` | ↗️ | `:arrow_upper_right:` |
| ↙️ | `:arrow_lower_left:` | ↘️ | `:arrow_lower_right:` |
| ⏪ | `:rewind:` | ⏩ | `:fast_forward:` |
| 🔄 | `:arrows_clockwise:` | 🔃 | `:arrows_counterclockwise:` |

##### Status & UI Elements
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| ✅ | `:white_check_mark:` | ❌ | `:x:` |
| ⭕ | `:o:` | ❗ | `:exclamation:` |
| ❓ | `:question:` | ⚠️ | `:warning:` |
| 🔴 | `:red_circle:` | 🟢 | `:green_circle:` |
| 🔵 | `:large_blue_circle:` | ⚪ | `:white_circle:` |
| ⚫ | `:black_circle:` | 🔘 | `:radio_button:` |

##### Tech & Objects
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| 💻 | `:computer:` | 📱 | `:iphone:` |
| ⌨️ | `:keyboard:` | 🖱️ | `:computer_mouse:` |
| 📧 | `:email:` | 📨 | `:incoming_envelope:` |
| 📁 | `:file_folder:` | 📂 | `:open_file_folder:` |
| 💾 | `:floppy_disk:` | 💿 | `:cd:` |
| 🔍 | `:mag:` | 🔎 | `:mag_right:` |

#### Nature & Weather
| Emoji | Code | Emoji | Code |
|-------|------|-------|------|
| ☀️ | `:sunny:` | ⛅ | `:partly_sunny:` |
| ☁️ | `:cloud:` | 🌧️ | `:rain_cloud:` |
| ⛈️ | `:thunder_cloud_rain:` | 🌩️ | `:cloud_lightning:` |
| ❄️ | `:snowflake:` | ⛄ | `:snowman:` |
| 🌈 | `:rainbow:` | ⚡ | `:zap:` |

---

### 🔢 **ASCII Codes**
ASCII (American Standard Code for Information Interchange) is een character encoding standaard.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Character encoding, data processing, low-level programming

#### Control Characters (0-31)
| Symbol | Dec | Hex | Description |
|--------|-----|-----|-------------|
| NUL | 0 | 0x00 | Null character |
| SOH | 1 | 0x01 | Start of Heading |
| STX | 2 | 0x02 | Start of Text |
| ETX | 3 | 0x03 | End of Text |
| EOT | 4 | 0x04 | End of Transmission |
| ENQ | 5 | 0x05 | Enquiry |
| ACK | 6 | 0x06 | Acknowledgment |
| BEL | 7 | 0x07 | Bell |
| BS | 8 | 0x08 | Back Space |
| HT | 9 | 0x09 | Horizontal Tab |
| LF | 10 | 0x0A | Line Feed |
| VT | 11 | 0x0B | Vertical Tab |
| FF | 12 | 0x0C | Form Feed |
| CR | 13 | 0x0D | Carriage Return |
| SO | 14 | 0x0E | Shift Out |
| SI | 15 | 0x0F | Shift In |

#### Printable Characters (32-126)
| Symbol | Dec | Hex | Symbol | Dec | Hex |
|--------|-----|-----|--------|-----|-----|
| (Space) | 32 | 0x20 | @ | 64 | 0x40 |
| ! | 33 | 0x21 | A | 65 | 0x41 |
| " | 34 | 0x22 | B | 66 | 0x42 |
| # | 35 | 0x23 | C | 67 | 0x43 |
| $ | 36 | 0x24 | D | 68 | 0x44 |
| % | 37 | 0x25 | E | 69 | 0x45 |
| & | 38 | 0x26 | F | 70 | 0x46 |
| ' | 39 | 0x27 | G | 71 | 0x47 |
| ( | 40 | 0x28 | H | 72 | 0x48 |
| ) | 41 | 0x29 | I | 73 | 0x49 |
| * | 42 | 0x2A | J | 74 | 0x4A |
| + | 43 | 0x2B | K | 75 | 0x4B |
| , | 44 | 0x2C | L | 76 | 0x4C |
| - | 45 | 0x2D | M | 77 | 0x4D |
| . | 46 | 0x2E | N | 78 | 0x4E |
| / | 47 | 0x2F | O | 79 | 0x4F |

#### Numbers (48-57)
| Symbol | Dec | Hex | Symbol | Dec | Hex |
|--------|-----|-----|--------|-----|-----|
| 0 | 48 | 0x30 | 5 | 53 | 0x35 |
| 1 | 49 | 0x31 | 6 | 54 | 0x36 |
| 2 | 50 | 0x32 | 7 | 55 | 0x37 |
| 3 | 51 | 0x33 | 8 | 56 | 0x38 |
| 4 | 52 | 0x34 | 9 | 57 | 0x39 |

#### Uppercase Letters (65-90)
| Symbol | Dec | Hex | Symbol | Dec | Hex |
|--------|-----|-----|--------|-----|-----|
| A | 65 | 0x41 | N | 78 | 0x4E |
| B | 66 | 0x42 | O | 79 | 0x4F |
| C | 67 | 0x43 | P | 80 | 0x50 |
| D | 68 | 0x44 | Q | 81 | 0x51 |
| E | 69 | 0x45 | R | 82 | 0x52 |
| F | 70 | 0x46 | S | 83 | 0x53 |
| G | 71 | 0x47 | T | 84 | 0x54 |
| H | 72 | 0x48 | U | 85 | 0x55 |
| I | 73 | 0x49 | V | 86 | 0x56 |
| J | 74 | 0x4A | W | 87 | 0x57 |
| K | 75 | 0x4B | X | 88 | 0x58 |
| L | 76 | 0x4C | Y | 89 | 0x59 |
| M | 77 | 0x4D | Z | 90 | 0x5A |

#### Lowercase Letters (97-122)
| Symbol | Dec | Hex | Symbol | Dec | Hex |
|--------|-----|-----|--------|-----|-----|
| a | 97 | 0x61 | n | 110 | 0x6E |
| b | 98 | 0x62 | o | 111 | 0x6F |
| c | 99 | 0x63 | p | 112 | 0x70 |
| d | 100 | 0x64 | q | 113 | 0x71 |
| e | 101 | 0x65 | r | 114 | 0x72 |
| f | 102 | 0x66 | s | 115 | 0x73 |
| g | 103 | 0x67 | t | 116 | 0x74 |
| h | 104 | 0x68 | u | 117 | 0x75 |
| i | 105 | 0x69 | v | 118 | 0x76 |
| j | 106 | 0x6A | w | 119 | 0x77 |
| k | 107 | 0x6B | x | 120 | 0x78 |
| l | 108 | 0x6C | y | 121 | 0x79 |
| m | 109 | 0x6D | z | 122 | 0x7A |

#### Special Characters (91-96, 123-126)
| Symbol | Dec | Hex | Description |
|--------|-----|-----|-------------|
| [ | 91 | 0x5B | Left square bracket |
| \ | 92 | 0x5C | Backslash |
| ] | 93 | 0x5D | Right square bracket |
| ^ | 94 | 0x5E | Circumflex accent |
| _ | 95 | 0x5F | Underscore |
| ` | 96 | 0x60 | Grave accent |
| { | 123 | 0x7B | Left curly bracket |
| \| | 124 | 0x7C | Vertical bar |
| } | 125 | 0x7D | Right curly bracket |
| ~ | 126 | 0x7E | Tilde |

---

### 🌐 **HTML Character Entities**
HTML character entities zorgen voor correcte weergave van speciale karakters in HTML.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: HTML development, web content, special character display

#### Essential HTML Entities
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&lt;` | < | `&#60;` | Less than |
| `&gt;` | > | `&#62;` | Greater than |
| `&amp;` | & | `&#38;` | Ampersand |
| `&quot;` | " | `&#34;` | Quotation mark |
| `&apos;` | ' | `&#39;` | Apostrophe |
| `&nbsp;` |   | `&#160;` | Non-breaking space |

#### Mathematical Symbols
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&plus;` | + | `&#43;` | Plus sign |
| `&minus;` | − | `&#8722;` | Minus sign |
| `&times;` | × | `&#215;` | Multiplication |
| `&divide;` | ÷ | `&#247;` | Division |
| `&plusmn;` | ± | `&#177;` | Plus-minus |
| `&frac14;` | ¼ | `&#188;` | One quarter |
| `&frac12;` | ½ | `&#189;` | One half |
| `&frac34;` | ¾ | `&#190;` | Three quarters |

#### Currency Symbols
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&dollar;` | $ | `&#36;` | Dollar sign |
| `&cent;` | ¢ | `&#162;` | Cent sign |
| `&pound;` | £ | `&#163;` | Pound sign |
| `&euro;` | € | `&#8364;` | Euro sign |
| `&yen;` | ¥ | `&#165;` | Yen sign |

#### Arrows & Symbols
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&larr;` | ← | `&#8592;` | Left arrow |
| `&uarr;` | ↑ | `&#8593;` | Up arrow |
| `&rarr;` | → | `&#8594;` | Right arrow |
| `&darr;` | ↓ | `&#8595;` | Down arrow |
| `&harr;` | ↔ | `&#8596;` | Left-right arrow |
| `&crarr;` | ↵ | `&#8629;` | Carriage return |

#### Greek Letters
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&alpha;` | α | `&#945;` | Alpha |
| `&beta;` | β | `&#946;` | Beta |
| `&gamma;` | γ | `&#947;` | Gamma |
| `&delta;` | δ | `&#948;` | Delta |
| `&epsilon;` | ε | `&#949;` | Epsilon |
| `&pi;` | π | `&#960;` | Pi |
| `&sigma;` | σ | `&#963;` | Sigma |
| `&omega;` | ω | `&#969;` | Omega |

#### Accented Characters
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&agrave;` | à | `&#224;` | a with grave |
| `&aacute;` | á | `&#225;` | a with acute |
| `&acirc;` | â | `&#226;` | a with circumflex |
| `&atilde;` | ã | `&#227;` | a with tilde |
| `&auml;` | ä | `&#228;` | a with diaeresis |
| `&aring;` | å | `&#229;` | a with ring above |
| `&ccedil;` | ç | `&#231;` | c with cedilla |
| `&egrave;` | è | `&#232;` | e with grave |
| `&eacute;` | é | `&#233;` | e with acute |
| `&ntilde;` | ñ | `&#241;` | n with tilde |

#### Punctuation & Marks
| HTML Entity | Symbol | Numeric | Description |
|-------------|--------|---------|-------------|
| `&lsquo;` | ' | `&#8216;` | Left single quote |
| `&rsquo;` | ' | `&#8217;` | Right single quote |
| `&ldquo;` | " | `&#8220;` | Left double quote |
| `&rdquo;` | " | `&#8221;` | Right double quote |
| `&ndash;` | – | `&#8211;` | En dash |
| `&mdash;` | — | `&#8212;` | Em dash |
| `&hellip;` | … | `&#8230;` | Horizontal ellipsis |
| `&copy;` | © | `&#169;` | Copyright |
| `&reg;` | ® | `&#174;` | Registered trademark |
| `&trade;` | ™ | `&#8482;` | Trademark |

---

## 🔐 **Security & Authentication**

### 🌐 **CORS - Cross-Origin Resource Sharing**
CORS is een security mechanisme dat browsers beschermt tegen ongeautoriseerde cross-origin requests.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Web security, API access control, browser compliance

#### CORS Headers
```javascript
// Allow specific origin
Access-Control-Allow-Origin: https://example.com

// Allow credentials
Access-Control-Allow-Credentials: true

// Allow specific methods
Access-Control-Allow-Methods: GET, POST, PUT, DELETE

// Allow specific headers
Access-Control-Allow-Headers: Content-Type, Authorization

// Preflight cache time
Access-Control-Max-Age: 86400
```

#### Express.js CORS Setup
```javascript
const cors = require('cors');

// Basic CORS
app.use(cors());

// Custom CORS configuration
app.use(cors({
  origin: ['https://example.com', 'https://app.example.com'],
  credentials: true,
  methods: ['GET', 'POST', 'PUT', 'DELETE'],
  allowedHeaders: ['Content-Type', 'Authorization']
}));
```

---

### 🔒 **File Permissions (chmod)**
chmod controleert wie bestanden kan lezen, schrijven of uitvoeren in Unix/Linux systemen.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Server security, file system management, deployment

#### Permission Numbers
| Number | Permission | Description |
|--------|------------|-------------|
| 0 | --- | No permissions |
| 1 | --x | Execute only |
| 2 | -w- | Write only |
| 3 | -wx | Write and execute |
| 4 | r-- | Read only |
| 5 | r-x | Read and execute |
| 6 | rw- | Read and write |
| 7 | rwx | Read, write, and execute |

#### Common Commands
```bash
# Make file executable
chmod +x script.sh

# Set specific permissions (owner/group/others)
chmod 755 file.txt    # rwxr-xr-x
chmod 644 file.txt    # rw-r--r--
chmod 600 file.txt    # rw-------

# Recursive permissions
chmod -R 755 directory/

# Change ownership
chown user:group file.txt
chown -R user:group directory/
```

---

### 📝 **Conventional Commits**
Conventional Commits is een standaard voor commit messages die automatisering en changelog generation mogelijk maakt.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Version control, automated releases, code documentation

#### Commit Message Format
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Common Types
| Type | Description |
|------|-------------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation changes |
| `style` | Code style changes (formatting) |
| `refactor` | Code refactoring |
| `test` | Adding/updating tests |
| `chore` | Maintenance tasks |
| `ci` | CI/CD changes |
| `perf` | Performance improvements |
| `build` | Build system changes |

#### Examples
```bash
git commit -m "feat: add user authentication"
git commit -m "fix(api): resolve cors issue with login endpoint"
git commit -m "docs: update README with installation steps"
git commit -m "style: format code with prettier"
git commit -m "feat!: change user model structure"  # Breaking change
```

---

## 📦 **Package Management & Deployment**

### 📋 **package.json**
package.json is het configuratiebestand voor Node.js projecten dat dependencies en scripts definieert.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Node.js projects, dependency management, script automation

#### Basic Structure
```json
{
  "name": "my-project",
  "version": "1.0.0",
  "description": "My awesome project",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js",
    "build": "webpack --mode production",
    "test": "jest",
    "lint": "eslint src/",
    "format": "prettier --write src/"
  },
  "dependencies": {
    "express": "^4.18.0",
    "react": "^18.0.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.0",
    "jest": "^28.0.0"
  },
  "engines": {
    "node": ">=16.0.0",
    "npm": ">=7.0.0"
  }
}
```

#### Important Fields
| Field | Description |
|-------|-------------|
| `name` | Package name (required) |
| `version` | Semantic version (required) |
| `main` | Entry point file |
| `scripts` | Executable commands |
| `dependencies` | Production dependencies |
| `devDependencies` | Development-only dependencies |
| `peerDependencies` | Expected to be provided |
| `engines` | Required Node/npm versions |

---

## 🗂️ **Project Structure & Architecture**

### 🎯 **JavaScript Patterns**
Veelgebruikte design patterns en architectuur patronen in JavaScript development.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Code organization, maintainability, scalability

#### Module Pattern
```javascript
// IIFE Module Pattern
const MyModule = (function() {
  let privateVar = 0;
  
  function privateFunction() {
    console.log('Private function called');
  }
  
  return {
    publicMethod() {
      privateVar++;
      return privateVar;
    },
    
    getCount() {
      return privateVar;
    }
  };
})();
```

#### Observer Pattern
```javascript
class EventEmitter {
  constructor() {
    this.events = {};
  }
  
  on(event, callback) {
    if (!this.events[event]) {
      this.events[event] = [];
    }
    this.events[event].push(callback);
  }
  
  emit(event, data) {
    if (this.events[event]) {
      this.events[event].forEach(callback => callback(data));
    }
  }
  
  off(event, callback) {
    if (this.events[event]) {
      this.events[event] = this.events[event].filter(cb => cb !== callback);
    }
  }
}
```

#### Singleton Pattern
```javascript
class Database {
  constructor() {
    if (Database.instance) {
      return Database.instance;
    }
    
    this.connection = null;
    Database.instance = this;
  }
  
  connect() {
    if (!this.connection) {
      this.connection = 'Connected to database';
    }
    return this.connection;
  }
}

const db1 = new Database();
const db2 = new Database();
console.log(db1 === db2); // true
```

---

### 📐 **Aspect Ratios**
Standaard aspect ratios voor design en media content.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Responsive design, media content, UI layouts

#### Common Aspect Ratios
| Ratio | Decimal | Usage |
|-------|---------|-------|
| 1:1 | 1.000 | Square, social media posts |
| 4:3 | 1.333 | Classic TV, presentations |
| 3:2 | 1.500 | Traditional photography |
| 16:10 | 1.600 | Widescreen monitors |
| 5:3 | 1.667 | Medium format photography |
| 16:9 | 1.778 | HD video, modern displays |
| 21:9 | 2.333 | Ultrawide monitors |
| 2.35:1 | 2.350 | Widescreen cinema |

#### CSS Implementation
```css
/* Aspect ratio with CSS */
.aspect-ratio-16-9 {
  aspect-ratio: 16 / 9;
}

/* Fallback for older browsers */
.aspect-ratio-16-9-fallback {
  position: relative;
  padding-bottom: 56.25%; /* 9/16 * 100% */
  height: 0;
  overflow: hidden;
}

.aspect-ratio-16-9-fallback > * {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
```

---

### 🖥️ **Screen Resolutions**
Overzicht van gangbare schermresoluties voor responsive design.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Responsive design, media queries, device testing

#### Common Breakpoints
| Device | Width | Height | Ratio | Usage |
|--------|-------|--------|-------|-------|
| Mobile (Small) | 320px | 568px | 16:9 | iPhone SE |
| Mobile (Medium) | 375px | 667px | 16:9 | iPhone 8 |
| Mobile (Large) | 414px | 896px | 19.5:9 | iPhone 11 |
| Tablet (Portrait) | 768px | 1024px | 4:3 | iPad |
| Tablet (Landscape) | 1024px | 768px | 4:3 | iPad |
| Laptop | 1366px | 768px | 16:9 | Common laptop |
| Desktop | 1920px | 1080px | 16:9 | Full HD |
| 4K | 3840px | 2160px | 16:9 | Ultra HD |

#### CSS Media Queries
```css
/* Mobile first approach */
/* Base styles for mobile */

@media (min-width: 480px) {
  /* Large mobile styles */
}

@media (min-width: 768px) {
  /* Tablet styles */
}

@media (min-width: 1024px) {
  /* Desktop styles */
}

@media (min-width: 1440px) {
  /* Large desktop styles */
}
```

---

## 🖥️ **Operating Systems & Tools**

### ⊞ **Windows Shortcuts**
Essentiële Windows toetsenbordsnelkoppelingen voor productiviteit.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: Windows productivity, system navigation, workflow optimization

#### System Shortcuts
| Shortcut | Action |
|----------|--------|
| `Win` | Open Start menu |
| `Win` + `D` | Show desktop |
| `Win` + `L` | Lock computer |
| `Win` + `R` | Run dialog |
| `Win` + `X` | Power user menu |
| `Win` + `I` | Settings |
| `Win` + `E` | File Explorer |
| `Win` + `S` | Search |
| `Alt` + `Tab` | Switch between apps |
| `Ctrl` + `Shift` + `Esc` | Task Manager |

#### Window Management
| Shortcut | Action |
|----------|--------|
| `Win` + `Left/Right` | Snap window to side |
| `Win` + `Up` | Maximize window |
| `Win` + `Down` | Minimize/restore window |
| `Win` + `Shift` + `Left/Right` | Move window between monitors |
| `Alt` + `F4` | Close active window |
| `Win` + `M` | Minimize all windows |

---

### 💻 **PowerShell**
PowerShell commands voor Windows system administration en automation.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Windows automation, system administration, scripting

#### Basic Commands
```powershell
# Navigation
Get-Location          # Current directory (like pwd)
Set-Location C:\      # Change directory (like cd)
Get-ChildItem         # List files (like ls)

# File operations
Copy-Item source dest # Copy file
Move-Item source dest # Move file
Remove-Item file      # Delete file
New-Item -Type File   # Create file

# System information
Get-Process           # Running processes
Get-Service           # System services
Get-ComputerInfo      # System information
```

---

### 🐧 **Ubuntu Commands**
Essentiële Ubuntu/Linux commando's voor server management.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Linux server management, system administration

#### Package Management
```bash
# Update package list
sudo apt update

# Upgrade packages
sudo apt upgrade

# Install package
sudo apt install package-name

# Remove package
sudo apt remove package-name

# Search for package
apt search package-name
```

#### System Management
```bash
# System information
uname -a              # System info
df -h                 # Disk usage
free -h               # Memory usage
top                   # Running processes
ps aux                # Process list

# Services
sudo systemctl start service-name
sudo systemctl stop service-name
sudo systemctl restart service-name
sudo systemctl status service-name
```

---

### ⏰ **Cron Jobs**
Cron syntax voor het plannen van geautomatiseerde taken in Unix/Linux.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Task automation, scheduled backups, system maintenance

#### Cron Syntax
```
* * * * * command
│ │ │ │ │
│ │ │ │ └─── Day of week (0-7, Sunday = 0 or 7)
│ │ │ └───── Month (1-12)
│ │ └─────── Day of month (1-31)
│ └───────── Hour (0-23)
└─────────── Minute (0-59)
```

#### Common Examples
```bash
# Every minute
* * * * * /path/to/command

# Every day at 2:30 AM
30 2 * * * /path/to/backup.sh

# Every Monday at 9 AM
0 9 * * 1 /path/to/weekly-task.sh

# First day of every month at midnight
0 0 1 * * /path/to/monthly-task.sh

# Every 5 minutes
*/5 * * * * /path/to/frequent-task.sh
```

---

## 🔍 **Search & Navigation**

### 🎯 **XPath**
XPath syntax voor het selecteren van XML/HTML elementen.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Web scraping, automated testing, data extraction

#### Basic Syntax
```xpath
// Basic selectors
/html/body/div           # Absolute path
//div                    # All div elements
//div[@class='example']  # Div with specific class
//div[1]                 # First div element
//div[last()]            # Last div element

// Attribute selectors
//*[@id='myId']          # Element with specific ID
//input[@type='text']    # Input with type text
//a[@href]               # Links with href attribute

// Text selectors
//div[text()='Hello']    # Div containing exact text
//div[contains(text(), 'Hello')] # Div containing text
```

---

### 🔍 **Find Command**
Unix find command voor het zoeken naar bestanden en directories.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: File management, system administration, automation

#### Basic Usage
```bash
# Find by name
find /path -name "*.txt"
find . -name "config*"

# Find by type
find /path -type f        # Files only
find /path -type d        # Directories only

# Find by size
find /path -size +100M    # Larger than 100MB
find /path -size -1K      # Smaller than 1KB

# Find by time
find /path -mtime -7      # Modified in last 7 days
find /path -atime +30     # Accessed more than 30 days ago

# Execute command on results
find /path -name "*.log" -delete
find /path -name "*.txt" -exec grep "pattern" {} \;
```

---

## 🤖 **AI & Automation**

### 🧠 **AI Tools**
Een uitgebreide directory van AI tools georganiseerd per categorie voor verschillende toepassingen.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: AI-powered productivity, content creation, development assistance

#### Health & Fitness AI Tools
- **[Buoy Health](https://buoyhealth.com)** - AI-powered health assistant
- **[MDacne](https://mdacne.com)** - Skin analysis and acne treatment
- **[Youper](https://youper.ai)** - Emotional health assistant
- **[Endel](https://endel.io/sleep)** - AI-generated soundscapes for sleep
- **[Dialogue](https://nowdialogue.com)** - Mental health support
- **[Maslo AI](https://maslo.ai)** - Companion for mental wellness

#### Text Processing & Writing
- **[Quillbot](https://quillbot.com)** - Paraphrasing and grammar checking
- **[Notion AI](https://notion.so/product/ai)** - AI-powered workspace assistant
- **[NaturalReader](https://naturalreaders.com)** - Text-to-speech conversion
- **[Wordtune Read](https://wordtune.com/read)** - AI reading assistant
- **[Uberduck](https://uberduck.ai)** - AI voice synthesis
- **[AISEO Slogan Generator](https://aiseo.ai/templates/slogan-generator.html)** - Marketing slogan creation

#### Image Editing & Generation
- **[Remove.bg](https://remove.bg)** - Automatic background removal
- **[Picsart Tools](https://tools.picsart.com/image)** - Quick image editing tools
- **[BeFunky](https://befunky.com)** - Online photo editor
- **[Topaz Photo AI](https://topazlabs.com/topaz-photo-ai)** - AI photo enhancement
- **[PhotoRoom](https://photoroom.com)** - Product photo editing
- **[Erase.bg](https://erase.bg)** - Background eraser

#### Developer Tools
- **[OpenAI for Coda](https://coda.io/@coda/openai-for-coda)** - GPT integration for Coda
- **[Nanonets OCR](https://case-study-page-nanonets.webflow.io/ocr-api)** - Optical character recognition
- **[Google AI](https://ai.google)** - Google's AI platform
- **[AssemblyAI](https://assemblyai.com)** - Speech-to-text API
- **[HTTPie AI](https://httpie.io)** - API testing with AI
- **[RunPod](https://runpod.io)** - Cloud GPU for AI workloads

#### Code Assistants
- **[Ghostwriter](https://replit.com/site/ghostwriter)** - Replit's AI coding assistant
- **[Fig AI](https://fig.io/user-manual/ai)** - Terminal autocomplete
- **[Continual](https://continual.ai)** - Operational AI platform
- **[Cheat Layer](https://cheatlayer.com)** - No-code automation
- **[Kodezi AI](https://kodezi.com)** - Code debugging assistant
- **[WhatTheDiff](https://whatthediff.ai)** - AI-powered code review

#### Creative & Design Tools
- **[DALL-E](https://openai.com/blog/dall-e)** - AI image generation
- **[Midjourney](https://midjourney.com)** - AI art generator
- **[Looka](https://looka.com)** - Logo and brand design
- **[Cartoonify](https://kapwing.com/cartoonify)** - Photo to cartoon converter
- **[Smart Upscaler](https://icons8.com/upscaler)** - AI image upscaling

#### Music & Audio
- **[MuseNet](https://openai.com/blog/musenet)** - AI music composition
- **[Moises App](https://moises.ai)** - Music separation and remixing
- **[Soundraw](https://soundraw.io)** - AI music generator
- **[AI Lyrics Generator](https://theselyricsdonotexist.com)** - Generate song lyrics
- **[PhonicMind](https://phonicmind.com)** - Vocal and instrument isolation

#### Video Editing
- **[Wave.video](https://wave.video)** - Online video editor
- **[Topaz Video AI](https://topazlabs.com/topaz-video-ai)** - Video enhancement
- **[Unscreen](https://unscreen.com)** - Remove video backgrounds
- **[Pictory](https://pictory.ai)** - Video creation from text
- **[Type Studio](https://typestudio.co/tool/video-to-text)** - Video transcription
- **[Papercup](https://papercup.com)** - AI dubbing

---

## 📱 **Mobile Development**

### 📱 **ADB (Android Debug Bridge)**
ADB is een veelzijdig command-line tool voor communicatie met Android devices.

🟡 **Moeilijkheidsgraad**: Medium  
**📊 Gebruik**: Android debugging, app testing, device management

#### Device Basics
| Command | Description |
|---------|-------------|
| `adb devices` | Lists connected devices |
| `adb devices -l` | Lists connected devices and kind |
| `adb root` | Restarts adbd with root permissions |
| `adb start-server` | Starts the adb server |
| `adb kill-server` | Kills the adb server |
| `adb remount` | Remounts file system with read/write access |
| `adb reboot` | Reboots the device |
| `adb reboot bootloader` | Reboots the device into fastboot |

#### Multiple Devices
```bash
# Wait for device connection
adb wait-for-device devices

# Target specific device
adb -s device-id root
adb -s emulator-5554 install app.apk
```

#### Logcat
| Command | Description |
|---------|-------------|
| `adb logcat` | Starts printing log messages |
| `adb logcat -g` | Displays current log buffer sizes |
| `adb logcat -G 16M` | Sets the buffer size |
| `adb logcat -c` | Clears the log buffers |
| `adb logcat *:V` | Enables ALL log messages (verbose) |
| `adb logcat -f filename` | Dumps to specified file |

```bash
# Filter by tag and priority
adb logcat ActivityManager:I MyApp:D *:S

# Save logs with timestamp
adb logcat -v time > myapp.log
```

#### File Management
```bash
# Push file to device
adb push local-file.txt /sdcard/
adb push myapp.apk /data/local/tmp/

# Pull file from device
adb pull /sdcard/screenshot.png
adb pull /data/data/com.example.app/databases/
```

#### Package Management
```bash
# Install APK
adb install myapp.apk
adb install -r myapp.apk  # Reinstall, keeping data

# Uninstall package
adb uninstall com.example.app
adb uninstall -k com.example.app  # Keep data

# List packages
adb shell pm list packages
adb shell pm list packages -3  # Third-party only
adb shell pm list packages -s  # System only
```

#### Remote Shell
```bash
# Open shell
adb shell

# Run command
adb shell ls /sdcard/
adb shell dumpsys battery
adb shell getprop ro.build.version.release

# Screen resolution
adb shell wm size
adb shell wm size 1080x1920
adb shell wm size reset

# Take screenshot
adb shell screencap /sdcard/screenshot.png
adb pull /sdcard/screenshot.png

# Record screen
adb shell screenrecord /sdcard/demo.mp4
adb shell screenrecord --time-limit 30 /sdcard/demo.mp4
```

#### App Testing
```bash
# Start activity
adb shell am start -n com.example.app/.MainActivity

# Send broadcast
adb shell am broadcast -a android.intent.action.BOOT_COMPLETED

# Start service
adb shell am startservice com.example.app/.MyService

# Force stop app
adb shell am force-stop com.example.app

# Clear app data
adb shell pm clear com.example.app
```

#### Networking
```bash
# Port forwarding
adb forward tcp:8080 tcp:8080

# Reverse port forwarding
adb reverse tcp:3000 tcp:3000

# Connect over WiFi
adb tcpip 5555
adb connect device-ip:5555
```

---

## 🌍 **Internationalization**

### 🌐 **ISO 639-1 Language Codes**
Standaard twee-letter codes voor taalidentificatie in internationale applicaties.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: i18n/l10n, multi-language websites, language selection

#### Common Language Codes
| Code | Language | Native Name |
|------|----------|-------------|
| `en` | English | English |
| `es` | Spanish | Español |
| `fr` | French | Français |
| `de` | German | Deutsch |
| `it` | Italian | Italiano |
| `pt` | Portuguese | Português |
| `ru` | Russian | Русский |
| `ja` | Japanese | 日本語 |
| `ko` | Korean | 한국어 |
| `zh` | Chinese | 中文 |
| `ar` | Arabic | العربية |
| `hi` | Hindi | हिन्दी |
| `nl` | Dutch | Nederlands |
| `sv` | Swedish | Svenska |
| `pl` | Polish | Polski |
| `tr` | Turkish | Türkçe |
| `vi` | Vietnamese | Tiếng Việt |
| `th` | Thai | ไทย |
| `el` | Greek | Ελληνικά |
| `he` | Hebrew | עברית |

#### Usage in HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Multi-language Site</title>
</head>
<body>
    <!-- Language switcher -->
    <select id="language-selector">
        <option value="en">English</option>
        <option value="es">Español</option>
        <option value="fr">Français</option>
    </select>
    
    <!-- Content with lang attributes -->
    <p lang="en">Hello World</p>
    <p lang="es">Hola Mundo</p>
    <p lang="fr">Bonjour le monde</p>
</body>
</html>
```

#### Usage in JavaScript
```javascript
// Browser language detection
const userLang = navigator.language || navigator.userLanguage; // "en-US"
const langCode = userLang.split('-')[0]; // "en"

// i18n object structure
const translations = {
    en: {
        welcome: "Welcome",
        goodbye: "Goodbye"
    },
    es: {
        welcome: "Bienvenido",
        goodbye: "Adiós"
    },
    fr: {
        welcome: "Bienvenue",
        goodbye: "Au revoir"
    }
};

// Get translation
function t(key, lang = 'en') {
    return translations[lang]?.[key] || translations.en[key];
}
```

---

### 📄 **MIME Types**
Media types voor het identificeren van bestandsformaten op het web.

🟢 **Moeilijkheidsgraad**: Easy  
**📊 Gebruik**: File uploads, content negotiation, HTTP headers

#### Common Web MIME Types
| Extension | MIME Type | Description |
|-----------|-----------|-------------|
| `.html` | `text/html` | HTML document |
| `.css` | `text/css` | CSS stylesheet |
| `.js` | `text/javascript` | JavaScript file |
| `.json` | `application/json` | JSON data |
| `.xml` | `application/xml` | XML document |
| `.txt` | `text/plain` | Plain text |

#### Image MIME Types
| Extension | MIME Type | Description |
|-----------|-----------|-------------|
| `.jpg` `.jpeg` | `image/jpeg` | JPEG image |
| `.png` | `image/png` | PNG image |
| `.gif` | `image/gif` | GIF image |
| `.webp` | `image/webp` | WebP image |
| `.svg` | `image/svg+xml` | SVG vector image |
| `.ico` | `image/x-icon` | Icon file |

#### Audio/Video MIME Types
| Extension | MIME Type | Description |
|-----------|-----------|-------------|
| `.mp3` | `audio/mpeg` | MP3 audio |
| `.wav` | `audio/wav` | WAV audio |
| `.ogg` | `audio/ogg` | OGG audio |
| `.mp4` | `video/mp4` | MP4 video |
| `.webm` | `video/webm` | WebM video |
| `.avi` | `video/x-msvideo` | AVI video |

#### Document MIME Types
| Extension | MIME Type | Description |
|-----------|-----------|-------------|
| `.pdf` | `application/pdf` | PDF document |
| `.doc` | `application/msword` | MS Word |
| `.docx` | `application/vnd.openxmlformats-officedocument.wordprocessingml.document` | MS Word (OpenXML) |
| `.xls` | `application/vnd.ms-excel` | MS Excel |
| `.xlsx` | `application/vnd.openxmlformats-officedocument.spreadsheetml.sheet` | MS Excel (OpenXML) |
| `.ppt` | `application/vnd.ms-powerpoint` | MS PowerPoint |

#### Archive MIME Types
| Extension | MIME Type | Description |
|-----------|-----------|-------------|
| `.zip` | `application/zip` | ZIP archive |
| `.rar` | `application/x-rar-compressed` | RAR archive |
| `.tar` | `application/x-tar` | TAR archive |
| `.gz` | `application/gzip` | GZIP compressed |
| `.7z` | `application/x-7z-compressed` | 7-Zip archive |

#### Usage Examples
```javascript
// File upload validation
function validateFileType(file) {
    const allowedTypes = [
        'image/jpeg',
        'image/png',
        'image/gif',
        'application/pdf'
    ];
    
    return allowedTypes.includes(file.type);
}

// Setting response headers
response.setHeader('Content-Type', 'application/json; charset=utf-8');

// HTML file input
<input type="file" accept="image/png, image/jpeg, application/pdf" />

// Fetch with correct content type
fetch('/api/data', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json'
    },
    body: JSON.stringify(data)
});
```

#### Creating Data URLs
```javascript
// Convert file to data URL
function fileToDataURL(file) {
    return new Promise((resolve, reject) => {
        const reader = new FileReader();
        reader.onload = e => resolve(e.target.result);
        reader.onerror = reject;
        reader.readAsDataURL(file);
    });
}

// Create blob with MIME type
const jsonBlob = new Blob([JSON.stringify(data)], {
    type: 'application/json'
});

// Download file with correct MIME
function downloadFile(content, filename, mimeType) {
    const blob = new Blob([content], { type: mimeType });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = filename;
    a.click();
    URL.revokeObjectURL(url);
}
```

---

## 🎉 **Einde van Combined Cheatsheet**

Dit document bevat een uitgebreide verzameling van moderne web development technologieën. Voor de meest recente informatie en updates, raadpleeg altijd de officiële documentatie van elke technologie.

**Happy Coding! 🚀**
