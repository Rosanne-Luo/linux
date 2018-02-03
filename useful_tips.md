1.虚拟机里ubuntu系统的vi工具的方向键和退格键不能正常使用？

将 /etc/vim/vimrc.tiny 文件中的 "set compatible" 改为 "set nocompatible"，并添加 "set backspace=2"
