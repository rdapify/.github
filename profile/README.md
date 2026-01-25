<div align="center">

# 🌐 RDAPify

### Modern, Secure, and Lightning-Fast RDAP Client

**The next-generation RDAP library for TypeScript/JavaScript**

[![npm version](https://img.shields.io/npm/v/rdapify?color=blue&logo=npm)](https://www.npmjs.com/package/rdapify)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16%2B-green?logo=node.js)](https://nodejs.org/)

[Website](https://rdapify.com) • [Documentation](https://rdapify.com/docs) • [Playground](https://rdapify.com/playground) • [API Reference](https://rdapify.com/docs/api)

</div>

---

## 🚀 What is RDAPify?

RDAPify is a **unified, enterprise-grade RDAP client** that makes querying domain, IP, and ASN registration data simple, secure, and fast. Built with TypeScript, it provides a modern alternative to legacy WHOIS tools.

### ✨ Key Features

- 🔒 **Privacy-First** - Built-in PII redaction & GDPR/CCPA compliance
- ⚡ **High Performance** - Smart caching & connection pooling
- 🛡️ **Enterprise Security** - SSRF protection & input validation
- 🌍 **Universal** - Works in Node.js, Deno, Bun, browsers, and edge runtimes
- 📦 **Zero Dependencies** - Minimal footprint, maximum reliability
- 🎯 **Type-Safe** - Full TypeScript support with comprehensive types
- 🔄 **Auto-Discovery** - Automatic IANA bootstrap service integration
- 📊 **Observable** - Built-in logging, metrics, and monitoring

## 💻 Quick Start

```bash
npm install rdapify

```

```typescript
import { RDAPClient } from 'rdapify';

const client = new RDAPClient();

// Query a domain
const domain = await client.domain('example.com');
console.log(domain.registrar);

// Query an IP address
const ip = await client.ip('8.8.8.8');
console.log(ip.network);

// Query an ASN
const asn = await client.asn(15169);
console.log(asn.name);
```

## 🎯 Use Cases

- 🔍 **Domain Research** - Investigate domain ownership and history
- 🌐 **IP Intelligence** - Analyze IP address allocations and networks
- 🔐 **Security Operations** - Threat intelligence and incident response
- 📊 **Compliance** - GDPR/CCPA compliant data collection
- 🤖 **Automation** - Batch processing and scheduled monitoring
- 📈 **Analytics** - Network topology and relationship mapping

## 📦 Our Projects

<table>
<tr>
<td width="50%">

### 📚 RDAPify Library
The core TypeScript/JavaScript library

**Features:**
- Domain, IP, and ASN lookups
- Smart caching & rate limiting
- Privacy controls & PII redaction
- Enterprise-grade security

[View Repository →](https://github.com/rdapify/RDAPify)

</td>
<td width="50%">

### 🌐 Website & Docs
Comprehensive documentation and guides

**Includes:**
- Getting started guides
- API reference
- Integration examples
- Interactive playground

[Visit Website →](https://rdapify.com)

</td>
</tr>
</table>

## 🎮 Try It Now

Experience RDAPify in action with our **interactive playground**:

👉 **[Launch Playground](https://rdapify.com/playground)**

Test queries, explore responses, and see real-time results without writing any code!

## 🌟 Why Choose RDAPify?

| Feature | RDAPify | Legacy WHOIS |
|---------|---------|--------------|
| Protocol | Modern RDAP | Legacy WHOIS |
| Format | Structured JSON | Unstructured text |
| Privacy | Built-in PII redaction | Manual parsing |
| Security | SSRF protection | Limited |
| Performance | Smart caching | No caching |
| Type Safety | Full TypeScript | None |
| Standards | RFC 7483 compliant | Varies |

## 📚 Documentation

- 📖 [Getting Started](https://rdapify.com/docs/getting-started)
- 🔧 [API Reference](https://rdapify.com/docs/api)
- 🎯 [Use Cases & Examples](https://rdapify.com/docs/examples)
- 🔒 [Security & Privacy](https://rdapify.com/docs/security)
- 🚀 [Deployment Guides](https://rdapify.com/docs/deployment)
- 🤝 [Contributing Guide](https://github.com/rdapify/RDAPify/blob/main/CONTRIBUTING.md)

## 🤝 Community & Support

<div align="center">

### Join Our Community

[![GitHub Discussions](https://img.shields.io/badge/Discussions-Join-blue?logo=github)](https://github.com/rdapify/RDAPify/discussions)
[![GitHub Issues](https://img.shields.io/badge/Issues-Report-red?logo=github)](https://github.com/rdapify/RDAPify/issues)
[![Twitter Follow](https://img.shields.io/badge/Twitter-Follow-1DA1F2?logo=twitter)](https://twitter.com/rdapify)

</div>

### 💬 Get Help

- 💡 **Questions?** Ask in [GitHub Discussions](https://github.com/rdapify/RDAPify/discussions)
- 🐛 **Found a bug?** Report it in [Issues](https://github.com/rdapify/RDAPify/issues)
- 📧 **Need support?** Email [support@rdapify.com](mailto:support@rdapify.com)
- 🔒 **Security issue?** Email [security@rdapify.com](mailto:security@rdapify.com)

### 📬 Contact

- **General Inquiries**: [contact@rdapify.com](mailto:contact@rdapify.com)
- **Support**: [support@rdapify.com](mailto:support@rdapify.com)
- **Security**: [security@rdapify.com](mailto:security@rdapify.com)
- **Partnerships**: [partnerships@rdapify.com](mailto:partnerships@rdapify.com)
- **Sponsorship**: [sponsors@rdapify.com](mailto:sponsors@rdapify.com)

## 🎯 Roadmap

- [x] Core RDAP client functionality
- [x] TypeScript support
- [x] Privacy controls & PII redaction
- [x] Interactive playground
- [ ] CLI tool
- [ ] Browser extension
- [ ] GraphQL API
- [ ] Real-time monitoring dashboard
- [ ] Machine learning anomaly detection

## 💖 Sponsors & Contributors

RDAPify is an open-source project maintained by passionate developers. We welcome contributions from the community!

### 🌟 Become a Sponsor

Support the project and help us build better tools for everyone:

- ☕ [Sponsor on GitHub](https://github.com/sponsors/rdapify)
- 💰 [Open Collective](https://opencollective.com/rdapify)

### 🤝 Contributing

We love contributions! Check out our [Contributing Guide](https://github.com/rdapify/RDAPify/blob/main/CONTRIBUTING.md) to get started.

## 📄 License

RDAPify is [MIT licensed](https://github.com/rdapify/RDAPify/blob/main/LICENSE).

---

<div align="center">

**Built with ❤️ by the RDAPify community**

[Website](https://rdapify.com) • [GitHub](https://github.com/rdapify) • [npm](https://www.npmjs.com/package/rdapify) • [Twitter](https://twitter.com/rdapify)

</div>
