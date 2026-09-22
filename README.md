# ZeroIoT: Industrial Protocol Connectors for .NET

[![ZeroPlatform Tier](https://img.shields.io/badge/ZeroPlatform-Tier%202%20(Transport%20%26%20Storage)-059669.svg)](https://github.com/kzxl/ZeroPlatform)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![.NET Multi-Targeting](https://img.shields.io/badge/.NET-8.0%20%7C%204.6.2%20%7C%20Standard%202.0-purple.svg)](https://dotnet.microsoft.com/)

**ZeroIoT** is a high-throughput, pure C# industrial protocol connector library for .NET. It provides zero-allocation memory pipeline decoders, binary encoders, and network clients for industrial edge computing and SCADA telemetry.

## Key Features

- **OPC-UA Binary Protocol**: Pure C# binary encoder/decoder (`UaBinaryEncoder`, `UaBinaryDecoder`), variant serialization (`UaVariant`), NodeId addressing, and asynchronous TCP transport (`UaTcpTransport`).
- **MQTT 3.1.1 & 5.0**: Ultra-lightweight asynchronous client (`MqttClient`), zero-allocation packet encoder/decoder (`MqttPacketEncoder`, `MqttPacketDecoder`) supporting QoS 0, 1, 2.
- **Sparkplug B**: Industrial IoT edge payload codec (`SparkplugCodec`) and typed metric models (`SparkplugMetric`).
- **Telemetry Bridges**: Integrated streaming bridge to `ZeroData` DataFrame (`IotDataFrameBridge`) and `ZeroStorage` Gorilla TSDB sink (`IotGorillaTsdbSink`).

## Multi-Targeting

- `.NET 8.0+`
- `.NET Framework 4.6.2+`
- `.NET Standard 2.0`

## License

MIT License. Copyright © 2026 Phong Võ (`kzxl`).
