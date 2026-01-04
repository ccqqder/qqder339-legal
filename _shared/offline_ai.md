# Offline AI & Privacy

## On-Device Processing

All AI features operate completely offline using local machine learning models:

### Technical Implementation
- **Local LLM Inference:** Uses on-device Large Language Models downloaded to your device
- **No Cloud Processing:** All AI computations run locally without external API calls
- **Privacy-First:** Your data never leaves your device during AI processing

### Model Downloads
- **User-Initiated:** Models are only downloaded when you explicitly choose to
- **One-Time Download:** Models are stored locally after download
- **Optional Feature:** AI features can be skipped; app works without downloading models

### Network Usage
Network access for AI features is limited to:
1. **Initial model download** (optional, user-initiated)
2. **No ongoing connections** for inference/processing

### Data Storage
- **Models:** Stored in device cache or App Group container
- **Inference Results:** Generated on-device, stored locally
- **No Telemetry:** No usage data transmitted to developers or third parties
