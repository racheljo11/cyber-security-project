# SSL Security Report

## SSL Grade
A

## Supported Protocols
- TLS 1.3
- TLS 1.2

## Unsupported Protocols
- TLS 1.1
- TLS 1.0
- SSLv3
- SSLv2

## Certificate Details
- Issuer: Sectigo
- Key Size: RSA 2048
- Signature Algorithm: SHA256withRSA

## Weaknesses Identified
- HSTS not enabled
- OCSP Stapling not enabled

## Recommendations
- Enable HSTS
- Enable OCSP Stapling
- Continue using TLS 1.2 and TLS 1.3 only

## Conclusion
The SSL configuration is secure and received an A grade.