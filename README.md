# AENIX - Decentralized DNS Network

AENIX is a decentralized DNS system built to provide secure and censorship-resistant domain name resolution. It allows users to register unique domains in a privacy-focused environment, powered by a network of nodes. AENIX offers a new domain format (e.g., `example@domain`) and aims to disrupt traditional DNS by enabling a decentralized, peer-to-peer approach.

## Key Features

- **Decentralized DNS**: AENIX provides a peer-to-peer network for domain resolution, ensuring privacy and preventing censorship.
- **Custom Domain Format**: Domains are registered in a unique `@domain` format (e.g., `example@shop`). This distinct approach differentiates AENIX from traditional DNS systems.
- **Node Reward System**: Nodes within the AENIX network are rewarded based on their contribution to domain registration and hosting. A point-based system ensures fair rewards.
- **Affordable Fees**: Domains can be registered for a one-time fee of $2-$6 and a small recurring fee of $0.50-$3 per month. This provides a sustainable funding model for the AENIX network.
- **End-to-End Encryption**: AENIX supports end-to-end encryption using a custom SSL-like protocol (AXSC), ensuring secure communication for registered domains.
- **Domain Verification & Dispute Resolution**: AENIX allows domain challenges based on trademarks or active web traffic. If a domain is contested, the dispute is resolved by a randomly selected group of nodes.
- **Seamless Integration with Nebula Browser**: AENIX domains are compatible with the Nebula Browser, which uses Lua-based scripting for enhanced security and performance.

## How It Works

### Domain Registration Process

1. **Search for Available Domains**: Users visit the AENIX domain registration page and search for available domain names.
2. **Fill Out Registration Form**: Once a domain is selected, users fill out a registration form with details like site title, keywords, and contact information.
3. **Payment**: Users pay a one-time registration fee of $2-$6, followed by a small monthly fee of $0.50-$3 to maintain the domain.
4. **Node Selection & Domain Registration**: Nodes in the AENIX network process the registration, ensuring the domain is available and verifying the user's details. Once confirmed, the domain is registered, and an AENIX SSL-like certificate (AXSC) is generated for encryption.
5. **DNS Hosting**: The registered domain is hosted on the AENIX DNS network. Users can configure the domain with their website's IP address, title, and keywords.

### Node Reward System

- Nodes that participate in domain registration and maintenance are rewarded based on their contribution to the network. This is determined through a point-based system, which allocates a portion of the total fees collected during a set time period.
- Nodes earn a share of the network’s income according to how much they contribute (e.g., validating domain registrations, hosting DNS records, etc.).

### Domain Ownership & Dispute Resolution

- **Generic Domains**: Common domain names like `@news` or `@shop` are maintained by AENIX and made available for users to register as subdomains (e.g., `example@news`).
- **Trademarked Domains**: Domains associated with well-known companies or trademarks (e.g., `@google`) are locked and require verification before they can be transferred or registered. Users can challenge the ownership of such domains by proving they have the rights to the name (e.g., through trademark ownership).
- **Domain Revocation**: If a domain owner fails to set up a website within 30 days of registration, the domain will be revoked, and the user will have to re-register it.

### Integration with Nebula Browser

AENIX domains are compatible with the Nebula Browser, which uses Lua scripting for web development. This provides enhanced security over traditional JavaScript by allowing for safer execution of client-side scripts. 

- **Lua-based Scripting**: The Nebula Browser supports Lua scripting for web pages, offering a lightweight alternative to JavaScript.
- **Security**: The use of Lua provides a more controlled environment for executing code, reducing the risk of malicious scripts.

## Fees

- **Registration Fee**: $2-$6 (one-time)
- **Monthly Maintenance Fee**: $0.50-$3 per domain
- **Node Payments**: Nodes receive a portion of the registration fees based on their contribution to the AENIX network.

## Cryptography & Security

AENIX will implement a custom encryption protocol (AXSC) to replace traditional SSL certificates. The custom SSL-like protocol will ensure that all communications between users and the AENIX DNS system are encrypted and secure.

## Technical Details

- **Core Infrastructure**: AENIX is built on a decentralized network of nodes that maintain the DNS system and validate domain registrations.
- **Programming Languages & Technologies**: AENIX will be built using a combination of web technologies such as HTML, CSS, and Lua for the Nebula Browser. The backend will rely on node-based peer-to-peer technology for domain resolution and encryption.
- **Integration with Traditional DNS**: While AENIX is designed to be independent of traditional DNS, users with existing well-known domains can register the same domain on AENIX, making the transition smoother.

## Future Developments

- **AENIX Browser**: In development, the AENIX Browser will be tailored to interact with AENIX’s decentralized DNS network. It will also provide enhanced security features with Lua scripting.
- **More Search Engines**: While **Nebula Search** will be the primary search engine for AENIX, there is potential for other search engines to be developed to work with AENIX domains.

## How to Get Involved

AENIX is currently in active development, and we welcome contributors who are passionate about decentralization, privacy, and censorship resistance. If you would like to contribute to the project, feel free to fork the repository and submit pull requests.

### Requirements

- **Node.js**: Required for running the backend system.
- **Lua**: For scripting and browser integration.

## License

AENIX is open-source software, licensed under the [MIT License](LICENSE).

---

For more information or if you have any questions, feel free to reach out via our contact page or open an issue in the repository.
