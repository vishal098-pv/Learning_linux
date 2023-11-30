# Learning_linux
all commands and scripts
awk - awk '{print NR,$1,$2,$5}' trace.text | head
      awk '{print NR,$1,$2,$5}' trace.text | tail
      awk '{print NR,$1,$2,$5}' trace.text > new_file_name (to save in the new file)
      wk  'NR>2 && NR<5 {print NR,$1,$2,$5}' trace.text | head (to print between no or rows)
      
