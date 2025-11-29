# WishShell – Custom Unix Shell

A lightweight command-line interpreter implementing core Unix shell behaviors with extended custom utilities.

---

##  Team Members

- **Samantha W** (23PW25)  
- **Sri Pooja S** (23PW31)

---

##  Overview  

WishShell is a custom Unix shell developed in C that supports command parsing, execution, and process management.  
It can run in two modes:

- **Interactive Mode:** users enter commands manually  
- **Batch Mode:** commands are executed from a script file  

The shell supports built-in commands (`cd`, `exit`, `path`), output redirection using `>`, and parallel execution with `&`.  
System calls such as `fork()`, `execv()`, and `waitpid()` enable process creation and external command execution.

In addition to standard shell behavior, wish++ includes extended custom utilities such as duplicate file detection, network status checks, file cleanup tools, reminders, and a todo-list—making the shell more functional and modular.

---

##  Features

###  Core Shell Capabilities
- Built-in commands:  
  - `exit` — terminate shell  
  - `cd` — change directory  
  - `path` — configure executable search paths  
- Output redirection: `>`  
- Parallel command execution: `&`  
- Batch and interactive execution  
- Command parsing and structured error handling

###  Custom Utility Commands
| Command | Purpose |
|--------|---------|
| `dupfinder` | Detect duplicate files in a directory |
| `netstatus` | Display internet status, public IP, and network latency |
| `wcleanup` | Remove unnecessary whitespace and format files |
| `todocli` | Manage a basic task list (add/list/remove) |
| `remindme` | Set reminders based on time delay |

---

##  Conclusion

WishShell demonstrates how operating system concepts like process management, system calls, I/O redirection, and command parsing are used to build a functioning shell environment.  
With additional custom utilities, it extends beyond basic execution and showcases how shell environments can be enhanced and personalized for real-world use.

---

