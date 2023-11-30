# Learning_linux
all commands and scripts
awk - awk '{print NR,$1,$2,$5}' trace.text | head
      awk '{print NR,$1,$2,$5}' trace.text | tail
      awk '{print NR,$1,$2,$5}' trace.text > new_file_name (to save in the new file)
      wk  'NR>2 && NR<5 {print NR,$1,$2,$5}' trace.text | head (to print between no or rows)
      wk  'NR>2 && NR<5 && /INFO/ {print NR,$1,$2,$5}' trace.text | head (to print between no or rows)  (info will not be printed but rows which have info will be printed)
for_time       
       awk '$2 >"08:52:51" && $2<"08:54:51" {print NR,$1,$2,$5}' trace.text
