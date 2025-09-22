# GitHub GIG Cymru CodeSpaces Guide

A comprehensive guide to setting up and using GitHub Codespaces within the GitHub GIG Cymru service for NHS Wales organizations.

## Table of Contents

- [What is GitHub Codespaces?](#what-is-github-codespaces)
- [What is GitHub GIG Cymru?](#what-is-github-gig-cymru)
- [Benefits of Using Codespaces](#benefits-of-using-codespaces)
- [Getting Started](#getting-started)
- [Setting Up Your First Codespace](#setting-up-your-first-codespace)
- [Using Codespaces Effectively](#using-codespaces-effectively)
- [Organization-Specific Features](#organization-specific-features)
- [Troubleshooting](#troubleshooting)
- [Support and Resources](#support-and-resources)

## What is GitHub Codespaces?

GitHub Codespaces is a cloud-based development environment that allows you to code, build, test, and debug applications directly in your browser or through Visual Studio Code. It provides a complete, configurable development environment hosted in the cloud, eliminating the need to set up local development environments.

### Key Features:
- **Instant Setup**: Launch a fully configured development environment in seconds
- **Browser-Based**: Code directly in your web browser with a full VS Code experience
- **Customizable**: Configure your environment with specific tools, extensions, and settings
- **Collaborative**: Share and collaborate on code with your team seamlessly
- **Scalable**: Choose from different machine types based on your project needs

## What is GitHub GIG Cymru?

**GitHub GIG Cymru is a secure, centrally managed GitHub Enterprise platform provided by NHS Wales.** This enterprise-grade platform offers several advantages for NHS Wales organizations:

### Core Benefits:
- **Develop under a community umbrella:** Each organization gets its own GitHub organization, fostering collaboration and knowledge sharing across NHS Wales
- **Leverage enterprise features:** Benefit from advanced security, compliance, and management tools specifically designed for healthcare environments

### Platform Features:
- **Enhanced Security**: Enterprise-grade security controls and compliance features
- **Central Management**: Streamlined administration across all NHS Wales organizations
- **Collaboration**: Cross-organizational collaboration while maintaining security boundaries
- **Compliance**: Built-in tools to help meet healthcare data protection requirements
- **Support**: Dedicated support for NHS Wales development teams

## Benefits of Using Codespaces

Using GitHub Codespaces within the GitHub GIG Cymru platform provides numerous advantages:

### 🚀 **Rapid Development**
- **Zero Setup Time**: Jump into coding immediately without local environment configuration
- **Consistent Environments**: Ensure all team members work with identical development setups
- **Pre-configured Tools**: Access pre-installed development tools and dependencies

### 🔒 **Enhanced Security**
- **Secure by Default**: Code remains in secure cloud environments
- **No Local Data**: Sensitive NHS data never needs to be stored locally
- **Access Controls**: Leverage enterprise security policies and access controls
- **Audit Trail**: Complete visibility into development activities

### 💡 **Improved Collaboration**
- **Instant Sharing**: Share development environments with colleagues instantly
- **Live Collaboration**: Work together on code in real-time
- **Knowledge Transfer**: Onboard new team members quickly with pre-configured environments

### 🌐 **Accessibility**
- **Device Independent**: Work from any device with a web browser
- **Remote Friendly**: Perfect for remote work and distributed teams
- **Consistent Experience**: Same development experience across all devices

### 💰 **Cost Effective**
- **No Hardware Requirements**: Reduce local hardware needs
- **Pay-per-Use**: Only pay for compute time when actively developing
- **Reduced IT Overhead**: Less local software management and troubleshooting

## Getting Started

### Prerequisites

Before you can use GitHub Codespaces, ensure you have:

1. **Access to GitHub GIG Cymru**: Your NHS Wales organization must have provisioned access
2. **GitHub Account**: A GitHub account associated with your organization
3. **Appropriate Permissions**: Repository access and Codespaces permissions
4. **Modern Web Browser**: Chrome, Firefox, Safari, or Edge (latest versions)

### Initial Setup

1. **Log into GitHub GIG Cymru**
   - Navigate to your organization's GitHub instance
   - Sign in with your NHS Wales credentials

2. **Verify Codespaces Access**
   - Go to your user settings
   - Check that Codespaces is enabled for your account

3. **Review Organization Policies**
   - Familiarize yourself with your organization's Codespaces policies
   - Understand any usage limits or restrictions

## Setting Up Your First Codespace

### Method 1: From a Repository

1. **Navigate to Repository**
   - Go to the repository you want to work on
   - Ensure you have appropriate access permissions

2. **Create Codespace**
   - Click the green **"Code"** button
   - Select the **"Codespaces"** tab
   - Click **"Create codespace on main"** (or your desired branch)

3. **Choose Configuration**
   - Select machine type (2-core, 4-core, 8-core, etc.)
   - Choose region (if available)
   - Click **"Create codespace"**

### Method 2: From Codespaces Dashboard

1. **Access Dashboard**
   - Go to [github.com/codespaces](https://github.com/codespaces)
   - Or click your profile → "Your codespaces"

2. **New Codespace**
   - Click **"New codespace"**
   - Select repository and branch
   - Configure machine type and region
   - Click **"Create codespace"**

### Initial Configuration

When your Codespace starts:

1. **Wait for Setup**: The environment will automatically configure based on repository settings
2. **Install Extensions**: VS Code extensions will be installed automatically
3. **Review Environment**: Check that all necessary tools are available
4. **Test Setup**: Run any setup scripts or commands specific to your project

## Using Codespaces Effectively

### Development Workflow

1. **Code Development**
   - Use the integrated VS Code interface
   - Access terminal for command-line operations
   - Install additional tools as needed

2. **Version Control**
   - Commit and push changes directly from the Codespace
   - Use VS Code's built-in Git integration
   - Create and manage branches

3. **Testing and Debugging**
   - Run tests within the Codespace environment
   - Use integrated debugging tools
   - Preview applications using port forwarding

### Best Practices

#### 🔧 **Environment Management**
- Use `devcontainer.json` files to define consistent environments
- Document environment requirements in your repository
- Regularly update base images and configurations

#### 💾 **Data Management**
- Commit changes frequently to avoid data loss
- Use persistent storage for important files
- Backup configuration files and settings

#### ⚡ **Performance Optimization**
- Choose appropriate machine types for your workload
- Stop Codespaces when not in use to save costs
- Use efficient development practices

#### 🔐 **Security Practices**
- Never store sensitive credentials in code
- Use environment variables for configuration
- Follow your organization's security guidelines

### Customization Options

#### Personal Settings
- **Dotfiles**: Automatically apply your personal configuration
- **Settings Sync**: Sync VS Code settings across Codespaces
- **Extensions**: Install and manage development extensions

#### Repository Configuration
- **Dev Containers**: Define project-specific environments
- **Prebuild**: Create faster-starting Codespaces
- **Port Configuration**: Set up application ports and forwarding

## Organization-Specific Features

### NHS Wales Integration

As part of the GitHub GIG Cymru platform, your Codespaces benefit from:

#### **Enterprise Security**
- Single Sign-On (SSO) integration
- Advanced audit logging
- IP allowlist support
- Enterprise-grade encryption

#### **Collaboration Tools**
- Cross-organization visibility (where appropriate)
- Shared templates and configurations
- Centralized billing and usage reporting
- Policy enforcement and compliance

#### **Resource Management**
- Organization-wide usage policies
- Spending limits and controls
- Machine type restrictions
- Automatic timeout configurations

### Compliance Considerations

When working with NHS data:

- **Data Classification**: Understand data sensitivity levels
- **Access Controls**: Respect patient data access restrictions
- **Audit Requirements**: Maintain appropriate audit trails
- **Data Residency**: Ensure compliance with data location requirements

## Troubleshooting

### Common Issues

#### **Codespace Won't Start**
- Check organization policies and limits
- Verify repository permissions
- Try a different machine type or region
- Contact your organization administrator

#### **Performance Issues**
- Upgrade to a larger machine type
- Close unnecessary browser tabs
- Check network connectivity
- Restart the Codespace

#### **Extension Problems**
- Update VS Code extensions
- Check extension compatibility
- Clear extension cache
- Reinstall problematic extensions

#### **Connection Issues**
- Refresh your browser
- Check internet connectivity
- Try incognito/private browsing mode
- Clear browser cache and cookies

### Getting Help

1. **Organization Support**
   - Contact your NHS Wales IT support team
   - Check internal documentation and wikis
   - Reach out to your GitHub organization administrators

2. **GitHub Documentation**
   - Visit [GitHub Codespaces Documentation](https://docs.github.com/en/codespaces)
   - Check [GitHub Community Forum](https://github.community/)
   - Review [GitHub Status Page](https://www.githubstatus.com/)

3. **Emergency Procedures**
   - Follow your organization's incident response procedures
   - Document any security-related issues
   - Escalate critical problems through appropriate channels

## Support and Resources

### Documentation Links
- [GitHub Codespaces Official Documentation](https://docs.github.com/en/codespaces)
- [VS Code in Codespaces](https://code.visualstudio.com/docs/remote/codespaces)
- [Dev Container Configuration](https://containers.dev/)

### Training Resources
- GitHub Skills courses on Codespaces
- NHS Wales internal training materials
- VS Code documentation and tutorials

### Community
- NHS Wales developer communities
- GitHub organization discussions
- Internal knowledge sharing sessions

---

## Quick Reference

### Essential Commands
```bash
# Open terminal
Ctrl+` (or Cmd+` on Mac)

# Command palette
Ctrl+Shift+P (or Cmd+Shift+P on Mac)

# File explorer
Ctrl+Shift+E (or Cmd+Shift+E on Mac)

# Source control
Ctrl+Shift+G (or Cmd+Shift+G on Mac)
```

### Useful Links
- [Your Codespaces Dashboard](https://github.com/codespaces)
- [Organization Settings](https://github.com/settings/organizations)
- [Usage and Billing](https://github.com/settings/billing)

---

*This guide is maintained by the GitHub GIG Cymru team for NHS Wales organizations. For updates and suggestions, please create an issue in this repository.*
