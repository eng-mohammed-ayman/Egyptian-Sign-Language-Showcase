# Egyptian Sign Language Recognition

## Team graduation-project showcase, no source code

A Galala University AI engineering graduation project exploring Egyptian Sign Language gesture recognition and Arabic output. This repository documents Mohamed Ayman's contribution to the project using his own project materials. It is a documentation showcase; the team's implementation code is not published here.

## My contribution

Mohamed contributed to initial research, multi-model evaluation (LSTM vs. ConvNeXt), data refinement, Arabic text-rendering integration, dataset preparation and technical documentation. He reviewed model comparisons and system results. The trained model, inference engine and interface are team work.

## What the documented system does

The project materials describe a webcam-based pipeline:

1. Capture a gesture video sequence.
2. Extract pose and hand landmarks with MediaPipe Holistic.
3. Represent each frame with 75 three-dimensional landmarks, 225 features in total.
4. Process 30-frame sequences with a two-layer LSTM recognition model.
5. Map the predicted sign to an Arabic label for display, with text/speech output described in the project documentation.

The project explored several approaches. This summary focuses on the landmark/LSTM path.


## Team credits

The supplied graduation report credits Maryam Elgohary, Shahd Ahmed, Ahmed Ashraf, Mohamed Ibrahim and Mohamed Ayman, supervised by Dr. Mohamed Ghetas. The presentation uses a different form of Shahd's name, so the report form is retained here without guessing a correction.

## Original project materials

The full 22-page presentation deck and 53-page report are available on request as privacy-redacted PDFs. Team names and all original pages are retained; student IDs and photographic signer images are removed. They are not currently hosted in this repository.

These are the original project materials from the graduation project.

## Materials and scope

See [MATERIALS.md](MATERIALS.md) for the exact source materials used and what was intentionally left out.

- No source code, model weights, training data, private dataset records or implementation files are included.
- There is no hosted live demo. Presentation screenshots in the original materials illustrate the system.
- This was a graduation prototype and is not intended for medical, legal or other high-stakes interpreting.

## Publication boundaries

This repository contains only contribution-focused text. It does not copy another team's repository, paper or implementation, and it grants no new rights over team code, datasets or third-party material. No student IDs, signer photos or sample signer videos are republished. Privacy-redacted versions of the original report and presentation are available on request as team-membership and project-history evidence.
