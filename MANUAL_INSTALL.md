This Is Manual Install Openpilot Guide

# 1. launch_openpilot.sh
```bash
cd /data/openpilot
./launch_openpilot.sh 
```

# 2.  create continue.sh file (this may take sometime)
```bash
cat > /data/data/com.termux/files/continue.sh << 'EOF'
#!/usr/bin/bash
cd /data/openpilot
./launch_openpilot.sh
EOF
```
# 3. reboot
