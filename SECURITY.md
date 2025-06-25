# Security Policy

## 🔒 Security Commitment

The Axie Infinity Offline project takes security seriously. As an offline application that handles no user data, our security focus is on:

- **Application Security**: Preventing malicious code execution
- **Local Data Protection**: Securing user's local game data
- **Download Integrity**: Ensuring safe and authentic releases
- **Privacy Protection**: Maintaining complete offline operation

## 🛡️ Supported Versions

We provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | ✅ Actively supported |
| 2.0.x   | ✅ Security updates only |
| 1.9.x   | ❌ No longer supported |
| < 1.9   | ❌ No longer supported |

## 🚨 Reporting Security Vulnerabilities

### How to Report
If you discover a security vulnerability, please report it privately:

**Email**: security@axie-offline.com  
**PGP Key**: Available on request  
**Response Time**: Within 48 hours

### What to Include
Please provide as much information as possible:

- **Description**: Clear explanation of the vulnerability
- **Impact**: Potential security implications
- **Reproduction**: Steps to reproduce the issue
- **Environment**: Operating system, app version, etc.
- **Proof of Concept**: Code or screenshots (if applicable)

### What NOT to Report Publicly
❌ **Do NOT create public GitHub issues for security vulnerabilities**  
❌ **Do NOT post security issues in Discord or forums**  
❌ **Do NOT share exploits publicly before we've addressed them**

## 🔍 Security Measures

### Application Security
- **Code Signing**: All releases are digitally signed
- **Sandboxing**: Application runs with minimal system permissions
- **No Network Access**: Complete offline operation prevents data leaks
- **Local Storage**: All data stored locally with user control

### Download Security
- **Checksum Verification**: SHA-256 hashes provided for all downloads
- **Official Sources Only**: Download only from GitHub releases or official mirrors
- **Anti-Virus Scanning**: All releases scanned before publication
- **Reproducible Builds**: Build process is transparent and verifiable

### Privacy Protection
- **No Telemetry**: Zero data collection or analytics
- **No External Calls**: No connections to external servers
- **Local Processing**: All calculations performed locally
- **User Control**: Users own all their data

## ⚠️ Common Security Considerations

### Safe Download Practices
✅ **Do**:
- Download from official GitHub releases
- Verify file checksums before installation
- Use updated antivirus software
- Read release notes and changelog

❌ **Don't**:
- Download from unofficial sources
- Ignore antivirus warnings without investigation
- Run suspicious files even if they claim to be our app
- Share the application through unofficial channels

### Local Security
- **Firewall**: Application doesn't require internet access
- **Permissions**: Grant minimal required system permissions
- **Updates**: Keep the application updated to latest version
- **Backups**: Backup your team builds and game data regularly

## 🛠️ Incident Response

### Our Process
1. **Acknowledgment**: Confirm receipt within 48 hours
2. **Assessment**: Evaluate severity and impact
3. **Development**: Create and test security fix
4. **Coordination**: Work with reporter on disclosure timeline
5. **Release**: Deploy patch and security advisory
6. **Follow-up**: Monitor for additional issues

### Timeline
- **Critical Issues**: Emergency patch within 24-72 hours
- **High Severity**: Patch within 1-2 weeks
- **Medium/Low**: Included in next regular release

## 🏆 Security Contributors

We maintain a responsible disclosure program and recognize security researchers who help improve our security:

### Hall of Fame
*Security contributors will be listed here (with permission)*

### Recognition
- Credit in security advisories
- Special mention in release notes  
- Optional listing in security hall of fame
- Bug bounty consideration for significant findings

## 📞 Security Contact

- **Email**: security@axie-offline.com
- **Discord**: Message @Security team members only
- **Emergency**: For critical issues affecting many users

## 🔐 Cryptographic Verification

### Release Signatures
All releases are signed with our PGP key:
```
Key ID: [KEY_ID]
Fingerprint: [FINGERPRINT]
```

### Verification Commands
```bash
# Verify release signature
gpg --verify axie-offline-v2.1.0.asc axie-offline-v2.1.0.zip

# Check file integrity
sha256sum -c axie-offline-v2.1.0.sha256
```

## 📋 Security Checklist for Users

### Before Installation
- [ ] Download from official GitHub releases only
- [ ] Verify file checksums match published values
- [ ] Scan downloaded files with antivirus
- [ ] Read security advisories for your version

### During Use  
- [ ] Keep application updated to latest version
- [ ] Don't run other untrusted software simultaneously
- [ ] Monitor system performance for anomalies
- [ ] Backup game data regularly

### If You Suspect Issues
- [ ] Stop using the application immediately
- [ ] Document any suspicious behavior
- [ ] Contact our security team
- [ ] Don't share potentially compromised data

## 🚨 Known Security Considerations

### Current Limitations
- **Local File Access**: Application can read/write local files (by design)
- **System Resources**: Uses CPU/GPU for game calculations (normal)
- **Memory Usage**: Loads game assets into memory (expected behavior)

### Not Security Issues
- High CPU usage during battles (intensive calculations)
- Local file creation for save data (required functionality)
- Memory usage for graphics assets (normal for games)
- Requests for graphics API access (required for rendering)

---

**Remember**: When in doubt about security, contact us privately before taking any action. We're here to help ensure everyone has a safe and secure gaming experience! 🛡️ 