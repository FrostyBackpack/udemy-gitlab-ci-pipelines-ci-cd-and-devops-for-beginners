# Your First Pipeline

Build ---> Test

.gitlab-ci.yml file is used to define a pipeline.

YAML (YAML Ain't Markup Language) is a human friendly data serialization standard for all programming languages.

We need to specify a job (Job is a task GitLab should do for us)

- touch [filename]
-> The touch command is a very simple way to create new, empty files.

- echo "[name]" > [txt file]
-> The echo command is used to display line of text/string.
-> With the greater-than operator ">", the output from the echo command will be redirected a file (car.txt)
-> If the file already exists, it will be deleted.

- The GitLab Runner is the tool used by GitLab to run your jobs and send the results back to GitLab.

- grep "[word]"
-> The grep command is used for searching lines that match a regular expression.
-> It does a global search with the regular expression and prints all matching lines.

GitLab by default will try run the jobs in parallel.
In order to specify the order in which different jobs should be executed, we need to define stages.
