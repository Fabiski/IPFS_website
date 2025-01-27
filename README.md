## Decentralized website with IPFS protocol and Pinata
I added only a html file for the index (index.html)

Then the yaml file in .github/workflows sends this html file to pinata, with the secret and public key I created on Pinata (they're stored in github and not in the code).
The code collect the cid Pinata gave us, to check for the website we created.

The website is just a .zip, didn't manage to create a real website that runs on Pinata
