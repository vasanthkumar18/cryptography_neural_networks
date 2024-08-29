# Secure Communication using Neural Networks via Socket Communication 
Implementing Cryptography using Neural Networks through tuning and implementation via socket communication. 

# Breif Summary 
### Project Focus:
> 1. Utilizes the CIA (Confidentiality, Integrity, and Availability) triad.
> 2. Demonstrates an efficient neural cryptography algorithm (NCA) through tuning and socket communication.

 ### NCA Characteristics:
> 1. Dynamically self-configurable.
> 2. Provides a robust yet variable algorithm with the potential for low error rates using neural networks.

 ### Innovations:
> 1. Introduces a new signature/verification capability based on neural network hidden states. <strong>*This feature has not been achieved before*</strong>

### Code and Development:
> 1. The provided code serves as a foundation for further research and enhancements in neural cryptography.
> 2. The cipher is designed to autonomously restore system confidentiality if compromised.

#### Potential Applications:
> 1. Secure communication for autonomous IoT devices.
> 2. Possible use in Artificial Intelligence due to its adaptable nature and efficiency in parallel processing environments.

## How to Use
Run on Jupyter Notebook enivronment 

## Results

### Cryptography Timing
#### NCA
<img width="610" alt="image" src="https://github.com/user-attachments/assets/1b72a369-2a62-4fec-9d74-b1d05664791d">

#### SHA256
<img width="562" alt="image" src="https://github.com/user-attachments/assets/3896cc90-b6f8-4cac-be59-d05feb1b3cb7">

### Signing and Verification Timing
#### NCA
<img width="545" alt="image" src="https://github.com/user-attachments/assets/d69dbd77-4b9c-4af1-bfe1-84d7900ff7e5">

#### SHA256
<img width="537" alt="image" src="https://github.com/user-attachments/assets/1f079059-484c-46d6-865a-9dcb18752719">


## Conclusion 

### Cryptography
I've shown that it's possible to achieve low error rates with neural networks, even though CNNs can be inconsistent. I simulated communication between "Alice" and "Bob" using sockets to demonstrate how CNNs could work in real-world scenarios on a TCP/IP network.
### Signature Verification 
In this notebook, I demonstrated how neural networks can create digital signatures that ensure data integrity and authenticity, similar to SHA256. Future work includes extending the socket implementation to work over the Internet, instead of just on localhost. Other goals involve adding an "Eve" component to the crypto process, allowing for signatures to be transmitted with the plaintext. It would also be interesting to see if "Eve" could generate a signature that matches those created by "Bob" and "Alice" using a hidden layer in the network.

## References
1. Adversarial Neural Cryptography in Theano -  [Link](https://nlml.github.io/neural-networks/adversarialneural-cryptography/)
2. Alexander KlimovAnton MityaginAdi Shamir, ***Analysis of Neural Cryptography***, 2016
3. Fernet (symmetric encryption)- [Link](https://cryptography.io/en/latest/fernet/)
4.  R. Mislovaty, E. Klein, I. Kanter, W. Kinzel, ***Security of neural cryptography***, 2004
