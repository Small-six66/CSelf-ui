#!/usr/bin/env sh
# 寻找npm安装位置 正常如下
#PATH="/usr/local/bin:$PATH"
# 寻找npm安装位置 mac 使用了volta 特例 忽略这个
#PATH="/Users/yaw/.volta/bin/:$PATH"
. "$(dirname -- "$0")/_/husky.sh"

npx --no-install commitlint --edit $1
