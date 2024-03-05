
# deploy a

score-humanitec --token $HUMANITEC_TOKEN --org $HUMANITEC_ORG --app $HUMANITEC_APP --env $HUMANITEC_ENV \
  delta --deploy -f ./score-service-a.yaml --extensions ./score-service-a-extension.yaml

# scale down manually a

# deploy b

score-humanitec --token $HUMANITEC_TOKEN --org $HUMANITEC_ORG --app $HUMANITEC_APP --env $HUMANITEC_ENV \
  delta --deploy -f ./score-service-b.yaml
