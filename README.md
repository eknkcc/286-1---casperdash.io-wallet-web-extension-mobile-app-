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

Pages on the website are working properly :

## Overall Impression of usage testing

The code was very well laid out and pretty printed for easy reading. Things were aligned nicely and it was easy to understand what was happening in the libraries as everything was also named very appropriately. Project successfully compiled and run.

Requirement | Finding
------------ | -------------

                           C# SDK project is available on public GitHub repository | PASS
                                   When instantiated, can connect to a Casper node | PASS
          When connected, it can make at least 1 method call and return a response | PASS
                                                     Project builds without errors | PASS
             Documentation provides sufficient installation/execution instructions | PASS
Project functionality meets/exceeds acceptance criteria and operates without error | PASS
                                                      Can connect to a Casper node | PASS
