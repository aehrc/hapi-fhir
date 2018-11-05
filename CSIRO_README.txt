
How to deploy this alternate branch to CSIRO's maven repo

mvn deploy -DskipTests -DaltDeploymentRepository=internal.repo::default::sftp://aehrc.com/srv/aehrc.com/maven2

