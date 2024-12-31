# TempestSDR

**TempestSDR_win32_executables** is a folder containing a self-executable version of [TempestSDR by martinmarinov](https://github.com/martinmarinov/TempestSDR) for Windows. This package integrates ExtIO support for multiple SDRs, including RTL-SDR, HackRF, SDRplay, and Airspy, making it a "click-and-play" solution. No additional dependencies are needed.

## Acknowledgment

This executable package is based on the efforts of [martinmarinov](https://github.com/martinmarinov/TempestSDR) for the original TempestSDR and [eried/Research/HackRF/TempestSDR](https://github.com/eried/Research/tree/master/HackRF/TempestSDR).

---

## Usage Instructions

# TempestSDR

**TempestSDR_win32_executables** is a folder containing a self-executable version of [TempestSDR by martinmarinov](https://github.com/martinmarinov/TempestSDR) for Windows. This package integrates ExtIO support for multiple SDRs, including RTL-SDR, HackRF, SDRplay, and Airspy, making it a "click-and-play" solution. Run the executable which corresponds to the SDR you are using.

## Usage Instructions

### Using Your SDR as a Source in TempestSDR
1. Ensure your SDR is properly connected and recognized by your operating system. Verify functionality using your SDR's official software or another tool like SDRSharp. If issues arise, consult your SDR's documentation or community resources.
2. Open TempestSDR from the folder. The package includes everything required, utilizing temporary files for OpenJDK and other dependencies.
3. Navigate to **File** > **Load ExtIO source** and select the appropriate ExtIO DLL for your SDR in the modal dialog.
4. Press **Start** in TempestSDR to begin.

---

## Steps for Visual Eavesdropping
1. Place your SDR device (e.g., HackRF) near the target screen to capture residual RF signals.
2. Use the included **tempest_test_elize_song.mp4** or **tempest_test_elize_song.zip** to generate a detectable pattern on the target screen.
3. In SDR software (e.g., SDRSharp), scan the frequency range of 100 MHz to 500 MHz in AM mode to detect residual RF signals. Look for signals resembling [this example](https://www.youtube.com/watch?v=_zx4ZvurgOs).
4. Enter the frequency you identified into TempestSDR.
5. Adjust the settings in TempestSDR to visualize the signal until you achieve a coherent image. The result should look like [this demonstration](https://www.youtube.com/watch?v=QjqpKtGNbQo).

---

## Modding the Self-Executable with Other EXTIO DLLs
To add support for additional SDR devices or modify existing ExtIO configurations, follow [this tutorial](https://www.youtube.com/watch?v=QjqpKtGNbQo).

---

## Note
Some antivirus programs may report a false positive for this package. This is due to the use of launch4j for wrapping the JAR file and WinRAR.SFX for handling execution. These are standard practices and do not indicate malicious activity.


---

## Steps for Visual Eavesdropping
1. Place your SDR device (e.g., HackRF) near the target screen to capture residual RF signals.
2. Use the included **tempest_test_elize_song.mp4** or **tempest_test_elize_song.zip** to generate a detectable pattern on the target screen.
3. In SDR software (e.g., SDRSharp), scan the frequency range of 100 MHz to 500 MHz in AM mode to detect residual RF signals. Look for signals resembling [this example](https://www.youtube.com/watch?v=_zx4ZvurgOs).
4. Enter the frequency you identified into TempestSDR.
5. Adjust the settings in TempestSDR to visualize the signal until you achieve a coherent image. The result should look like [this demonstration](https://www.youtube.com/watch?v=QjqpKtGNbQo).

---

## Modding the Self-Executable with Other EXTIO DLLs
If the executables do not work, you may need to manually change the ExtIO within the executable.
