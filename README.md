Readme · MD
Copy

# Tanglement.ai Legal Documents

> **⚖️ Comprehensive legal templates and documentation for Tanglement.ai**

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)]()

---

## 📋 Table of Contents

- [Overview](#overview)
- [Documents Available](#documents-available)
- [Usage Guidelines](#usage-guidelines)
- [Document Descriptions](#document-descriptions)
- [How to Use These Documents](#how-to-use-these-documents)
- [DocuSign Integration](#docusign-integration)
- [Customization Guide](#customization-guide)
- [Legal Disclaimer](#legal-disclaimer)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 🎯 Overview

This repository contains production-ready legal templates and documentation for **Tanglement.ai**. These documents are designed to protect our intellectual property, establish clear business relationships, and ensure compliance with applicable laws.

---

## 📄 Documents Available

### 🔐 Non-Disclosure Agreements (NDAs)

| Document | Format | Purpose | Status |
|----------|--------|---------|--------|
| **Tanglement_NDA_Final** | `.docx` / `.md` | Primary mutual NDA for all business relationships | ✅ Ready |
| **Tanglement_NDA_DocuSign** | `.docx` | DocuSign-optimized with clear signature fields | ✅ Ready |
| **Tanglement_NDA_AutoTag** | `.docx` | Auto-tagging version for DocuSign automation | ✅ Ready |

### 📋 Additional Documents

| Document | Format | Purpose | Status |
|----------|--------|---------|--------|
| **DocuSign_Implementation_Guide** | `.md` | Complete setup instructions for DocuSign | ✅ Ready |
| *(More templates coming soon)* | - | - | 🚧 Planned |

---

## 🚀 Usage Guidelines

### Quick Start

1. **Choose the right document** for your use case (see [Document Descriptions](#document-descriptions))
2. **Customize** the template with your specific information
3. **Review** with legal counsel (recommended)
4. **Deploy** via DocuSign or manual signing

### When to Use Each NDA

- **For investors, partners, or co-founders**: Use `Tanglement_NDA_Final.docx`
- **For contractors or consultants**: Use `Tanglement_NDA_Final.docx`
- **For quick DocuSign setup**: Use `Tanglement_NDA_AutoTag.docx`
- **For maximum control**: Use `Tanglement_NDA_DocuSign.docx`

---

## 📖 Document Descriptions

### Tanglement_NDA_Final (DOCX & Markdown)

**Purpose**: Comprehensive mutual non-disclosure agreement protecting Tanglement.ai's intellectual property.

**Key Features**:
- ✅ **Comprehensive confidentiality** - Covers all technical, business, and strategic information
- ✅ **Strong non-compete** (3 years) - Specifically prohibits competing LLM routing systems
- ✅ **Non-circumvention** (3 years) - Protects business relationships and opportunities
- ✅ **IP assignment** - Any derivatives based on our IP belong to Tanglement.ai
- ✅ **Liquidated damages** - $500,000 per non-compete breach
- ✅ **7-year survival** - Obligations continue after termination
- ✅ **Trade secret protection** - Permanent protection for qualifying information

**What It Protects**:
- 🔹 DHT implementations and routing algorithms
- 🔹 WireGuard mesh network configurations
- 🔹 Signal Protocol implementations
- 🔹 Token economic models
- 🔹 Business plans and go-to-market strategies
- 🔹 Customer and partner relationships
- 🔹 All work-in-progress and prototypes

**Best For**:
- Investor presentations and due diligence
- Co-founder and early team discussions
- Strategic partnership negotiations
- Contractor and consultant engagements
- Any disclosure of proprietary technology

---

### Tanglement_NDA_DocuSign (DOCX)

**Purpose**: Clean, visually formatted NDA optimized for manual field placement in DocuSign.

**Key Features**:
- Clear signature lines with underscores
- Separate signature pages for each party
- Professional formatting
- Easy drag-and-drop field placement

**Best For**: Users who want maximum control over DocuSign field placement and configuration.

---

### Tanglement_NDA_AutoTag (DOCX)

**Purpose**: Automated DocuSign setup using anchor text tags.

**Key Features**:
- Embedded `\s1\`, `\n1\`, `\d1\` tags for automatic field detection
- Zero manual field placement required
- Faster deployment workflow
- Consistent field positioning

**DocuSign Tags Used**:
- `\s1\` `\s2\` - Signature fields
- `\n1\` `\n2\` - Full name fields
- `\t1\` `\t2\` - Title fields
- `\d1\` `\d2\` - Date fields
- `\co2\` - Company name (receiving party)

**Best For**: High-volume NDA deployment with consistent formatting needs.

---

## 🔧 How to Use These Documents

### Method 1: DocuSign (Recommended)

#### Using Auto-Tag Version

1. Log into DocuSign
2. Select **"Send an Envelope"**
3. Upload `Tanglement_NDA_AutoTag.docx`
4. Add recipients:
   - **Signer 1**: Your email (Tanglement.ai)
   - **Signer 2**: Recipient's email
5. Enable **"Auto Place"** fields
6. Review that all fields are detected correctly
7. Add subject line and message
8. Send!

#### Using Manual Version

1. Log into DocuSign
2. Select **"Send an Envelope"**
3. Upload `Tanglement_NDA_DocuSign.docx`
4. Add recipients
5. Click **"Add Fields to Document"**
6. Drag signature, date, and text fields onto the signature lines
7. Assign fields to appropriate signers
8. Send!

### Method 2: Manual Signing

1. Download `Tanglement_NDA_Final.docx`
2. Customize the bracketed fields `[Your Company Address]`, etc.
3. Print two copies
4. Sign and date both copies
5. Have the other party sign and date
6. Each party retains one fully executed copy

---

## 📱 DocuSign Integration

### Setup Requirements

- DocuSign account (Business Pro or higher recommended)
- Signer email addresses
- Company information ready to fill in

### Field Types You'll Need

| Field Type | Purpose | Required |
|-----------|---------|----------|
| Signature | Legal signature | ✅ Yes |
| Date Signed | Execution date | ✅ Yes |
| Full Name | Printed name | ⚠️ Recommended |
| Title | Signer's role | ⚠️ Recommended |
| Company | Organization name | ⚠️ Optional |

### Best Practices

✅ **DO**:
- Test send to yourself first
- Use signing order (you first, then recipient)
- Set all signature and date fields as required
- Add a clear email subject and message
- Save completed documents securely

❌ **DON'T**:
- Send without testing field placement
- Use unclear recipient names
- Skip the review step before sending
- Forget to download executed copies

---

## ✏️ Customization Guide

### Required Customizations

Before using any template, you **must** customize these fields:

#### In the Preamble Section

```
[Your Company Address]      → Your actual business address
[Your Company Email]         → Your business email address
[Receiving Party Name]       → Other party's name or leave blank
[Receiving Party Address]    → Other party's address or leave blank
[Receiving Party Email]      → Other party's email or leave blank
```

#### Optional Customizations

You may want to adjust:

1. **Non-Compete Duration** (Section 4.1)
   - Default: 3 years
   - Consider: 1-5 years based on industry norms

2. **Liquidated Damages Amount** (Section 9.3)
   - Default: $500,000
   - Consider: Based on potential actual damages

3. **Survival Period** (Section 5.3)
   - Default: 7 years
   - Consider: 3-10 years based on sensitivity

4. **Governing Law** (Section 10)
   - Default: California / San Bernardino County
   - Consider: Your primary business location

### Advanced Customizations

For more significant modifications:

1. **Consult legal counsel** - These are complex legal agreements
2. **Test thoroughly** - Ensure modifications don't break DocuSign integration
3. **Version control** - Keep track of customized versions
4. **Document changes** - Note what was modified and why

---

## ⚖️ Legal Disclaimer

### Important Notices

⚠️ **THESE TEMPLATES ARE PROVIDED FOR INFORMATIONAL PURPOSES ONLY**

- These documents are **not legal advice**
- These documents are **not a substitute for an attorney**
- **Consult with a qualified attorney** in your jurisdiction before using these documents
- Laws vary by jurisdiction and circumstances
- Tanglement.ai makes **no warranties** about the suitability of these documents
- Use of these documents is **at your own risk**

### Limitations of Liability

By using these documents, you acknowledge that:

1. **No Attorney-Client Relationship**: Use of these documents does not create an attorney-client relationship
2. **No Guarantees**: We make no guarantees about legal validity or enforceability
3. **Your Responsibility**: You are solely responsible for customizing and using these documents appropriately
4. **Jurisdictional Variations**: These documents may not be suitable for all jurisdictions
5. **Changes in Law**: Laws change; ensure documents are current for your needs

### When You Should Hire an Attorney

You should **definitely** consult an attorney if:

- 🔴 You're protecting highly sensitive or valuable IP
- 🔴 You're entering a major business relationship
- 🔴 You're dealing with international parties
- 🔴 Your state has specific NDA requirements
- 🔴 You need to customize the standard terms
- 🔴 You're uncertain about any provisions
- 🔴 The other party has concerns or requests changes

---

## 🤝 Contributing

We welcome improvements to these templates! However, please note:

### Contribution Guidelines

1. **Fork** this repository
2. **Create a branch** for your changes
3. **Test thoroughly** - Ensure DocuSign compatibility
4. **Document changes** - Explain what and why
5. **Submit a pull request** with clear description

### What We Accept

✅ **YES**:
- Grammatical corrections
- Formatting improvements
- DocuSign optimization
- Additional template variations
- Documentation improvements

❌ **NO**:
- Changes that weaken legal protections
- Unilateral modifications to legal terms
- Removal of key protective clauses

### Review Process

- All contributions reviewed by legal team
- May take 7-14 days for review
- Changes may be requested
- Not all contributions will be accepted

---

## 📞 Contact

### Tanglement.ai

- **Website**: [tanglement.ai](https://tanglement.ai)
- **Email**: legal@tanglement.ai
- **GitHub**: [@tanglement-ai](https://github.com/tanglement-ai)

### For Legal Questions

Please direct legal questions to your own attorney. We cannot provide legal advice.

### For Template Issues

If you find errors or have suggestions:
1. Open an issue on GitHub
2. Email legal@tanglement.ai
3. Submit a pull request with fixes

---

## 📚 Additional Resources

### Related Documentation

- [Tanglement.ai Technical Specification](../docs/spec/README.md)
- [Token Economics Whitepaper](../docs/economics/README.md)
- [Security Architecture](../docs/security/README.md)

### External Resources

- [DocuSign API Documentation](https://developers.docusign.com/)
- [AIPLA - Model Forms](https://www.aipla.org/)
- [WSGR - Document Generator](https://www.wsgr.com/en/insights/document-generator.html)

### Legal Information

- [Understanding NDAs](https://www.sba.gov/business-guide/launch-your-business/protect-your-intellectual-property)
- [Non-Compete Agreements](https://www.nolo.com/legal-encyclopedia/noncompete-agreements-overview-29862.html)
- [Trade Secrets Protection](https://www.uspto.gov/ip-policy/trade-secret-policy)

---

## 📄 License

These templates are proprietary and confidential to Tanglement.ai. 

**Usage Terms**:
- ✅ You may use these templates for your interactions with Tanglement.ai
- ✅ You may customize these templates for your specific use case
- ❌ You may not redistribute these templates
- ❌ You may not remove or modify attribution

See [LICENSE](LICENSE) file for complete terms.

---

## 🔄 Version History

### v1.0.0 (October 2025)
- Initial release
- Comprehensive mutual NDA
- DocuSign integration
- Multiple format options

---

## 🎯 Roadmap

### Planned Additions

- [ ] Employee offer letter templates
- [ ] Contractor agreements
- [ ] Terms of Service
- [ ] Privacy Policy
- [ ] API Terms of Use
- [ ] Token Purchase Agreement
- [ ] Partner Agreement Template
- [ ] Advisory Board Agreement

### In Development

- [ ] Multi-language versions
- [ ] Jurisdiction-specific variations
- [ ] Interactive customization wizard
- [ ] Automated compliance checker

---

## ⭐ Acknowledgments

These templates were created with input from:
- Legal counsel experienced in technology transactions
- DocuSign integration specialists
- Open source legal template communities
- Tanglement.ai founding team

---

## 📊 Status

| Category | Status |
|----------|--------|
| NDA Templates | ✅ Complete |
| DocuSign Integration | ✅ Complete |
| Documentation | ✅ Complete |
| Legal Review | ✅ Complete |
| Multi-jurisdiction | 🚧 In Progress |
| Employee Templates | 📋 Planned |

---

**Last Updated**: October 2025  
**Maintained By**: Tanglement.ai Legal Team  
**Repository**: github.com/tanglement-ai/legal-docs

---

<p align="center">
  <strong>Protecting innovation through clear, comprehensive legal frameworks</strong><br>
  <sub>Built for the distributed future of AI infrastructure</sub>
</p>

---

## Quick Links

- 📥 [Download All Templates](../../releases/latest)
- 📖 [Read the Docs](../docs/README.md)
- 🐛 [Report an Issue](../../issues)
- 💡 [Request a Feature](../../issues/new)
- 🔐 [Security Policy](SECURITY.md)

---
