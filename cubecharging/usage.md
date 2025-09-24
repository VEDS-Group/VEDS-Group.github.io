---
title: Usage
parent: CubeCharging
nav_order: 3
---

# Usage Guide

This guide will help you get started with CubeCharging and understand how to use its key features.

## Getting Started

### Starting the Service

Once you have CubeCharging installed, start the service:

```bash
npm start
```

The service will be available at `http://localhost:3000` by default.

### API Endpoints

CubeCharging provides a RESTful API for managing charging operations:

#### Health Check
```bash
GET /api/health
```

#### Get Charging Stations
```bash
GET /api/stations
```

#### Start Charging Session
```bash
POST /api/sessions
{
  "stationId": "station_001",
  "deviceId": "device_123",
  "maxPower": 5000
}
```

#### Get Session Status
```bash
GET /api/sessions/{sessionId}
```

#### Stop Charging Session
```bash
DELETE /api/sessions/{sessionId}
```

## Basic Usage Examples

### Starting a Charging Session

```bash
curl -X POST http://localhost:3000/api/sessions \
  -H "Content-Type: application/json" \
  -d '{
    "stationId": "station_001",
    "deviceId": "device_123",
    "maxPower": 5000
  }'
```

### Monitoring Charging Progress

```bash
curl http://localhost:3000/api/sessions/session_123
```

### Stopping a Charging Session

```bash
curl -X DELETE http://localhost:3000/api/sessions/session_123
```

## Configuration

### Power Management

Configure charging power limits:

```json
{
  "maxStationPower": 10000,
  "maxSessionPower": 5000,
  "safetyThreshold": 0.9
}
```

### Device Compatibility

Supported charging standards:
- USB-C PD (Power Delivery)
- Quick Charge 3.0/4.0
- Adaptive Fast Charging
- Standard USB charging

### Safety Features

CubeCharging includes several safety mechanisms:

- **Overcurrent Protection**: Automatically reduces power if current exceeds limits
- **Temperature Monitoring**: Monitors device temperature and adjusts charging accordingly
- **Voltage Regulation**: Maintains stable voltage levels
- **Emergency Stop**: Manual and automatic emergency stop capabilities

## Advanced Features

### Scheduling

Schedule charging sessions:

```bash
curl -X POST http://localhost:3000/api/schedules \
  -H "Content-Type: application/json" \
  -d '{
    "deviceId": "device_123",
    "startTime": "2024-01-01T02:00:00Z",
    "duration": 3600,
    "maxPower": 3000
  }'
```

### Analytics

Access charging analytics:

```bash
# Get usage statistics
GET /api/analytics/usage

# Get efficiency metrics
GET /api/analytics/efficiency

# Get cost analysis
GET /api/analytics/costs
```

### Integration

CubeCharging can be integrated with:

- Smart home systems (Home Assistant, OpenHAB)
- Fleet management systems
- Energy management platforms
- IoT monitoring solutions

## Troubleshooting

### Common Issues

**Charging session won't start:**
- Check if the station is available
- Verify device compatibility
- Ensure sufficient power capacity

**Charging stops unexpectedly:**
- Check temperature readings
- Verify power supply stability
- Review error logs

**API connection issues:**
- Verify the service is running
- Check network connectivity
- Validate API keys and authentication

### Logs

View application logs:

```bash
# View real-time logs
npm run logs

# View error logs only
npm run logs --level=error

# View logs for specific session
npm run logs --session=session_123
```

### Support

For additional support:
- Check the [FAQ](faq.md)
- Review [troubleshooting guide](troubleshooting.md)
- Contact support: support@veds-group.com