# Auto-runner-for-zed
How to run python program with keyboard shortcut in Zed<br>
- Open zed<br>
- press f1<br>
- search tasks and open it<br>
- paste : (delete evrything in tasks.josn file if you are opening that for the first time ! )<br>
  [<br>
  {<br>
    "label": "r/python",<br>
    "command": "python3",<br>
    "args": ["\"$ZED_FILE\""],<br>
    "use_new_terminal": false,<br>
    "allow_concurrent_runs": true,<br>
  },<br>
]<br>
-again press f1 and search keymap file and open it.<br>
-add this uder binding in workspace<br>
"ctrl-r": ["task::Spawn", { "task_name": "r/python" }]<br>
-now write a python program and run it using CTRL + R and Enjoy!<br>

