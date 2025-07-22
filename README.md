# QtTinySA-mac

This is a macOS-compatible version of [QtTinySA](https://github.com/g4ixt/QtTinySA), a graphical interface for the TinySA spectrum analyzer.  
It provides real-time scanning, frequency range control, 2D/3D visualizations, and CSV export of spectrum data.

## 🔧 Requirements

- macOS (tested on Apple Silicon)
- Python 3.10+
- Conda (recommended)

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Highlander-maker/QtTinySA-mac.git
cd QtTinySA-mac

# Create and activate conda environment
conda create -n tinysa python=3.10
conda activate tinysa

# Install required Python packages
pip install pyqt5 pyqtgraph pyopengl numpy platformdirs pyserial

# Run the app
python src/QtTinySA.py

## 📊 Tips for Scanning

- Set **Start/Stop Frequency** using the lower control bar.
- Adjust **RBW** and **Points** to balance scan speed vs. resolution.
- Enable **Max trace** to capture peaks.
- Use **Markers** (M1/M2/M3) to highlight signal frequencies.
- **CSV Export**: Not fully implemented — for now, manually read or screenshot data.

---

## 🧰 Useful Controls

- **LNA** – Boosts weak signals (only when needed)
- **Spur On** – Suppresses internal clock harmonics
- **Attenuator** – Protects input by reducing incoming signal level

---

## 🧠 Notes

- Tested with **TinySA firmware v1.4-175**
- Scan speed depends on your frequency span and settings
- Best results using **USB cable connection** (not battery-powered)

---

## 🙏 Credits

- Original project: [g4ixt/QtTinySA](https://github.com/g4ixt/QtTinySA)
- macOS adaptation by [Highlander-maker](https://github.com/Highlander-maker)