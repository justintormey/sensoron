# SensorOn

**The SensorOn Standard (SOS)**: an open, testable status-light standard for camera-bearing wearables. One lamp, four states, every behavior adapted from a signal the world already reads, and every requirement written to be tested.

- **Read the specification:** [sensoron.org](https://sensoron.org) (until DNS propagates: [justintormey.github.io/sensoron](https://justintormey.github.io/sensoron/))
- **Status:** Draft, developed in public. Current version is in [`VERSION`](VERSION); history in [`CHANGELOG.md`](CHANGELOG.md). Versions follow [Semantic Versioning](https://semver.org/) and are tagged.
- **Editor:** Justin Tormey

## The four states

A camera-bearing wearable carries one lamp, the sensor indicator, that tells the viewer which of four states it is in:

| State | Lamp | The claim it makes |
|---|---|---|
| OFF | Dark | My sensors have no power. |
| AMBIENT | Dim green, smooth pulse, never off | I am sensing, and I keep nothing. I can only wake. |
| SESSION | Solid, bright green | I have been invoked and I can act. Nothing of this session will outlive it. |
| RECORDING | Hard-blinking red | This moment may persist beyond itself. |

No light, no sensing. The specification carries measurable values for every requirement (chromaticity, intensity, timing, interlock, tamper) and a tiered conformance model separating what any bench can verify from what accredited-laboratory certification verifies.

## Participating

This is a work in progress, in public. See [CONTRIBUTING.md](CONTRIBUTING.md):

- **Errata** (a factual or technical mistake in the spec): open an issue with the `errata` label.
- **Proposals** (a change to requirements, states, scope, or process): open an issue with the `proposal` label.
- **Open questions**: the specification's section 14 items are tracked as `open-question` issues.
- **Discussions** are open for everything that is not yet an issue.

Changes arrive as pull requests and are decided by the editor.

## License

The specification text is licensed under [CC BY 4.0](LICENSE.md). The SensorOn wordmark, the Pulse logo, and the SOS adopter mark are governed by section 15 of the specification; the license grants no trademark rights.
