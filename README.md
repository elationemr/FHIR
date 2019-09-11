# FHIR

brew install mkcert (https://github.com/FiloSottile/mkcert)
run "mkcert -install"
use hippo branch fhir_serializer
restart docker
git clone fhir repo
cd growth-chart-app
npm install
npm start

login to testdoctor1
http://localhost:9000/launch?fhirServiceUrl=https://localhost&patientId=1638401