# ftraceData
ext4 file operations route captured by ftrace tool

ftrace_ext4_writev, ftrace_ftruncate, ftrace_lseek and ftrace_write is captured with DAX off, I'm not sure about other files, most probolely they are also with DAX off.