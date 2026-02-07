
---

# 📄 `troubleshooting.md`

```markdown
# Troubleshooting Guide

## Overview
This document provides solutions to common issues encountered when authenticating with the API or running the data retrieval scripts.

---

## Authentication Issues

### Issue: 401 Unauthorized
**Cause:** Access token is missing or expired  
**Solution:**
- Request a new access token
- Verify token is included in the `Authorization` header

---

### Issue: Invalid Client Error
**Cause:** Incorrect client credentials  
**Solution:**
- Confirm client ID and client secret values
- Verify environment variables are set correctly

---

## Script Execution Issues

### Issue: Script fails on startup
**Cause:** Missing environment variables  
**Solution:**
- Ensure all required variables are exported
- Restart the terminal session after setting variables

---

### Issue: API request timeout
**Cause:** Network issues or API downtime  
**Solution:**
- Retry the request
- Verify API availability
- Check firewall or VPN settings

---

## Data Issues

### Issue: Empty or incomplete output files
**Cause:** No data returned for selected date range  
**Solution:**
- Verify input parameters
- Confirm data exists for the specified timeframe

---

## Logging and Debugging
- Review console output for error messages
- Inspect log files for failed requests
- Enable debug logging if available

---

## When to Escalate
Escalate issues if:
- Authentication fails consistently
- API responses return unexpected formats
- Errors persist after retries and configuration checks

---

## Summary
Most issues can be resolved through credential verification, configuration checks, or retry logic. This guide is intended to reduce downtime and support faster issue resolution.

