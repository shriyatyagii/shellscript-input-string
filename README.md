# shellscript-input-string
Shell Script-1

#!/bin/sh
INPUT_STRING=hello
while [ "$INPUT_STRING" != "bye" ]
do
  echo "Please type something in (type bye to quit)"
  read INPUT_STRING
  echo "You typed: $INPUT_STRING"
done
