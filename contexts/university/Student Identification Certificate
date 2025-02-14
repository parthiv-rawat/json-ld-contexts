{
    "@context": {
        "@version": 1.1,
        "@protected": true,
        "schema": "http://schema.org/",
        "xsd": "http://www.w3.org/2001/XMLSchema#",
        "ex": "https://example.org/terms#",
        "id": "@id",
        "type": "@type",
        
        "credentialName": "schema:name",
        "issuer": {
            "@id": "schema:issuer",
            "@type": "@id"
        },
        "validFrom": {
            "@id": "schema:validFrom",
            "@type": "xsd:date"
        },
        "validUntil": {
            "@id": "schema:validUntil",
            "@type": "xsd:date"
        },
        "credentialSchema": {
            "@id": "schema:credentialSchema",
            "@type": "@id"
        },
        "credentialSubject": {
            "@id": "schema:credentialSubject",
            "@context": {
                "@version": 1.1,
                "@protected": true,
                "id": "@id",
                "studentDetails": {
                    "@id": "schema:about",
                    "@type": "schema:Person",
                    "@context": {
                        "userName": "schema:name",
                        "enrollmentID": "schema:identifier",
                        "dateOfBirth": {
                            "@id": "schema:birthDate",
                            "@type": "xsd:date"
                        },
                        "gender": "schema:gender",
                        "nationality": "schema:nationality",
                        "photo": {
                            "@id": "schema:image",
                            "@type": "@id"
                        }
                    }
                },
                "institutionDetails": {
                    "@id": "schema:provider",
                    "@type": "schema:Organization",
                    "@context": {
                        "issuerName": "schema:name",
                        "institutionType": "schema:category",
                        "officialAddress": "schema:address",
                        "contactInformation": {
                            "@id": "schema:contactPoint",
                            "@type": "schema:ContactPoint",
                            "@context": {
                                "phoneNumber": "schema:telephone",
                                "email": "schema:email"
                            }
                        },
                        "institutionLogo": {
                            "@id": "schema:logo",
                            "@type": "@id"
                        }
                    }
                },
                "authorizedSignatory": {
                    "@id": "schema:signatory",
                    "@type": "schema:Person",
                    "@context": {
                        "signatoryName": "schema:name",
                        "designation": "schema:jobTitle",
                        "signature": {
                            "@id": "schema:signature",
                            "@type": "@id"
                        },
                        "institutionSealOrStamp": {
                            "@id": "schema:image",
                            "@type": "@id"
                        }
                    }
                }
            }
        },
        "VerifiableCredential": "https://www.w3.org/2018/credentials#VerifiableCredential"
    }
}
