Grant Proposal | 286-1---casperdash.io-wallet-web-extension-mobile-app
------------ | -------------
Milestone Title | Web Wallet
Reviewer | Ekin Keçeci <ekin@ekonteknoloji.com>

# Milestone Details

## Details & Acceptance Criteria

**Details of what will be delivered in milestone:**

- Control of Integration with Casper Singer
- Control of Dashboard
  - View CSPR balance
  - Send/Receive CRPR
  - CRPS price chart
- Control of Tokens
  - View token info/balance
  - Send/Receive tokens
  - Add custom token by contract hash
- Control of History
  - View transfer transactions history
- Control of Keys Manager
  - Deploy keys manager contract
  - Edit account weight
  - Edit Deployment/ Key management threshold
  - Add new associated key
  - Edit associated account weight
- Control of Stacking (Stacking CSPR)  
   
**Acceptance criteria:**

- Release a stable version working on mainnet with feature 

## Milestone Submission

The following milestone assets/artifacts were submitted for review:

Repository | Revision Reviewed
------------ | -------------
https://github.com/CasperDash/casperdash-client/tree/v1.0.0 | ade2cbf

# Install & Usage Testing Procedure and Findings
Following the instructions in the README of https://github.com/CasperDash/casperdash-client/tree/v1.0.0 and https://github.com/CasperDash/casperdash-api, the reviewer was able to successfully install the library. The reviewer was also able to successfully build the source code for this milestone by using the build script furnished in the root and readme of the repository.

## Overall Impression of usage testing

The code was very well laid out and pretty printed for easy reading. Things were aligned nicely and it was easy to understand what was happening in the libraries as everything was also named very appropriately. Project successfully compiled and run.

Requirement | Part | Finding
------------ | ------------- | -----------

                                   Control to View CSPR balance | Dashboard | PASS
                                   Control to Send/Receive CRPR | Dashboard | PASS
                                   Control to CRPS price chart  | Dashboard | PASS
                                   
                                   Control to View transfer transactions history |  History  | PASS
                                
  

# Documentation

### Code Documentation

Reviewer observed that all critical functions of the project had low-level code documentation which could be used for automated documentation generation.

Requirement | Finding
------------ | -------------
Code Documented | PASS

### Project Documentation

The reviewer observed that the README of the project has detailed general and usage documentation.

Requirement | Finding
------------ | -------------
Usage Documented | PASS

## Overall Conclusion on Documentation

The reviewer concludes that the project has sufficient comprehensive general documentation. 

# Open Source Practices

## Licenses

The Project is released under the MIT License

Requirement | Finding
------------ | -------------
OSI-approved open source software license | PASS

## Contribution Policies

Pull requests and Issues are enabled. And, the project contain a CONTRIBUTING policy. 

Requirement | Finding
------------ | -------------
OSS contribution best practices | PASS

# Coding Standards

## General Observations

Code is generally well-structured and readable. The Github linked project is easy and successful to install, but an error was encountered during the installation phase of the app project. An error was received in the unit tests of the project. Manual tests fail for making a delegation using the casper signer. These errors prevent the project from succeeding.

# Final Conclusion
The project provides the most of the functionalities described in the grant application and milestone acceptance criteria. 
The reviewer praises the OP for the general stability and the fluid user experience of the app.
However, it is recommended to fix test errors in the lib file. Also the "delegate using casper signer" in the milestone doesn't work properly. 
Thus, in the reviewer's opinion, this submission should fail.

# Recommendation

Recommendation | FAIL
------------ | -------------
