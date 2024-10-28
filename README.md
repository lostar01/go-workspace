# go-workspace

```
# Install devpod
wget https://github.com/loft-sh/devpod/releases/download/v0.5.21/devpod-linux-amd64
mv devpod-linux-amd64 /usr/local/bin/devpod
chmod a+x /usr/local/bin/devpod

# 自动保存git凭证
git config --global credential.helper store

# 可在/tmp目录下选clone一下，输入凭证
git clone https://github.com/lostar01/go-workspace.git

# 启动
devpod up https://github.com/lostar01/go-workspace.git --ide=none --id=zack-go-workspace

```
