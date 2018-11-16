
How to deploy this alternate branch to CSIRO's maven repo

mvn deploy -DskipTests -DaltDeploymentRepository=aehrc-repository::default::sftp://aehrc.com/srv/aehrc.com/maven2

Use of "aehrc-repository" above selects appropriate credentials from settings.xml

