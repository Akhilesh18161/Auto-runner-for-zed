# Auto-runner-for-zed
How to run python program with keyboard shortcut in Zed
- Open zed
- press f1
- search tasks and open it
- paste : (delete evrything in tasks.josn file if you are opening that for the first time ! )
  [
  {
    "label": "r/python",
    "command": "python3",
    "args": ["\"$ZED_FILE\""],
    "use_new_terminal": false,
    "allow_concurrent_runs": true,
  },
]
-again press f1 and search keymap file and open it.
-add this uder binding in workspace
"ctrl-r": ["task::Spawn", { "task_name": "r/python" }]
-now write a python program and run it using CTRL + R and Enjoy!

