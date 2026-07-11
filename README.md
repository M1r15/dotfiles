# dotfiles
My configuration files

These custom Zsh functions allow you to dynamically track your target and attacker IP addresses directly on the Tmux status bar in real-time.

### Commands

*   **Set Target IP (RHOST):**
    ```bash
    settarget <ip_address>
    ```
*   **Set Attacker IP (LHOST):**
    ```bash
    setattacker <ip_address>
    ```
*   **Clear IPs:**
    ```bash
    donectf
    ```
>   Running `donectf` instantly resets the status bar indicators back to `No IP`
---

![Terminal Preview](tmux.png)
