# WebProber

**Unified Cross-Browser Developer Tools — Native, Fast, and Simple**

---

## About WebProber

WebProber is a native desktop application designed to provide web developers with a unified and simplified developer tool interface across multiple browsers. Unlike traditional browser dev tools, WebProber connects directly to your chosen browser and offers a streamlined, consistent UI to inspect, debug, and analyze web pages — without the clutter and bloat.

---

## Features (Planned)

- Cross-browser support (Chrome, Firefox, Edge, Safari)
- Unified UI for DOM inspection, CSS, network, and console
- Lightweight and high-performance native app
- Local-only data storage, no dependency on cloud services
- Modular architecture for easy extensibility

---

## Why WebProber?

- Simplifies the developer experience with one tool instead of many
- Removes inconsistencies and clunkiness of browser-specific dev tools
- Built with C++ for performance and native feel
- Ideal for developers who want control and speed

---

## Getting Started

This project is in early development.

### Prerequisites

- C++17 compatible compiler
- Qt framework (for UI and browser integration)
- CMake or preferred build system

### Build Instructions

```bash
# Clone the repo
git clone https://github.com/smsadat-dev/webprober.git
cd webprober

# Build steps (example)
mkdir build && cd build
cmake ..
make
