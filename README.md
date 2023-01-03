# cloud-custodian

custodian run --output-dir ouput --region us-east-1 running-instances.yaml
custodian report --output-dir ouput --region us-east-1 running-instances.yaml

#  docker build -t matheuss7/cloud-custodian-aws:latest .  && docker push  matheuss7/cloud-custodian-aws:latest
#  docker run -d -p 8080:80 matheuss7/cloud-custodian-aws:latest
