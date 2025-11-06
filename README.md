# Device Certificate Updates
Share location for certificate updates for Global Payments payment devices.

Certificates are provided in PEM, .crt format. The file extension can be renamed to view the certificate in .txt, .pem or .cer format.  
If DER format is needed, OpenSSL can be used to convert the file using the command openssl req -inform PEM -outform DER -in CSR.pem -out CSR.der
