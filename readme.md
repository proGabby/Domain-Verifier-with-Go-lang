## A SIMPLE DOMAIN-VERIFIER WITH GO LANG

# HOW IT WORKS
1. The program takes A domain name.
2. lookup the MX record of the domain to ensure the Mx record isn't empty.
3. lookup the TXT record to ensure the SPF and DMARC records are found
4. If all record are found the domain is declare valid.

# HOW TO USE
1. Ensure Go is install on your machine
2. Clone the repo on your machine
3. initialize Go mod by running go mod init 
4. run - go run main.go

