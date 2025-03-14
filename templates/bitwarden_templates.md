# Bitwarden Templates

## Password Template

```
{
  "name": "Password Template",
  "fields": [
    {
      "name": "Password",
      "type": "password",
      "required": true,
      "minLength": 12,
      "pattern": "^(?=.*[a-z])(?=.*[A-Z])(?=.*\\d)(?=.*[@$!%*?&])[A-Za-z\\d@$!%*?&]{12,}$"
    }
  ]
}
```

## Personal Information Template

```
{
  "name": "Personal Information Template",
  "fields": [
    {
      "name": "Full Name",
      "type": "text",
      "required": true,
      "minLength": 2,
      "pattern": "^[a-zA-Z\\s]+$"
    },
    {
      "name": "Phone Number",
      "type": "text",
      "required": true,
      "pattern": "^\\+90\\d{10}$"
    },
    {
      "name": "Email",
      "type": "email",
      "required": false
    },
    {
      "name": "Address",
      "type": "text",
      "required": false
    },
    {
      "name": "Company",
      "type": "text",
      "required": false
    },
    {
      "name": "Job Title",
      "type": "text",
      "required": false
    },
    {
      "name": "Notes",
      "type": "textarea",
      "required": false
    }
  ]
}
```

## Notes Template

```
{
  "name": "Notes Template",
  "fields": [
    {
      "name": "Title",
      "type": "text",
      "required": true
    },
    {
      "name": "Content",
      "type": "textarea",
      "required": true
    }
  ]
}
```

## OTP Template

```
{
  "name": "OTP Template",
  "fields": [
    {
      "name": "Service Name",
      "type": "text",
      "required": true
    },
    {
      "name": "OTP Secret",
      "type": "text",
      "required": true
    },
    {
      "name": "Issuer",
      "type": "text",
      "required": false
    },
    {
      "name": "Algorithm",
      "type": "text",
      "required": false
    }
  ]
}
```
