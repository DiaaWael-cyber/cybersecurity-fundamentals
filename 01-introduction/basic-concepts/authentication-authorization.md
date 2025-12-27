# Authentication vs Authorization

## Definitions

### Authentication
Verifying the identity of a user, device, or system.

### Authorization
Determining what resources and actions an authenticated entity can access.

## Authentication Methods

### Something You Know
- Passwords
- PINs
- Security questions

### Something You Have
- Security tokens
- Smart cards
- Mobile devices
- USB security keys

### Something You Are
- Fingerprint recognition
- Facial recognition
- Iris scanning
- Voice recognition

### Somewhere You Are
- Geographic location
- IP address restrictions
- Time-based access

## Authorization Models

### Role-Based Access Control (RBAC)
- Access based on job roles
- Common in corporate environments
- Easy to manage at scale

### Attribute-Based Access Control (ABAC)
- Access based on multiple attributes
- More granular control
- Dynamic policy evaluation

### Mandatory Access Control (MAC)
- System-enforced policies
- Common in government/military
- Labels and clearances

### Discretionary Access Control (DAC)
- Owner-controlled access
- Common in personal systems
- File permissions (Unix)

## Best Practices

### Authentication
- Implement multi-factor authentication (MFA)
- Enforce strong password policies
- Use password managers
- Regular credential rotation

### Authorization
- Principle of least privilege
- Regular access reviews
- Separation of duties
- Log all access attempts

## Common Vulnerabilities

### Authentication Issues
- Weak passwords
- Password reuse
- Credential stuffing
- Session hijacking

### Authorization Issues
- Privilege escalation
- Insecure direct object references
- Broken access control
- Overly permissive policies
