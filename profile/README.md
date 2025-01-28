# SAFE-PFL
SAFE-PFL is a framework for efficient and secure personalized federated learning (FL) based on the `SAFE-PFL: Efficient and Secure Personalized Federated Learning` paper.

## Research Focus

SAFE-PFL incorporates three innovative components: a secure clustering module using a novel heuristic for similarity analysis based on parameter identifiers, which eliminates the need for gradient transmission and thus enhances privacy; a cluster-based Multi-key Homomorphic Encryption scheme that allows individual clients within a cluster to encrypt their data with unique keys, preventing key monopolization and reducing the risk of collusion; and a selective encryption strategy that targets only sensitive gradient components, reducing computational overhead while maintaining robust defense against data reconstruction attacks. Our evaluations demonstrate that SAFE-PFL achieves accuracy equal to that of PFL in trustworthy settings, while significantly enhancing data security and reducing computational demand. SAFE-PFL enhances security by encrypting just 10% of the model, effectively guarding against reconstruction attacks with minimal computation overheads of 12.68%.

## GitHub Repositories

- [safe-pfl](https://github.com/safe-pfl/safe-pfl) 
- [safe-pfl-distance](https://github.com/safe-pfl/distances) _package_
- [safe-pfl-plotter](https://github.com/safe-pfl/safe-pfl-plotter) _package_
- [safe-pfl-utils](https://github.com/safe-pfl/utils) _package_
- [safe-pfl examples](https://github.com/safe-pfl/examples)

## Members and Contacts

Visit the SAFE-PFL [people](https://github.com/orgs/safe-pfl/people) section
