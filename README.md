- 👋 Hi, I’m @sabariredhat
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sabariredhat/sabariredhat is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
facing issue during devstack installation on centos 7.6

+functions-common:restart_service:2309     '[' -x /bin/systemctl ']'
+**functions-common:restart_service:2310     sudo /bin/systemctl restart httpd
Job for httpd.service failed because the control process exited with error code. See "systemctl status httpd.service" and "journalctl -xe" for details**.
+functions-common:restart_service:1        exit_trap
+stack.sh:exit_trap:521                    local r=1
++stack.sh:exit_trap:522                    jobs -p
+stack.sh:exit_trap:522                    jobs=
+stack.sh:exit_trap:525                    [[ -n '' ]]
+stack.sh:exit_trap:531                    '[' -f '' ']'
+stack.sh:exit_trap:536                    kill_spinner
+stack.sh:kill_spinner:431                 '[' '!' -z '' ']'
+stack.sh:exit_trap:538                    [[ 1 -ne 0 ]]
+stack.sh:exit_trap:539                    echo 'Error on exit'
Error on exit
+stack.sh:exit_trap:541                    type -p generate-subunit
+stack.sh:exit_trap:542                    generate-subunit 1649335749 78 fail
+stack.sh:exit_trap:544                    [[ -z /opt/stack/logs ]]
+stack.sh:exit_trap:547                    /bin/python3.6 /opt/stack/devstack/tools/worlddump.py -d /opt/stack/logs
+stack.sh:exit_trap:556                    exit 1
[stack@controller devstack]$
