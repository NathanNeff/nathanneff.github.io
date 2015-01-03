---
layout: default
title: Tmux
---

# Tmux

## Basic Keybindings

      Key | Purpose
    ---------------------------
        A | command-prompt "rename-window %%"
        ? | list-keys
      C-a | last-window
    Space | next-layout
      C-o | rotate-window
      C-z | suspend-client
      0-9 | select-window 0-9

## Panes

        Key | Purpose
       -------------------------
          ! | break-pane
          " | split-window
          # | list-buffers
          $ | command-prompt -I #S "rename-session '%%'"
          % | split-window -h
          & | confirm-before -p "kill-window #W? (y/n)" kill-window
          ' | command-prompt "find-window %%"
          ( | switch-client -p
          ) | switch-client -n
          , | command-prompt -I #W "rename-window '%%'"
          - | split-window -v
          . | command-prompt "move-window -t '%%'"
          / | command-prompt "split-window 'exec man %%'"
          : | command-prompt
          ; | last-pane
          = | choose-buffer
          D | choose-client
          L | switch-client -l
          S | command-prompt "new-window -n %1 'ssh %1'"
          [ | copy-mode
          ] | paste-buffer
          b | set-option status
          c | new-window
          d | detach-client
          f | command-prompt "find-window '%%'"
          h | select-pane -L
          i | display-message
          j | select-pane -D
          k | select-pane -U
          l | select-pane -R
          n | next-window
          o | select-pane -t :.+
          p | previous-window
          q | display-panes
          r | source-file /Users/nathan/.tmux.conf
          s | choose-tree
          t | clock-mode
          w | choose-window
          x | confirm-before -p "kill-pane #P? (y/n)" kill-pane
          z | resize-pane -Z
          { | swap-pane -U
          | | split-window -h
          } | swap-pane -D
          ~ | show-messages
      PPage | copy-mode -u
         Up | select-pane -U
       Down | select-pane -D
       Left | select-pane -L
      Right | select-pane -R
        M-1 | select-layout even-horizontal
        M-2 | select-layout even-vertical
        M-3 | select-layout main-horizontal
        M-4 | select-layout main-vertical
        M-5 | select-layout tiled
        M-n | next-window -a
        M-o | rotate-window -D
        M-p | previous-window -a
       C-Up | resize-pane -U
     C-Down | resize-pane -D
     C-Left | resize-pane -L
    C-Right | resize-pane -R
